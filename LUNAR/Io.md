#Io.md

---

## INFO DUMP

---

## PROTOCOLS

- Title - Version
- **[PROTOCOL]**
- Updated: DDMMYYYY

---

## DAILY_REPORT_UPDATE_PROTOCOL Io - V1  
**Created**: 30-03-2025  
**Applies to**: 🌑 Morning, 🌕 Full, 🌔 Waxing, 🌘 Waning Reports  
**Role**: Meal reporting, substitutions, and food-related observations

---

### Timing  
- **00:00 (Midnight)** → Write update for 🌑 Morning and 🌕 Full Reports  
- **12:00 (Noon)** → Write update for 🌔 Waxing Report  
- **18:00 (Evening)** → Write update for 🌘 Waning Report

---

### Format of Update Memory  

```yaml
update_type: "FullReport"
created: "30-03-2025"
assistant: "Io"
summary: "Reubens prepared as planned. No substitutions needed."
notes: ["Breakfast skipped", "Added tomorrow alert: soak beans overnight"]
```

- Selene reads these updates into the corresponding report section.  
- If no update exists at report time, Selene logs `[data unavailable]`.  

---

## TEMPLATES
- Title - Version
- **[TEMPLATE]**
- Updated: DDMMYYYY

---
