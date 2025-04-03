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

# 📦 INVENTORY
---

```yaml
InventoryDate: "03-04-2025"

Pantry:
  - item: "Premium Coconut Cream"
    quantity: "1 can"
    open: false
    freshness: "new"
    tags: ['canned', 'pantryfriendly', 'mealprep']

  - item: "Organic Sauerkraut"
    quantity: "1 jar"
    open: false
    freshness: "new"
    tags: ['fermented', 'pantryfriendly']

  - item: "Spidey Pasta Cheddar"
    quantity: "2 boxes"
    open: false
    freshness: "new"
    tags: ['kids', 'pantryfriendly']

Fridge:
  - item: "Bananas"
    quantity: "3.48 lbs"
    open: true
    freshness: "new"
    tags: ['fruit', 'fresh', 'toddler']

  - item: "Jumbo Avocados"
    quantity: "3"
    open: false
    freshness: "ripe"
    tags: ['produce', 'fresh']

  - item: "Carrots"
    quantity: "0.71 lbs"
    open: true
    freshness: "new"
    tags: ['vegetable', 'fresh']

  - item: "Baby Arugula"
    quantity: "1 container"
    open: false
    freshness: "new"
    tags: ['greens', 'fresh']

  - item: "Bell Peppers (Orange, Red, Yellow)"
    quantity: "3"
    open: false
    freshness: "new"
    tags: ['produce', 'fresh']

  - item: "Sour Cream Crunch Loops"
    quantity: "3 boxes"
    open: false
    freshness: "new"
    tags: ['snack', 'toddler']

  - item: "Orange Juice"
    quantity: "1 bottle"
    open: false
    freshness: "new"
    tags: ['drink', 'cold', 'breakfast']

  - item: "Avocado Veggie Blend"
    quantity: "10 pouches"
    open: false
    freshness: "new"
    tags: ['toddler', 'cold']

  - item: "Kale Apple Veggie Blend"
    quantity: "4 pouches"
    open: false
    freshness: "new"
    tags: ['toddler', 'cold']

  - item: "Apple Cherry Blend"
    quantity: "5 pouches"
    open: false
    freshness: "new"
    tags: ['toddler', 'cold']

  - item: "Raspberry Smart Blend"
    quantity: "3 pouches"
    open: false
    freshness: "new"
    tags: ['toddler', 'cold']

  - item: "Cracker Cuts Cheese"
    quantity: "1 pack"
    open: false
    freshness: "new"
    tags: ['cheese', 'deli']

  - item: "Turkey Breakfast Sausage"
    quantity: "1 pack"
    open: false
    freshness: "new"
    tags: ['protein', 'breakfast', 'cold']

  - item: "Oak Smoked Salmon"
    quantity: "1 pack"
    open: false
    freshness: "new"
    tags: ['protein', 'cold', 'bagels']

Freezer:
  - item: "Organic Green Apple Pops"
    quantity: "1 box"
    open: false
    freshness: "new"
    tags: ['dessert', 'treat', 'freezer']

```
