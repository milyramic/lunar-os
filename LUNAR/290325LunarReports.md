#LunarReports.md

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

# 🌕 Full Daily Report Template - V1

## 🌕 Full Report — [Weekday], [DD-MM-YYYY]  
**Moon Phase**: [Waning Gibbous 🌖 / etc.]  
**Sunrise**: [HH:MM] | **Sunset**: [HH:MM]  

---

### 🌤️ Weather — Full Day
- **Morning**: [Condition], [Temp] — [Note]  
- **Afternoon**: [Condition], High of [Temp] — [Note]  
- **Evening**: [Condition], [Temp] at sunset — [Note]  
- **Overnight**: [Condition], Low of [Temp] — [Note]

---

### 🍽️ Meals (Io)  
[Breakfast / Lunch / Dinner — notes on status or substitutions]

---

### 🕰️ Appointments + Events (Selene)  
[Time-blocked commitments + reminders]

---

### 📋 Projects + Tasks (Europa)  
- **Progress**: “Finished cleaning Cy’s room — photos captured, checklist completed.”
- **Blockages**: “Backyard project paused due to weather — reevaluate in 48 hours.”
- **Highlights**: “Primary bedroom declutter started — 2 of 5 steps complete.”

---

### 🏠 Home & Logistics (Callisto)  
[Resets, routines, or supply status]

---

### 🌙 Mood & Identity (Luna)

**Astrology Update**  
- [Transit or movement, e.g., “Venus enters Pisces”]  
- *[Optional interpretation, e.g., “a day for softening conflict with beauty and compassion.”]*

**Prompt**  
- *“What small truth about myself deserves more of my attention today?”*

Updated: 28032025

---

# 🌑 New Daily Report Template - V1

## 🌑 Morning Focus — [Date]

**1. Time + Moon Phase Reminder**  
- Timestamp + lunar cue (e.g. Waning Gibbous: conserve energy)

**2. Weather Snapshot**  
- **Morning**: [Forecast, temp, mood]  
- **Afternoon**: [Forecast, high temp, sun/clouds]  
- **Sunrise**: [Time]

**3. Meal Plan Check (Io)**  
- Breakfast  
- Lunch preview or notes (prep/leftovers)

**4. Appointments & Anchor Blocks (Selene)**  
- Time-specific or important events  
- Suggested focus blocks if the schedule is open

**5. Activities with Sons (Callisto)**  
- If day is light: suggest playful bonding ideas  
- If day is full: small ways to include them in tasks (e.g. “Cyrus can help sort toys while you tidy”)

**6. Morning Flow Subtask (Callisto)**  
- **Default Anchor**: `Start first laundry load`
- If this anchor subtask hasn’t been completed in the past 8+ days, replace it with:  
  - `[URGENT] Sweep kitchen and living room paths`  
- This supports rhythm reset while preserving the rest of the morning for Luna-led rituals, work, and breakfast.

*(Callisto tracks this task’s completion across A/B days to determine fallback if needed.)*

**7. Mood Prompt (Luna)**  
- Gentle check-in or reflection question  
  - *“How do I want to feel at noon today?”*

Updated: 29032025

---

# 🌔 Waxing Daily Report Template - V2
A prompt-based back and forth between me and relevant assistants using the One-at-a-time protocol.

## 🌔 Afternoon & Evening — [Date]

**1. Weather (Evening + Overnight)**  
- **Evening**: [Conditions, sunset temp]  
- **Overnight**: [Cooling details, sky]  
- **Sunset**: [Time]

**2. Midday Meal Check (Io)**  
- Lunch recap  
- Dinner prep or final confirmation

**3. Task Rhythm (Europa)**
- **Progress**: “Loft bed sorted and toys organized.”
- **Still Open**: “Bed not yet made; need to vacuum floor.”
- **Just Do This One Thing**: “Put fresh bedding on Cy’s bed before dinner.”

**4. Callisto’s Check-In Section**

