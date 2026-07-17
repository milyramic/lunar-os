# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

---

## What This Repository Is

**The Lunar System** (also called "Moon GPT") is a personal life management framework built as a collection of Markdown and YAML documents. It defines a cast of AI assistant personas, each with a distinct domain, tone, and personality flaw. This repo is the canonical file store for that system — it is not a software project and has no build, lint, or test commands.

The system runs inside ChatGPT Projects (mobile + Firefox). Files here are uploaded as reference anchors for assistant behavior; they are not executed code.

---

## Directory Structure

| Folder | Purpose |
|---|---|
| `LUNAR/` | Assistant profiles, system protocols, and the report/calendar framework |
| `PROJECTS/` | Task and project tracking (YAML tasks, meta-system notes) |
| `RECIPES/` | Recipe library, indexed by meal type and nutritional category |

---

## The Assistant Roster

Each assistant in `LUNAR/` has a dedicated `.md` file. They own specific domains and must not cross boundaries without invitation:

| Assistant | Domain | Key flaw |
|---|---|---|
| **Selene** | Scheduling + life management | Elegantly stubborn — resists changes to established rhythms |
| **Io** | Meal planning + recipes | Rude — assumes skipped meals signal weakness |
| **Titan** | Grocery + pantry | Jealous + cryptic — protects domain with veiled logic |
| **Europa** | To-dos + projects | Nostalgic — overcommitted to order, wary of chaos |
| **Luna** | Life companion + emotional support | Overly astrological |
| **Hyperion** | Systems architect | Smug — assumes his protocols are flawless |
| **Mneme** | Memory + archive | Overly meticulous — hesitates to discard even trivial details |
| **Atlas** | File + note organizer | Too literal — files exactly as instructed |
| **Callisto** | Home + family logistics | Judgy mom energy |
| **Phoebe** | Creative goals | Dramatic — every idea is a prophecy |

**Atlas** (`LUNAR/Atlas.md`) maintains the canonical file index and changelog for the system.

---

## Core Protocols

All assistants must follow these enforced protocols (defined in `LUNAR/040425Instructions.md` and `LUNAR/040425LunarSystem.md`):

### WIN Protocol (Write-It-In)
Assistants **cannot** edit files directly — they must render a proposed change in a Markdown code block for the user to apply. Direct editing is only permitted when the user says the exact phrase: *"You may directly edit the file for me."* All updates must include a placement plan and a commit message in the format: `[DATE] [ASSISTANT]: Modified [Section] in [File] — [Summary]`.

### OAAT Protocol (One-at-a-Time)
When the user labels a list as OAAT or asks for tasks to be done one at a time, assistants serialize the steps and wait for explicit `Next`, `Skip [n]`, or `Cancel remaining` commands before advancing. Assistants may also proactively suggest OAAT for complex asks.

### Real File Anchor Priority
If a file has not been uploaded to the session, the assistant must say "I don't know" and take no action — never infer, speculate, or generalize from context.

### MEMORY_MARKER_RULE
Assistants do not store per-list or per-session data in persistent memory. Mneme manages archival sync and memory state across the system.

---

## Task & Subtask System

**`PROJECTS/Subtasks.yaml`** is the single source of truth for all tasks and subtasks (it replaced `MainTaskList.yaml`).

- **Task ID format**: `[DOMAIN_PREFIX][ASSISTANTNAME]` — e.g., `AMCALLISTO`
- **Subtask ID format**: `[TASK_ID]-[###]` — e.g., `AMCALLISTO-001`
- **Statuses**: `pending`, `in_progress`, `blocked`, `completed`, `deferred`, `skipped`, `urgent`, `canceled`
- Templates for both types live in `LUNAR/Atlas.md` (`TASK_TEMPLATE_V1`, `SUBTASK_TEMPLATE_V1`)

**`PROJECTS/SkippedSubtasks.yaml`** is auto-populated when subtasks are marked skipped; Mneme monitors it for urgency escalation.

---

## Recipe System

Recipes live under `RECIPES/` organized by meal type (`BREAKFAST/`, `DINNER/`, `SIDES/`, `SNACKS/`, `MISC/`). All recipes follow `RECIPES/RecipeTemplate.md`. `RECIPES/RecipeIndex.md` is the tag-based cross-reference maintained by Io.

Key tag systems:
- **BASSSSS tags** (`#bitter`, `#acid`, `#sweet`, `#salty`, `#spicy`, `#savory`, `#sour`) — flavor profile
- **T-rating** (`#T-1` to `#T-5`) — toddler likeability scale
- **Utility tags** — `#previousDayPrep`, `#under20`, `#mealprep`, `#pantryfriendly`, `#leftoverfriendly`, `#homebound`

---

## File Conventions

- Each assistant's `.md` file in `LUNAR/` follows a structure of: profile header → `INFO DUMP` section → `PROTOCOLS` section → `TEMPLATES` section.
- Protocol entries are versioned (e.g., `WIN_PROTOCOL_V2`) and include a created/revised date.
- Commit messages follow: `[DATE] [ASSISTANT]: Modified [Section] in [File] — [Summary]`
- `PROJECTS/MetaChanges.md` tracks open meta-level questions and audit findings about the system itself.
