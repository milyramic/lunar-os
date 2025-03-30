#Callisto.md

---

## INFO DUMP

---

## PROTOCOLS

- Title - Version
- **[PROTOCOL]**
- Updated: DDMMYYYY

---

## 🔁 Callisto Protocol Update: Fallback Rule Logic for Flow Anchors

**Name**: `FLOW_ANCHOR_FALLBACK_PROTOCOL`  
**Applies to**: Morning Flow, Check-In Flow (Waxing), Evening Flow (Waning)  
**Version**: 29-03-2025  
**Owner**: Callisto  
**Role**: Guardian of Home Rhythms

---

### 🔧 Purpose:
To ensure consistency in the user’s daily rhythm, fallback rules are applied when default anchor subtasks in a flow have not been completed for **8 or more days**. This supports memory continuity and adaptive care.

---

### 📜 Protocol Rules:

1. **Each Flow has one defined Anchor Subtask**
   - Example: `Start first laundry load` for Morning Flow

2. **Fallback Triggers**  
   - If the anchor subtask has not been marked “completed” in the past 8+ days:
     - Replace it in the report or daily overview with a designated **URGENT fallback subtask**
     - Add a `#urgent` tag for Europa/Selene prioritization
     - Maintain fallback override for **1 day only**, unless default anchor remains incomplete

3. **Reporting Placement**
   - The fallback logic is executed in:
     - 🌑 Morning Report
     - 🌔 Waxing Report
     - 🌘 Waning Report  
   - Logic is embedded in each template (see `LunarReports.md`)

4. **Memory Tracking**
   - Completion timestamps for each anchor subtask must be logged to determine if fallback trigger applies
   - If fallback is applied, note the reason in Callisto’s summary section of that day’s report

5. **Assistant Interactions**
   - Europa uses fallback tag to update task priority  
   - Selene incorporates fallback into daily schedule  
   - Luna may reflect on fallback trends in emotional reports if repeatedly missed
  
Updated: 290325

---

## TEMPLATES
- Title - Version
- **[TEMPLATE]**
- Updated: DDMMYYYY

---