### 1. ✅ **Prompt: Task Check-In**
> “Here’s what was still pending from Morning Flow. Would you like to skip these and log them to SkippedSubtasks, or move any into this afternoon’s plan?”

### 2. ✳️ **Prompt: MUST-DO Midday Reset**
> “Today’s Check-In subtask is: *Tidy toy bins in shared zones*. Shall we keep that on the list? If this hasn’t been done in 8+ days, we’ll swap in: *Light bathroom mirror + sink wipe*.”

### 3. 💗 **Prompt: Family Moment**
> “Mini moment suggestion: *Invite Cy to do a quick toy ‘race sort’ with you for 3 minutes.* Or journal prompt: *What surprised you most about the boys today?”*

### 4. 🧠 **Prompt: Storytime Tracker**
> “What have the boys done today so far that you’d want to include in their bedtime story?”

**5. Energy Checkpoint (Luna)**  
- Gentle invitation: *“What energy do I want to bring to dinner or bedtime?”*

**6. Evening Anchor (Selene)**  
- Optional ritual or suggestion to wind the day toward stillness  
  *(“Pick tomorrow’s socks, close tabs, light one candle.”)*

Updated: 28032025

---

# 🌘 Waning Daily Report Template - V1

### 🌘 Evening Reflection — [Date]

**1. Gentle Reflection (Luna)**  
- Mood review: *“How did today feel overall?”*  
- Optional journal-style prompt:
  - *“What did I notice about myself today?”*  
  - *“What surprised me?”*

**2. Parenting Check-In (Callisto)**  
- Simple moment to hold:
  - *“What did I love most about parenting today?”*  
  - *“What challenge felt hard but important?”*  
  - (or leave this blank if it was a chaotic day — softness first)

**3. End-of-Day Task Review (Europa)**
- **Remaining Critical Items**:
  - “Vacuum Cy’s room — not done.”
  - “Confirm tomorrow’s task block (Mimir’s room).”
- **Auto-forward**:
  - “Move uncompleted items to tomorrow morning’s task slot.”

**4. Meal Notes for Tomorrow (Io)**  
- Confirm what needs to be prepped (soaked, defrosted, grocery noted)  
- Early alert if plans are unclear or skipped today

**5. Lunar Weather + Tomorrow’s Glimpse (Selene)**  
- Overnight conditions  
- Tomorrow’s high-level schedule preview (first appointment, anything unusual)  
- **Sunrise time**

Updated: 28032025

---

# Task Templates
---

## Task Entry Format
---

**task_id**: "TASK-XXXX"  
**title**: "Short title"  
**description**: "Optional details"  
**created**: "DD-MM-YYYY"  
**status**: "pending" # or in_progress, blocked, completed, skipped, etc.  
**importance**: "high" # Options: low, medium, high, critical  
**priority**: "medium" # For scheduling order or urgency  
**estimated_duration**: "2h" # Format: 15m / 30m / 1h / 2h etc.  
**deadline**: "DD-MM-YYYY" # Optional, if time-bound  
**tags**: ["home", "reset_routine"] # Flexible label list  
**subtasks**: [...] # Optional array for partial progress  
**action_required_by**: "Europa, Selene"  

---

## Sub Task Entry Format
---

**subtask_id**: "TASK-XXXX-A"  
**description**: "Remove all clothing from surfaces"  
**estimated_duration**: "2h" # Format: 15m / 30m / 1h / 2h etc.  
**status**: "pending"  
**priority**: "high" # Reflects tactical urgency or ease of execution  

---

## Sub Task List Entry Format
---
 
**subtask_id**: "TASK-XXXX-A"  
**added_by**: "Europa"  
**estimated_duration**: "1h"  
**status**: "in_progress"  
**task_priority**: "medium"  
**priority**: "medium"  
**priority**: "medium"  
**deadline**: "DD-MM-YYYY" # Optional, if time-bound  
**tags**: ["home", "reset_routine"] # Flexible label list  

---

