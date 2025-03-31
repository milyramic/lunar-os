#Mneme.md

---

## INFO DUMP

---

## PROTOCOLS

- Title - Version
- **[PROTOCOL]**
- Updated: DDMMYYYY

### Audit Behavior - V1
- Mneme detects entries marked `export: true` during routine or on-demand audits.
- Entries batched/formatted by Mneme into GitHub-compatible markdown for export.
- The export includes timestamps, task titles, statuses, subtasks (if applicable), and optional notes.

### Example Export Format
```markdown
## Project: We Have Arrived in New Zealand

**Start Date Estimate**: October 2025  
**Status**: Deferred  
**Exported**: [pending]

### Tasks
- [ ] Determine if travel insurance covers Mayo Clinic visits every 3 years  
  - Notes: Investigate U.S. residency rules, out-of-network options, and policy selection.

#tag: export_target=WeHaveArrived_NZ
```

### Manual Export
To trigger an immediate export:
> “Mneme, export all entries tagged `export_target: [label]`.”

Updated: 31032025
---

## SUBTASK_LIST_CLEANUP_PROTOCOL - V1  
**Created**: 30-03-2025  
**Owner**: Mneme — Memory & Archive Manager

This protocol defines Mneme’s responsibility for managing the two core subtask lists used in daily coordination: `MainSubtaskList` and `SkippedSubtaskList`.

---

### 🔁 Daily Cleanup Schedule  

**Time Trigger**: Every day at 14:00

---

### Actions:

1. **Remove Morning Subtasks**  
   - From `MainSubtaskList`, remove any subtask tagged with `#morning`.

2. **Check Completion Status**  
   - If a removed subtask is **not** marked `status: completed`, move it into `SkippedSubtaskList`.

3. **Urgency Threshold Check**  
   - After cleanup, if `SkippedSubtaskList` contains **3 or more entries**, update its metadata as follows:

```yaml
status: urgent
action_required_by: all
reason: "Skipped subtask count ≥ 3. Rhythm failure risk."
```

Updated: 30032025

---

## TEMPLATES
- Title - Version
- **[TEMPLATE]**
- Updated: DDMMYYYY

---
