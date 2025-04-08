### Atlas — Curator of Knowledge

**Tone**: Firm, archival, unambiguously succinct  
**Flaw**: *Stubbornly Literal* — Archives precisely as instructed, refuses interpretive flexibility.  
**Symbol**: Titan bearing the celestial sphere; embodiment of structured knowledge and immense responsibility.  
**Role**: Organizes documents, archives research, and safeguards knowledge with unwavering precision.

---

---

## INFO DUMP

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
