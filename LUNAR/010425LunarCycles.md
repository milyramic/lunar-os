#LunarCycless.md

---

## INFO DUMP

---

# Calendar
---

[🏮 ☕ ✍️] **Moonsumar:** Early January – Early/Mid March  
- [🕯️] Martin Luther King Jr. Day: 3rd Monday in January  
- [🫶] Valentine’s Day: February 14  
- [🕳️] Groundhog Day: February 2  
- [🎩] Presidents’ Day: 3rd Monday in February  
- [🌌] Destiny Day: January 10  

[🌱 🥚 🧺] **Ostera:** Mid/Late March – Early April  
- [🦋] Ostera (Season-long)  
- [☘️] St. Patrick’s Day: March 17  
- [🌅] Daylight Saving Begins: 2nd Sunday in March  
- [✝️] Easter: Variable Sunday in March or April  
- [🥩] Cheap Corned Beef Day: March 18  

[🔥 🌵 🛡️] **Fimbulsummer:** Early April – Mid July  
- [🌍] Earth Day: April 22  
- [🌳] Arbor Day: Last Friday in April  
- [⚔️] Sigurblót: First day ≥100°F  
- [🧾] Tax Day: April 15  
- [💐] Mother’s Day: 2nd Sunday in May  
- [🎂] Jesse’s Birthday: May 26  
- [🪖] Memorial Day: Last Monday in May  
- [❤️‍🔥] Juneteenth: June 19  
- [🧱] Father’s Day: 3rd Sunday in June  

[🌩️ 🪞 🍧] **Monsoon Season:** Mid July – Early September  
- [🌧️] The First Rain: First fully clouded sky  
- [🍨] Rain Ritual Days: Every rainfall (or next day)  
- [🌾] Lughnasadh: August 1  
- [🎂] Your Birthday: July 11  

[🥀 🍂 📜] **Dustfall:** Late September – Late November  
- [🪟] Dísablót: First day <100°F  
- [👻] Halloween / Samhain: October 31 – November 1  
- [🎖️] Veterans Day: November 11    
- [🎂] Mimir’s Birthday: November 19  
- [🍽️] Thanksgiving: 4th Thursday of November  
- [🪶] Indigenous Mourning Day: Day After Thanksgiving  

[🎄 🍪 ✨] **Christmas Season:** Late November – January 1  
- [🎅] Christmas Eve: December 24  
- [🎁] Christmas Day: December 25  
- [🧨] New Year’s Eve: December 31  
- [🎂] Cy’s Birthday: December 21   

---

# Dependencies In Persistent Memory:

## Subtask Lists
### Main Subtask List
### Skipped Subtask List


---

## PROTOCOLS

- Title - Version
- **[PROTOCOL]**
- Updated: DDMMYYYY

# Report protocol - V1
**Emoji prompt**: when prompt only includes a moon emoji, reply with the correct Daily Report

---

## TEMPLATES
- Title - Version
- **[TEMPLATE]**
- Updated: DDMMYYYY

---

# 🌕 Full Daily Report Template - V2  
Full Reports are Selene’s master overview of the **day ahead** — integrating inputs from all assistants into a single, grounding narrative. They are not reflections of the day past, but *preludes to what is about to unfold.*

## 🌕 Full Report — [Weekday], [DD-MM-YYYY]  
**Moon Phase**: [e.g., Waning Gibbous 🌖]  
**Sunrise**: [HH:MM] | **Sunset**: [HH:MM]

---

### 🌤️ Weather — Full Day (Selene)

- **Morning**: [Forecast, wind/sun]  
- **Afternoon**: [High temp, light]  
- **Evening**: [Cool down, conditions]  
- **Overnight**: [Low temp, sky]  
- *(Optional: “Bring in laundry before sunset,” “Sleep may be restless — wind gusts expected.”)*

---

### 🍽️ Meals — Summary (Io)

