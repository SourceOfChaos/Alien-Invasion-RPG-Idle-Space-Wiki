---
layout: default
title: Evolution Shop
parent: Upgrade-Facilities
nav_order: 2
---

## Evolution Shop

The **Evolution Shop** provides permanent upgrades purchased with Essences.
Each purchase grants **random upgrades** from the available pool.

The required Essences are obtained from their corresponding mines:
- <a href="{% link resources/green_essence.md %}">Green Essence Mine</a>
- <a href="{% link resources/red_essence.md %}">Red Essence Mine</a>
- <a href="{% link resources/purple_essence.md %}">Purple Essence Mine</a>

---

## General Mechanics

### Random Upgrade System
- Each purchase grants **1 random upgrade**
- Bulk purchase grants **5 random upgrades**
- No discounts for bulk purchases (only faster progression)

### Price Caps (per upgrade)

| Essence | Cost per Upgrade (Capped) |
|------|------------------|
| Green | 80,000 |
| Red | 24,000 |
| Purple | 5,000 |

---

## Level Scaling Rules

For most upgrades:
- Level 0 = 0
- Each level increases the value by a **fixed step**
- Level 1–99 scale linearly
- Level 100 is calculated normally **and then multiplied by ×2**
- Formula: value = level × step
if level == 100 → value × 2
This makes the final level a **true power spike**.

### Exceptions
- **Double Resources**
- **Double EXP**

These upgrades:
- Scale normally up to Level 99
- Reach a **hard cap** at Level 100
- Do **not** receive an additional ×2 multiplier beyond their maximum

### Rounding Behavior
- Percentage values are **rounded down**
- Example:
- 99 × 0.75 % = 74.25 %
- Displayed as **74.2 %**

---

# Green Essence Upgrades

## Catching Speed
Extra catching speed.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 1,000 |
| 50 | 50,000 |
| 99 | 99,000 |
| 100 | 200,000 |

---

## Cargo
Extra cargo capacity.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 100 |
| 50 | 5,000 |
| 99 | 9,900 |
| 100 | 20,000 |

---

## Hit Points
Increase health.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 8 |
| 50 | 400 |
| 99 | 792 |
| 100 | 1,600 |

---

## Regeneration
Hit points regenerated per second.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 0.16 |
| 50 | 8 |
| 99 | 15.84 |
| 100 | 32 |

---

# Red Essence Upgrades

## Catching Speed
Extra catching speed.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 3,000 |
| 50 | 150,000 |
| 99 | 297,000 |
| 100 | 600,000 |

---

## Cargo
Extra cargo capacity.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 140 |
| 50 | 7,000 |
| 99 | 13,860 |
| 100 | 28,000 |

---

## Hit Points
Increase health.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 12 |
| 50 | 600 |
| 99 | 1,188 |
| 100 | 2,400 |

---

## Regeneration
Hit points regenerated per second.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 0.24 |
| 50 | 12 |
| 99 | 23.76 |
| 100 | 48 |

---

## Extra Mining
Extra green/red/purple Essence mining speed.

| Level | Value |
|------|------:|
| 0 | 0% |
| 1 | 0.5% |
| 50 | 25% |
| 99 | 49.5% |
| 100 | 100% |

All follow identical scaling.

---

# Purple Essence Upgrades

## Catching Speed
Extra catching speed.

| Level | Value |
|------|------:|
| 0 | 0 |
| 1 | 8,000 |
| 50 | 400,000 |
| 99 | 792,000 |
| 100 | 1,600,000 |

---

## Extra Mining
Extra green/red/purple Essence mining speed.

| Level | Value |
|------|------:|
| 0 | 0% |
| 1 | 0.75% |
| 50 | 37.5% |
| 99 | 74.2% |
| 100 | 150% |

---

## Heat Resistance
Extra heat resistance.

| Level | Value |
|------|------:|
| 0 | 0% |
| 1 | 2% |
| 50 | 100% |
| 99 | 198% |
| 100 | 400% |

---

## Double Resources (Special Rule)
Chance to receive double resources from humans.

| Level | Value |
|------|------:|
| 0 | 0% |
| 1 | 0.6% |
| 50 | 30% |
| 99 | 59.4% |
| 100 | 100% |

---

## Double EXP (Special Rule)
Chance to receive double EXP from humans.

| Level | Value |
|------|------:|
| 0 | 0% |
| 1 | 0.6% |
| 50 | 30% |
| 99 | 59.4% |
| 100 | 100% |

---

**Data status**
- Game version: 4.32
- Last verified: 2026-01-09
