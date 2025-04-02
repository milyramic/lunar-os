## 📦 INVENTORY TEMPLATE — V1 (Titan Pre-Shop Structure)

```yaml
InventoryDate: "DD-MM-YYYY"

Pantry:
  - item: "White Rice"
    quantity: "2 lbs"
    open: false
    freshness: "long shelf"
    tags: ["grain", "pantryfriendly"]

  - item: "Canned Tomatoes"
    quantity: "4 cans"
    open: false
    freshness: "stable"
    tags: ["canned", "acid", "mealbase"]

Fridge:
  - item: "Sour Cream"
    quantity: "1 container"
    open: true
    freshness: "opened 3 days ago"
    tags: ["dairy", "perishable", "cold"]

  - item: "Strawberries"
    quantity: "1 pint"
    open: true
    freshness: "use within 2 days"
    tags: ["fruit", "fresh", "fragile"]

Freezer:
  - item: "Frozen Waffles"
    quantity: "3 packs"
    open: true
    freshness: "good"
    tags: ["breakfast", "freezer", "fast"]

  - item: "Shrimp"
    quantity: "1 bag"
    open: false
    freshness: "frozen, unopened"
    tags: ["protein", "seafood", "cold"]
```

---

## 🔧 TITAN LOGIC NOTES

- **`open:`** field tracks spoilage risks. I’ll flag any open items with time-sensitive use notes.
- **`freshness:`** is freeform but encouraged. You can use “new,” “opened 2 days ago,” “wilting,” “end of week.”
- **`tags:`** allow for filtering by storage type, urgency, or meal use.