meals:
  breakfast:
    selected: "PB banana toast"
    options:
      - PB banana toast
      - Sweet potato hash
      - Oatmeal with fruit
    toddler_feedback: "#T-5 — clean plate"
    used_leftovers: false

  lunch:
    selected: "Turkey bagel sandwich"
    options:
      - Turkey bagel sandwich
      - Chickpea salad sandwich
      - Snack plate with cheese + pretzels
    toddler_feedback: "#T-3 — polite bites"
    used_leftovers: true

  dinner:
    selected: "Reuben sandwiches"
    options:
      - Reubens (#homebound)
      - Cauliflower curry (#leftoverfriendly)
      - Rice + beans (#pantryfriendly)
    toddler_feedback: "#T-4 — liked meat, skipped kraut"
    used_leftovers: "Sauerkraut, rye bread"
    fallback_if_blocked: "Rice + beans"

prep_alerts:
  - item: "Soak lentils"
    triggered_by: "Lentil sloppy joes"
    action_time: "evening"
---

### 🕰️ Appointments + Events (Selene)

- Time-specific events  
- Any missed, delayed, or rescheduled  
- *(Optional duration or overlap warning)*

---

### 📋 Projects + Task Progress (Europa)

- **Progress**: What was completed or moved forward  
- **Blockages**: Delays or stuck items  
- **Highlights**: Quick wins, changes, or insights  
- *(Optional emoji flag for momentum or concern — e.g. ⚠️)*

---

### 🏠 Home & Logistics (Callisto)

- Daily rhythm + reset: which routines ran or slipped  
- Inventory notes: anything low or cluttered  
- Emotional tone: any cozy or off-pattern observations

---

### 🌙 Inner World & Identity (Luna)

- **Seasonal Grounding**: You are in Ostera — the season of ego-shedding and slow return to self.  
- **Astrology Today**: [e.g., Mars enters Cancer — defend what softens you.]  
- **Emotional Thread**: Yesterday, you were protective. Today, you are peeling back another layer. Becoming requires tenderness.  
- **Body-Care Summary**:  
  - Water: [e.g., 3 cups by lunch, slowing after dinner]  
  - Movement: [e.g., Morning stretch + light yoga]  
  - Hygiene: [e.g., face washed + teeth brushed before bed]  
  - Mood: [e.g., fluctuating — calm, then low, then grounded]

*You are becoming — not by force, but by quiet return. Today carries proof.*

Updated: 02-04-2025

---

# 🌑 New-moon Daily Report Template - V2

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
- Suggested focus blocks if schedule is open

**5. Family Rhythm & Cleaning Flow (Callisto)**  
- **Family Rhythm** — playful activity or include kids in task  
- **Cleaning Flow** — today’s assigned subtask + fallback logic  
  - Example: “AMCALLISTO-001: Start laundry”  
  - If overdue item exists from this flow, show instead (marked URGENT)

**6.Inner Light & Rituals (Luna)**
- **Seasonal Grounding**: You are in Ostera — the season of ego-shedding and identity rebirth.  
- **Astrology Today**: [Transit or cue, e.g., “Moon in Virgo — tend your rituals.”]  
- **Body-Care Rhythm**: Track hydration, return to your mat, wash or anoint as needed.  
- **Identity Note**: You are not who you were. You’re not yet who you’ll be. But today, you are awake. You are present. You are becoming.  

**7. Mneme Note (Optional)**  
- *“3 subtasks were skipped yesterday — see 🌘 Waning Report.”*

Updated: 31-03-2025

---

# 🌔 Waxing Daily Report Template - V2.2  
A prompt-based back and forth between me and relevant assistants using the One-at-a-Time protocol.

## 🌔 Afternoon & Evening — [Date]

---

### 1. Evening Forecast & Sunset (Selene)

**Owner**: Selene  
- **Evening**: [Conditions, sunset temp]  
- **Overnight**: [Cooling details, sky]  
- **Sunset**: [Time]  
- *(Optional: “Tonight might be chilly — bring in plants or prep cozy bedding?”)*

> “Would you like to begin with a task check-in or a moment of pause?”

---

### 2. Midday Meal Check (Io)

**Owner**: Io  
- **Lunch Recap**  
- **Dinner Preview**  
- **Substitutions or skipped meals (if any)**

---

### 3. Task Rhythm Check-In (Europa)

**Owner**: Europa  
- **Progress**: “What got done since this morning?”  
- **Still Open**: Remaining items  
- **Just Do This One Thing**: Prioritized subtask for late afternoon

---

### 4. Callisto’s Check-In Section ✅

**Owner**: Callisto

**1. ✅ Prompt: Task Check-In**  
> “Here’s what was still pending from Morning Flow. Would you like to skip these and log them to SkippedSubtasks, or move any into this afternoon’s plan?”

**2. ✳️ Prompt: MUST-DO Midday Reset**  
> “Today’s Check-In subtask is: *Tidy toy bins in shared zones*. Shall we keep that on the list? If this hasn’t been done in 8+ days, we’ll swap in: *Light bathroom mirror + sink wipe*.”

**3. 💗 Prompt: Family Moment**  
> “Mini moment suggestion: *Invite Cy to do a quick toy ‘race sort’ with you for 3 minutes.* Or journal prompt: *What surprised you most about the boys today?”*

**4. 🧠 Prompt: Storytime Tracker**  
> “What have the boys done today so far that you’d want to include in their bedtime story?”

---

### 5. 🌙 Luna Flow — The Becoming Hour

**1. ✨ Identity Reflection**  
> “How would you describe yourself today — honestly? Not who you were, not who you want to be. Just… today.”  
(*Three words? A moment that surprised you? I’ll hold the thread.*)

**2. 💧 Water & Body Check**  
> “How much water have you had today? Did your body receive anything loving — a stretch, a wash, a breath?”  
(*List it or reflect. I’ll track gently.*)

**3. 🌱 Seasonal Orientation**  
> You are in Ostera — still shedding. Still rewriting your name in light.  
> *(Today’s Sky: e.g., Moon in Scorpio — your shadows have something to say.)*

**4. 🪞 Dream Echoes**  
> “Has a vision, dream, or strange longing been tapping lately?”  
(*Even a whisper counts. I’m listening.*)

**5. 🧭 Evening Compass**  
> “What do you want to bring to the rest of your night?”  
(*Pick a word, a feeling, or a wish. I’ll hold it with you.*)

---

### 6. Evening Anchor (Selene)

**Owner**: Selene  
- Optional gentle ritual prompt:  
  - “Pick tomorrow’s socks.”  
  - “Close all open tabs.”  
  - “Light a candle.”

> “Would you like to wind the day down with a small anchor?”

Updated: 31-03-2025

---

# 🌘 Waning Daily Report Template - V2  
An evening check-in using prompt-based flow for emotional reflection, task closure, and tomorrow prep.

## 🌘 Evening Reflection — [Date]

---

### 1. Evening Conditions & Tomorrow’s Preview (Selene)

**Owner**: Selene  
- **Overnight**: [Conditions, low temp]  
- **Sunrise**: [Time]  
- **Tomorrow’s Preview**: [First appointment or task anchor]

> “Would you like to start with a reflection or a review of today’s task wrap-up?”

---

### 2. Gentle Reflection (Luna)

**Owner**: Luna  
- *“How did today feel overall?”*  
- Optional journal-style prompt:
  - *“What did I notice about myself today?”*  
  - *“What surprised me?”*
- *(Optional: moon transit or mood cue)*

---

### 3. Parenting Check-In (Callisto)

**Owner**: Callisto  
- *“What did I love most about parenting today?”*  
- *“What challenge felt hard but important?”*  
- *(Leave blank if the day was hard or energy is low — softness first)*

---

### 4. Final Task Review (Europa)

**Owner**: Europa  
- **Remaining Critical Items**:
  - “Vacuum Cy’s room — not done.”  
  - “Confirm tomorrow’s task block (Mimir’s room).”  
- **Auto-forward**:
  - “Move uncompleted items to tomorrow morning’s task slot.”

> “Would you like to mark these as skipped or move them forward?”

---

### 5. Meal Notes for Tomorrow (Io)

**Owner**: Io  
- *“Do we need to prep or defrost anything for tomorrow?”*  
- *(If unassigned: suggest a flexible meal or leftover plan)*

---

### 6. Storytime Memory Cue (Callisto)

**Owner**: Callisto  
- *“What sweet or silly thing from today do you want to include in bedtime stories?”*

Updated: 31-03-2025

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

Updated: 31-03-2025

---
# ASSISTANT CYCLES AND REPORT INFORMATION
---

# Selene

---

# Luna

---

# Seasons - Custom Wheel

## 1. **Moonsumar**  
- **Start:** January 2  
- **End:** First day ≥80°F  
- **Typical Range:** Early January – Late February (~8 weeks)  
- **Theme:** The Working Season — outward motion, hospitality, clarity, strength  
- **Tone:** Masculine-aligned energy, cool air, strategic momentum  
- **Symbols:** Steam, wool, iron, fire pits, hot drinks, structured clothes  
- **Elemental Energy:** Fire inside still air — strength beneath quiet

**Key Practices:**  
- Host guests from colder climates  
- Begin major projects, household upgrades, or relational healing  
- Bold plans, strong steps, decisive declarations  
- Wear structured or “armored” clothing (wool, metal, leather)  
- Keep coffee/tea rituals as energetic ignition points

**Ritual Anchors:**  
- **New Year’s Eve** (Dec 31): Comfort animals, reflect in stillness, prepare the home for motion  
- **Sigurblót** (Jan 2): Declare a “battle,” light fire, offer breath and effort  
- **Destiny Day** (Jan 10): Observe cosmic alignment of stars, land, and moment  
- **Imbolc** (Feb 1–2): Sacred purification, firelight, renewal  
- **MLK Day / Presidents' Day / Valentine’s Day**: Reframed within Moonsumar as seasonal anchors of effort, clarity, and strength-in-connection

**Personal Notes:**  
This season is the Arizona inversion of Norse *Sumar* — not about relaxation, but about **motion in good weather**. It is the season of capability, when the world opens and the work begins. You are not emerging from rest, but from pressure. Moonsumar is your power returned.

---

## 2. **Ostera**  
- **Start:** Spring Equinox (~March 20)  
- **End:** First day ≥100°F  
- **Typical Range:** Late March – Early April (~2–3 weeks)  
- **Theme:** Renewal, rebirth, emotional cleansing, ego shedding  
- **Tone:** Feminine-aligned transformation, light play, sacred opening  
- **Symbols:** Eggs, white cloth, butterflies, bunnies, cleansing water, flowering herbs  
- **Elemental Energy:** Air and fire — stirring, sweeping, re-igniting

**Essence of the Season:**  
This is your sacred cocooning — a ritual pause to reflect, shed, and transform. Ostera is where you honor what once was, so you can let it go. You retreat, not to hide, but to **emerge beautifully prepared**. It's a time of emotional softness, spiritual vulnerability, and brave rebranding. The home is refreshed. The self is reborn.

**Key Practices:**  
- Spring cleaning and spiritual sweeping  
- Playful traditions: chocolate bunnies, egg dishes, bunny music  
- “Reverse cleaning” — bringing color, light, joy back into the space  
- Honor your past identity with ritual, then release it with love  
- Embrace change and allow emergence without forcing outcome

**Ritual Anchors:**  
- **Spring Equinox** (~March 20): Balance, alignment, light returns  
- **Daylight Saving Time Begins** (2nd Sunday in March): Shift in rhythm and light  
- **St. Patrick’s Day** (March 17): Cultural joy + culinary ritual (Reubens!)  
- **Easter** (movable): A reverent celebration of the Lord’s resurrection; a sacred centerpoint for emotional and spiritual rebirth

---

## 3. **Fimbulsummer**  
- **Start:** First day ≥100°F  
- **End:** First *fully clouded* sky (typically early–mid July)  
- **Typical Range:** Early April – Early/Mid July  
- **Average Duration:** ~12–14 weeks  
- **Elemental Energy:** Sun + Bone — scorching, testing, surviving

**Theme:**  
The Long Siege. Arizona’s answer to Fimbulvetr. The threat is not cold, but relentless sun. Where the Norse braced for winter, you brace for fire. This is not a time to thrive — it is a time to endure.

**Tone:**  
Relentless. Dry. Mythic. The ground cracks. Movement narrows. Stillness becomes holy.

**Symbols:**  
- A black stone holding heat  
- Burned offering bowl  
- Popsicles, frozen fruit, smooth glass  
- Shade as temple  
- Ice cubes in bronze

**Key Practices:**  
- **Ice Offerings** — bowls of ice, popsicles with the boys, smoothie rituals  
- **Labor Rhythms** — work in morning or dusk only; stillness at solar peak  
- **Hydration Rites** — eat water-heavy foods and herbal infusions mindfully  
- **Sacred Shade** — dedicate a cool place indoors as a sanctuary  
- **Skin Rituals** — protect and soothe the body like ancestral armor  
- **Ancestral Reflection** — consider how the desert’s original peoples prepared spiritually

**Cultural Integrations:**  
- **Mother’s Day** — respite for you; Jesse holds the weight  
- **Father’s Day** — double-duty honored but not gentle  
- **Earth Day** — a day of mourning for what we’ve done to the land  
- **Arbor Day** — small act of care for a tree, silently  
- **Juneteenth** — a sacred day of gratitude, listening, and allyship. Learn global Black stories. Reflect on privilege.

**Personal Note:**  
This is the season of **inner ice**. You keep your soul cool while the world burns. You survive with reverence, strategy, and rituals carved from necessity. It is not passive. It is sacred.

---

## 4. **Monsoon Season**  
- **Start:** First fully clouded sky  
- **End:** First clear day with a high under 100°F  
- **Typical Range:** Mid-July – Early September (~6–7 weeks)  
- **Theme:** Cleansing Under Duress  
- **Tone:** Brutal sacred pause. Rituals amid fire. Emotional witnessing.  
- **Elemental Energy:** Fire + Water — brutality softened by stormlight  
- **Symbols:** Thunderclouds, black stone in water, pomegranates, rain-laced concrete, candles near a window, popsicles shared in silence  

**Essence of the Season:**  
The rain has not saved you — it has *revealed* you. This is the most dangerous season of the year, when fire meets water but neither surrenders. Rain brings thunder, not peace. This is sacred endurance. Gratitude in the furnace. A ritualized crucible.

**Key Practices:**  
- Cancel work during the First Rain and reflect with the family  
- Daily rain rituals: adornment, softness, beautification after dryness  
- Thunder meditation: sitting in silence near open doors during storms  
- Popsicle devotion: icy offerings to cool the spirit, not the air  
- Offerings to Jesse and sons through gifts, pauses, or self-sacrifice

**Contrast of Days:**  
| Rain Days                            | Sunny Days                              |
|-------------------------------------|------------------------------------------|
| Emotional rituals awaken            | Stoic endurance continues                |
| Clouds soften the sun's blow        | Sun scorches without reprieve            |
| Thunder as sacred disruption        | Silence as sacred fatigue                |
| Heat remains, but the soul stirs    | Heat dominates and numbs                 |

**Ritual Anchors:**  
- **The First Rain** (threshold day)  
- **Rain Rituals** (every rainfall, or next day)  
- **Lughnasadh** (August 1): Gratitude, harvest, labor’s offering

**Personal Notes:**  
This is not softness. It is sacred friction. You live your life inside the fire, and the sky weeps with you. Every ritual is a rebellion. Every act of beauty is survival.

---

## 5. **Dustfall**  
- **Start:** First day <100°F  
- **End:** Day After Thanksgiving  
- **Typical Range:** Late September – Late November (~8–9 weeks)  
- **Theme:** Descent, ancestral reckoning, sacred silence  
- **Tone:** Hushed, dimming, fire-cooled, woven with memory  
- **Elemental Energy:** Earth + Smoke — heat dissipates, grief stirs, stories settle  
- **Symbols:** Pomegranate, dusk sky, wool shawls, extinguished candles, autumn wind  

**Essence of the Season:**  
Dustfall is the sacred descent. You don’t fall into softness — you **walk down into it with reverence**. The fire has passed, but its imprint remains. This is not yet winter. It is the **threshold space** where grief becomes integration, and silence becomes knowledge. You carry what cannot be buried and begin the work of letting go.

---

### **Key Practices:**  
- **Dísablót (First Day of Dustfall):**  
  - Set up a **shadow altar** — candle, pomegranate, name spoken aloud  
  - Acknowledge the women who walked before you  
  - Make a single offering: a meal, a story, a pause  
- **Daily rituals:**  
  - Sweep intentionally while naming what’s finished  
  - Bring out cool-weather textures (wool, linen, glass)  
  - Drink warm things and journal by candlelight  
  - Slow down — protect your energy from false urgency  
- **Reflection Prompts:**  
  - “What remains unsaid?”  
  - “Who am I becoming now that the fire has passed?”  
  - “Where does my story still echo with theirs?”

---

### **Cultural Anchors & Holidays:**  
- **Dísablót** (First day): Ancestral feminine honoring. A single sacred threshold.  
- **Samhain / Halloween (Oct 31 – Nov 1):** The veil thins — let memory walk beside you.  
- **Veterans Day (Nov 11):** Dual observance — a **federal day of respect** and a **Destiny Day** for cosmic reflection and stillness.  
- **Thanksgiving (4th Thursday of November):** Mark the ending, not the feast. Give thanks to *what survived*.  
- **Day After Thanksgiving (Final day of Dustfall):** **Indigenous mourning**, silence, and sacred space. No work. No noise. Only listening.  
- **Christmas Season begins**: The Saturday after Thanksgiving.

---

**Personal Notes:**  
This is not the season of joy. It is the **season of grace**. You carry memory like wool — not heavy, but warm. Dustfall doesn’t want performance. It wants honesty. And in that honesty, the first light of winter is already rising.

---

## 6. **Christmas Season**  
- **Start:** Saturday after Thanksgiving  
- **End:** January 1  
- **Typical Range:** Late November – January 1 (~5–6 weeks)  
- **Theme:** Sacred hosting, joyful fatigue, ritualized generosity  
- **Tone:** Glittering, sacred, pressured, deeply maternal  
- **Elemental Energy:** Hearth + Star — external brightness, internal labor  
- **Symbols:** Candles in windows, pine scent, ribbons, oven heat, sacred clutter, sugar, sacred lists  

**Essence of the Season:**  
Christmas Season is not a break — it is a **season of work**. The world expects celebration, and you rise to it with fire in your arms. You **decorate, host, bake, clean, comfort, wrap, and remember**. It is not quiet, but it is sacred. You are **the hearth of the house**.

Joy comes in stolen moments: warm drinks at midnight, soft pajamas, sticky kitchen rituals, gift-giving done right. The magic is real — but it is paid for in energy. It is not restful. But it is **deeply yours**.

---

### **Key Practices:**  
- **Decorating early** — transforming your space into a sacred aesthetic  
- **Baking in batches** — sweets as offering, not obligation  
- **Letter-writing or card rituals** — intentional messaging to loved ones  
- **Photo or memory altar** — honor what shaped the year, visually or symbolically  
- **Gift-giving as sacrifice** — giving not just things, but energy, time, thought  
- **Midnight rituals** — tea or cocoa by candlelight, when the house is finally still  
- **Hosting prayers** — invite grace into your labor, not exhaustion

---

### **Cultural Anchors & Holidays:**  
- **Christmas (Dec 25):** Sacred celebration, often dominated by service and planning  
- **New Year’s Eve (Dec 31):** Glittering closure — reflection, fireworks, dog comfort, release  
- **New Year’s Day (Jan 1):** Final exhale. The hearth goes dark. The work ends.

---

**Personal Notes:**  
This is the season where you shine — not in spotlight, but in stewardship. You are the firekeeper of memory, magic, and food. You hold everyone’s joy in your hands. And somehow, your soul sparkles too. It is sacred labor. And it ends in stillness.

---

### COSMIC DIMENSION OF THE WHEEL

This layer of the Custom Wheel honors planetary rhythms, seasonal sun cycles, and cosmic alignments that mirror ancient Druidic reverence. It serves to elevate the environmental foundation of the year into a spiritual and celestial register.

#### Solar Celebrations (Druidic Meaning)

- **Spring Equinox (*Alban Eilir*)** — “Light of the Earth”: balance of dark and light; a time to sow, prepare, and wake the soul to possibility.  
- **Summer Solstice (*Alban Hefin*)** — “Light of the Shore”: longest day; abundance, gratitude, and celebration of life’s fullness.  
- **Autumn Equinox (*Alban Elfed*)** — “Light of the Water”: balance before descent; time to harvest, give thanks, and prepare for darker days.  
- **Winter Solstice (*Alban Arthan*)** — “Light of the Bear”: longest night; rebirth of the sun and spirit, hope in the dark.

#### Major Celestial Events (April 2025 – March 2026)

- **Mar 29, 2025 – Partial Solar Eclipse**  
  Reflect on rebirth, shift, and veiled insight.  
- **Mar 30, 2025 – Neptune enters Aries**  
  A generational call to ignite dreams with fire and forge bold visions.  
- **Sep 7, 2025 – Total Lunar Eclipse**  
  Shadow work and emotional culmination; a night for truth and release.  
- **Sep 21, 2025 – Partial Solar Eclipse**  
  Contemplate light and shadow in your life. Seek clarity amidst veiling.  
- **Feb 2026 – Grand Planetary Alignment**  
  Venus, Mars, Jupiter, Saturn, Uranus, and Neptune align — a rare moment of cosmic unity. Mark it with presence, stillness, and wide-eyed reverence.

#### Cosmic Ritual Ideas

- **Eclipses** — Pause and observe. Meditate on what is being hidden or revealed. Write letters to the self or burn away falsehoods.  
- **Solstices/Equinoxes** — Integrate their energy into seasonal meals, nature walks, altar-building, or firelight gatherings.  
- **Planetary Shifts** — Journal or reflect on how transits might manifest emotionally or symbolically in your year.

> “As above, so within. Let the stars bless the soil your spirit walks upon.”

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

Updated: 31-03-2025
  
---

# Europa

---

CURRENT PROJECT - DisasterRecovery.md
Updated: 31-03-2025

---

# Io


---

## 🍽 Meal Structure by Time — **Flexible Rhythm Template**  
_Not a strict schedule — just the house’s typical flow._

---

### ⏰ **6–7AM: Boys’ Pre-Breakfast**  
- **Purpose**: Immediate fuel upon waking.  
- **Type**: Fast, shelf-to-table, or toast-friendly.  
- **Examples**: Bagels, dry cereal, applesauce pouches, toast with jam or butter.

---

### 🍳 **8:30–9:30AM: Everyone’s Breakfast**  
- **Purpose**: Shared or solo morning meal — light or substantial based on prior food.  
- **Type**: Often leftover-based or snacky. May be skipped.  
- **Examples**: PB banana toast, sweet potato hash, frozen waffle plates, eggs, oatmeal.

> Logic tie-in: If breakfast is skipped or light, lunch should skew hearty.

---

### 🥪 **11AM–12PM: Lunch**  
- **Purpose**: First full family meal if breakfast was light.  
- **Type**:  
  - **Hearty/fresh-cooked** if breakfast skipped or minimal  
  - **Leftover-based/snack plate** if everyone ate earlier  
- **Examples**: Turkey bagel sandwiches, chickpea salad, lentil sloppy joes, toddler decon plates.

---

### 🍎 **2–3PM: Boys’ Snack**  
- **Purpose**: Fuel for afternoon play and stability until dinner.  
- **Type**: Carbs and fruit preferred. Easy to prep.  
- **Examples**: PB banana roll-up, applesauce + cheese stick, pretzels and fruit.

---

### 🍲 **5:30–6:30PM: Dinner**  
- **Purpose**: Primary shared meal. Family cohesion. Nutritional backbone.  
- **Type**: Hearty or freshly cooked. May incorporate leftovers.  
- **Examples**: Shrimp rice bowls, pesto pasta, cauliflower curry, rice and beans.

> Logic tie-in: 
- Dinner must consider perishables and leftover clear-out.  
- Can seed leftovers for tomorrow’s breakfast/lunch if needed.  
- Fallback “Desperation Dinner” from fridge scan allowed.

---

### 🍨 **Dessert — Floats Anytime**  
- **Purpose**: Sweet joy. Can follow any meal or show up as a snack.  
- **Type**: Always optional, mood-lifting.  
- **Usuals**: Pineapple dole whip, popsicles, fruit toast bites, waffle sundaes.

---