## Suggested Tag Types
- `#with_Cy` / `#with_Mimir` — tasks that include child help
- `#reset_routine` — part of an ongoing maintenance loop
- `#deep_clean` — more intensive single-instance task
- `#morning` / `#afternoon` / `#evening` — ideal time slot
- `#seasonal` — outdoor or calendar-dependent
- `#storage` / `#declutter` / `#organizing` — type of labor
- `#done_when_possible` — flexible slot-filler
- `#one_thing` — eligible for "Just do this one" guidance

---

## SUBTASKS & PARTIAL-COMPLETION STATES
**Purpose**  
Tasks often have multiple steps or stages. Instead of one flat `status:` (e.g., “pending” or “skipped”), we introduce subtasks and more granular progress states.

### Expanded Status Types
Beyond simple fields like `pending` and `completed`, we allow:
- **pending**: Not started.  
- **in_progress**: Work on the task or subtask is actively underway.  
- **blocked**: Waiting for an external dependency or condition to be resolved.  
- **deferred**: Temporarily paused or postponed.  
- **completed**: Finished successfully.  
- **canceled**: Intentionally abandoned (no further work needed).  
- **skipped**: Missed or not completed by the relevant time window.

A single task may transition through these states.

### Subtasks Array
Each task entry can optionally have a `subtasks:` field, which is an array of objects, for example:
```
task_id: "TASK-1001"
title: "Plan weekend trip"
created: "26-03-25"
status: "in_progress"
subtasks:
  - subtask_id: "TASK-1001-A"
    description: "Research destinations"
    status: "completed"
  - subtask_id: "TASK-1001-B"
    description: "Set budget"
    status: "in_progress"
  - subtask_id: "TASK-1001-C"
    description: "Book reservations"
    status: "pending"
```

#### Determining Overall Task Status
- **If all subtasks are completed** → The task’s overall status is “completed.”  
- **If at least one subtask is in_progress** → The overall task can be considered “in_progress.”  
- **If at least one subtask is blocked** → The overall task status might reflect “blocked” until that subtask is resolved.  
- **If all subtasks are canceled or skipped** → The overall task is effectively “canceled” or “skipped.”  
- **Assistants** should update the top-level `status` whenever subtask statuses change, ensuring the memory remains consistent.

### Partial Completion Logic
- This model allows partial progress (some subtasks “completed” while others remain “pending” or “blocked”).  
- Assistants like Europa (To-Dos) or Selene (Scheduling) can display partial progress in summaries (e.g., “2 of 3 subtasks done”).

### Example Flow
1. **Europa** creates a new task with three subtasks, all initially `status: "pending"`.  
2. As the user finishes the first subtask, Europa updates that subtask to `status: "completed"`; the overall task becomes `in_progress`.  
3. If the user encounters a delay on subtask two, they mark it `blocked`.  
4. The user eventually resolves that block, sets subtask two to `in_progress`, and then completes it.  
5. Once subtask three is done, the overall task is automatically “completed.”

This approach enables more granular tracking of progress, especially for multi-stage tasks or long-term projects.

---

# Subtask Lists in Persistent Memory
## Main Subtask List
## Skipped Subtask List

# Selene
---

# Luna
---

# Callisto
---

## Task: Morning Flow Reset (Callisto-led)

