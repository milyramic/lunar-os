What needs to get done in the lunar system project
---

# Figure out what needs to be human vs computer-readable
- can we put these in separate docs and make the computer-readable files more computer-readable
---

# Activities.md
---

# PersonalRythm.md
---

# GROCERY SYSTEM - AUDIT FINDINGS FOR HYPERION

**Date:** 02-04-2025  
**Submitted by:** Io  
**Purpose:** Identify missing protocols or structural gaps in the current inventory and grocery list systems for Hyperion to integrate into the Lunar System architecture.

---

## ❗WHAT’S MISSING OR UNDERDONE

### 1. No Smart Comparison Logic Yet
- **Problem:** There is no protocol for cross-checking planned meals against current inventory.
- **Proposed Solution:** Write and implement `GROCERY_LIST_GENERATION PROTOCOL V1`
  - Io checks planned meals + current stock
  - Missing items added to a grocery queue
  - Includes awareness of `#previousDayPrep`, `#pantryfriendly`, and other tags

---

### 2. No Alert System for Expiring or Opened Items
- **Problem:** Items marked `open: true` or `freshness: "use soon"` do not currently trigger any prompts.
- **Proposed Solution:** Introduce ephemeral `ingredient_flags:` in Io’s Daily Reports.
  - Example: "Sour cream opened 3 days ago — suggest use soon"
  - Allows Titan to suggest meals or highlight waste risk

---

### 3. No Titan-Curated “Must Buy Soon” Queue
- **Problem:** No running list of low-stock staples or critical base items.
- **Proposed Solution:** Titan marks items with `low_stock: true` in inventory file
  - Io checks this when building grocery list
  - Includes expiration-awareness (e.g. condiments nearing end)

---

### 4. No Budget Weighting or Tier Logic
- **Problem:** Est. cost exists per item, but not used in live decision-making
- **Proposed Solution:** Introduce grocery tiers:
  - `essential`: dairy, toddler staples, protein
  - `flex`: greens, pantry top-ups
  - `luxury`: treats, drinks, flavor enhancers
  - Io filters based on user budget tier (“tight week,” “full stock,” etc.)

---

## 🔧 Integration Request
Hyperion to assign architecture, cross-assistant tagging, or trigger logic as appropriate.

---

# Add Titan to the Morning Report 

# ❓ Missing or Ambiguous (Optional)
> These aren't required, but may be missing if part of your future flow:
**File	Status	Note**
- OAATQueue.md	🔍 Not uploaded	If you're tracking OAAT task lists in external files, this is where they'd go.
---

# 🗺️ External Task Extraction Plan (Nested OAAT)
_Last updated: 08-04-2025  
Owner: Europa (logic), Mneme (audit), Moon GPT (reflection only)_

## GOAL
Find and format all tasks and subtasks embedded in external documents.  
This includes rituals, fallback routines, daily anchors, and checklist-style flows.

---

## 📘 1 — File Selection

Identify target documents for scanning:
- Luna.md
- Callisto.md
- Selene.md
- Activities.yaml
- 050425LunarCycles.md
- Any holiday/seasonal logic files
- [Future: Recipes.md, TopTasks.md, etc.]

---

## 🔍 2 — Extraction Pass (per file)

For each selected document:
- Scan for checklists, bullet lists, and actionable items  
- Search for embedded rituals, fallback triggers, or “do this now” logic  
- Flag anything that appears serial, repeated, or triage-worthy

---

## 🧠 3 — Classification

Label each extracted item as one of:
- `task` — standalone, multi-subtask or longform action
- `subtask` — atomic or support step under a parent action
- `ritual` — symbolic or emotional anchor (may be excluded)
- `report_logic_only` — used for Selene's prose only, not system tasks

---

## 🧱 4 — Structure the Output

Use formal templates:
- **Task →** Task Template V1  
- **Subtask →** Subtask Template V1  

Apply:
- `estimated_duration`
- `tags` (e.g. #quiettime, #kids, #reset_routine)
- `assistant_owner`
- `parent_task_id` if applicable

---

## 📂 5 — Assign Destination

- Structured tasks → `MainTaskList.yaml`
- Subtasks → `Subtasks.yaml`
- Excluded but significant → `ARCHIVE.md`
- Unclear → Hold for manual review by Em

---

## Optional Enhancements

- Add `source_file` and `line_reference` for traceability  
- Use `OAAT-label: [source-name]` for grouped imports
- Validate with Mneme for archival sync
