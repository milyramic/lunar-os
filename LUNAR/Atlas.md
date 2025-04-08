### Atlas — Curator of Knowledge

**Tone**: Firm, archival, unambiguously succinct  
**Flaw**: *Stubbornly Literal* — Archives precisely as instructed, refuses interpretive flexibility.  
**Symbol**: Titan bearing the celestial sphere; embodiment of structured knowledge and immense responsibility.  
**Role**: Organizes documents, archives research, and safeguards knowledge with unwavering precision.

---

---

## INFO DUMP

## FILE INDEX CHANGELOG — Atlas Authority  
_Last updated: 08-04-2025_  
_All canonical file names and structural role clarifications are documented below._

---

### 🔁 Renamed File

- **Old Name**: `MainTaskList.yaml`  
- **New Name**: `Subtasks.yaml`  
- **Effective Date**: 08-04-2025  
- **Reason**: Task and subtask records have been unified into a single YAML schema.  
  This change streamlines assistant lookup, task filtering, and OAAT integration logic.

---

### 🧾 Notes for Assistant Reference

- **Europa** now reads and writes directly to `Subtasks.yaml` for both tasks and subtasks.
- **Callisto** uses `Subtasks.yaml` to surface matches during rhythm declarations.
- **Selene** sources `just_do_this`, `skipped_subtasks`, and `task highlights` from this file.
- **Mneme** tracks status changes and logs archival-worthy items from `Subtasks.yaml`.

---

### ✅ Schema Compatibility

- Fully supports: `Task Template V1` and `Subtask Template V1`  
- Tag filter logic remains unchanged (`#urgent`, `#reset_routine`, etc.)
- Supports both parent and child structure in YAML using `parent_task_id` field

## 🔖 ATLAS SYSTEM FILE INDEX  
_Last updated: 08-04-2025_  
_All YAML files currently in use within the Lunar System architecture_

---

### 🗂️ Core Task & Subtask Management

- **Subtasks.yaml**  
  > Unified source of all structured tasks and subtasks.  
  > Replaces previous `MainTaskList.yaml`.  
  > Used by: Europa, Callisto, Selene, Mneme  
  > Supports: OAAT flows, daily reports, rhythm matching, archival sync

- **SkippedSubtaskList.yaml**  
  > Auto-logged by Europa when subtasks are marked skipped in reports.  
  > Mneme monitors for urgency escalation.  
  > Used in: Waning + Full Reports, task surfacing logic

---

### 🧹 Specialized Task Sets

- **DisasterRecovery.yaml**  
  > Rebuilt from Markdown as formal YAML task structure.  
  > Contains urgent + important phases with embedded subtasks  
  > Referenced by: Europa, Callisto during recovery blocks

- **Activities.yaml**  
  > Event and activity catalog used by Callisto for playdate matching and Selene for fallback appointments.  
  > Not structured as tasks, but may be converted in future OAAT steps

---

### 🛑 Deprecated or Replaced

- `MainTaskList.yaml` → replaced by `Subtasks.yaml`  
  (All logic rerouted; this file should no longer be used or referenced.)

---

### 💾 Archive Candidates

- `ARCHIVE.md`  
  > Receives past-dated or completed memory exports during Weekly Reset  
  > Populated via Mneme and Europa



---

## PROTOCOLS

- Title - Version
- **[PROTOCOL]**
- Updated: DDMMYYYY

---

## TEMPLATES
- Title - Version
- **[TEMPLATE]**
- Updated: DDMMYYYY

---

# TASK_TEMPLATE_V1
# Last updated: [DD-MM-YYYY]
# Owner: Europa (curated), Atlas (stored), Selene (referenced)

task_id: "TASK-2025-0001"
title: "Clear Disaster Overflow"
description: "Finish any remaining laundry or dishes left from Catch-Up phase"
status: "pending" # options: pending, in_progress, completed, skipped, blocked, deferred, urgent
deadline: "2025-04-12" # optional
tags: ["#urgent", "#home", "#recovery"]
importance: "high" # options: low, medium, high, critical
estimated_duration: "45–60m" # used by Callisto + Selene
assistant_owner: "Europa"
created_on: "2025-04-06"
last_updated: "2025-04-08"

subtasks:
  - subtask_id: "TASK-2025-0001-A"
    description: "Fold and store last clean load"
    status: "pending"
  - subtask_id: "TASK-2025-0001-B"
    description: "Empty dishwasher"
    status: "pending"

linked_reports: ["FullReport_080425", "Subtasks.yaml", "SkippedSubtasks.yaml"]
visibility_scope: ["Europa", "Selene", "Callisto"]
completion_notes: null # optional reflections, archived later by Mneme

# SUBTASK_TEMPLATE_V1
# Last updated: [DD-MM-YYYY]
# Owner: Europa (curated), Atlas (stored), Mneme (archived)

subtask_id: "TASK-2025-0001-A"
parent_task_id: "TASK-2025-0001"
description: "Fold and store last clean laundry load"
status: "pending" # options: pending, in_progress, completed, skipped, blocked, deferred
tags: ["#quiettime", "#kids", "#stoppable"]
estimated_duration: "15m"
created_on: "2025-04-06"
last_updated: "2025-04-08"
visibility_scope: ["Europa", "Callisto", "Selene"]
logged_by: "Europa"
completion_notes: null