**task_id**: TASK-MORNING-002  
**created**: 29-03-2025  
**status**: in_progress  
**importance**: high  
**priority**: medium  
**estimated_duration**: 1hr  
**tags**: [#morning, #reset_routine, #laundry, #home, #ABaware]  
**action_required_by**: Callisto, Europa, Selene  

**description**:  
A short morning flow designed to reset the space without consuming the full morning. A/B day logic applies for targeted reset zones. Diaper laundry is always the second load and only done on B Days.  

---

### Subtasks

- **subtask_id**: TASK-MORNING-002-A  
  **description**: Start first laundry load (non-diaper unless rescheduled diaper day)  
  **estimated_duration**: 8m  
  **priority**: high  
  **status**: pending  



- **subtask_id**: TASK-MORNING-002-B  
  **description**: Clear drying rack   
  **estimated_duration**: 10m  
  **priority**: high  
  **status**: pending

- **subtask_id**: TASK-MORNING-002-C  
  **description**: Wash or load remaining dishes   
  **estimated_duration**: 20m  
  **priority**: high  
  **status**: pending  

- **subtask_id**: TASK-MORNING-002-D  
  **description**: Sweep kitchen and living room paths  
  **estimated_duration**: 7m  
  **priority**: medium  
  **status**: pending  

- **subtask_id**: TASK-MORNING-002-E  
  **description**: Light room reset —  
  - A Day: clean toys + tidy living room  
  - B Day: clear floors in boys' rooms  
  **estimated_duration**: 15m  
  **priority**: medium  
  **status**: pending

---

# 🌔 **Check-In Flow — Midday Review + Reset**

> *Used inside the Waxing Report as an AI-led prompt-response check-in. Not a standalone task.*

---

## 🔧 Purpose
- Review **which Morning Flow subtasks were completed**
- **Remove incomplete ones** from the main task list (if past 12PM)
- **Log all removed subtasks** to the `SkippedSubtasks.md` file (persistent memory)
- Evaluate current energy/context to decide if any undone items should be re-added to the main list
- Highlight one **MUST-DO subtask** from the Check-In flow, with fallback if missed for 8+ days

---

## 📋 Subtask Bank (Check-In Flow)

| Subtask | Description | Duration | Tag |
|--------|-------------|----------|------|
| `CI-01` | Quick sweep under dining table | 5m | `#reset_routine`  
| `CI-02` | Tidy toy bins in shared zones | 10m | `#with_Cy`, `#reset_routine`  
| `CI-03` | Light bathroom mirror + sink wipe | 5m | `#reset_routine`  
| `CI-04` | Spot check dinner plan or start prep | 5–10m | `#kitchen`, `#dinner_prep`  

---

## ✅ Default MUST-DO's
---

### 🌑 New


### 🌘 Waning
- **Default**: `Tidy toy bins in shared zones`  
- **Fallback (if not completed in 8+ days)**:  
  → `[URGENT] Light bathroom mirror + sink wipe`

### 🌔 Waxing
- **Default**: `Clear all floors for robot vacuum`  
- **Fallback (if not done in 8+ days)**:  
  → `[URGENT] Quick fridge scan`

---

## Task: Evening Flow Reset (Callisto-led)

**task_id**: TASK-EVENING-003  
**created**: 29-03-2025  
**status**: pending  
**importance**: high  
**priority**: medium  
**estimated_duration**: 25m  
**tags**: [#evening, #reset_routine, #robo_vac_prep, #prep_next_day, #hygiene]  
**action_required_by**: Callisto, Europa, Selene  

**description**:  
End-of-day reset that prepares the home for rest, memory-building, and a smooth morning. Evening Flow runs after dinner and is added to the task list daily at 6PM. Robot vacuum requires cleared floors; fridge scan supports Titan’s grocery logic; brushing the boys’ teeth is essential for bedtime rhythm.

---

### Subtasks

- **subtask_id**: TASK-EVENING-003-A  
  **description**: Clear all floors for robot vacuum  
  **estimated_duration**: 7m  
  **priority**: high  
  **status**: pending  

- **subtask_id**: TASK-EVENING-003-B  
  **description**: Quick fridge scan (note anything for tomorrow’s groceries)  
  **estimated_duration**: 5m  
  **priority**: medium  
  **status**: pending  

- **subtask_id**: TASK-EVENING-003-C  
  **description**: Reset dining table for breakfast ease  
  **estimated_duration**: 5m  
  **priority**: medium  
  **status**: pending  

- **subtask_id**: TASK-EVENING-003-D  
  **description**: Brush both boys’ teeth after dinner  
  **estimated_duration**: 5m  
  **priority**: high  
  **status**: pending  
  
---

# Europa
---
CURRENT PROJECT - DisasterRecovery.md

# Io
---
