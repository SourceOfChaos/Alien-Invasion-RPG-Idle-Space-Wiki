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
- [Green Essence Mine](resources/green_essence.md)
- [Red Essence Mine](resources/red_essence.md)
- [Purple Essence Mine](resources/purple_essence.md)

---

## General Mechanics

### Random Upgrade System
- Each purchase grants **1 random upgrade**
- Bulk purchase grants **5 random upgrades**
- No discounts for bulk purchases (only faster progression)

### Price Caps (per upgrade)
| Essence | Cost per Upgrade |
|------|------------------|
| Green | 80,000 |
| Red | 24,000 |
| Purple | 5,000 |

---

## Level Scaling Rules

For most upgrades:
- Level 0 = 0
- Level 100 = Final value
- Level 99 = **~50% of final value**
- Level 100 **doubles** the value compared to level 99

### Exceptions
- **Double Resources**
- **Double EXP**

These upgrades are **capped at 100%**.
- Level 99 ≈ 59.4%
- Level 100 = 100%
- No doubling at max level

### Rounding Behavior
- Purple Essence mining upgrades increase by **0.75 per level**
- Displayed values are **rounded down**
- Example: last value before max shows **74.2**, not 74.25

---

# Green Essence Upgrades

## Catching Speed
Extra catching speed.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | - |
| 100/100 | 200K | MAXED |

---

## Cargo
Extra cargo capacity.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 10.0K | MAXED |

---

## Hit Points
Increase health.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 800 | MAXED |

---

## Regeneration
Hit points regenerated per second.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 16 | MAXED |

---

# Red Essence Upgrades

## Catching Speed
Extra catching speed.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 600K | MAXED |

---

## Cargo
Extra cargo capacity.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 14.0K | MAXED |

---

## Hit Points
Increase health.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 1.20K | MAXED |

---

## Regeneration
Hit points regenerated per second.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 24 | MAXED |

---

## Extra Mining
Extra Essence mining speed.

| Upgrade | Max Value |
|-------|-----------|
| Green Essence | +100% |
| Red Essence | +100% |
| Purple Essence | +100% |

All follow identical scaling.

---

# Purple Essence Upgrades

## Catching Speed
Extra catching speed.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 1.60M | MAXED |

---

## Extra Mining
Extra Essence mining speed.

| Essence | Max Value |
|-------|-----------|
| Green | +150% |
| Red | +150% |
| Purple | +150% |

---

## Heat Resistance
Extra heat resistance.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0 | – |
| 100/100 | 400% | MAXED |

---

## Double Resources (Special Rule)
Chance to receive double resources from humans.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0% | – |
| 100/100 | 100% | MAXED |

- Level 99 ≈ 59.4%
- Value is **capped**, no doubling at max level

---

## Double EXP (Special Rule)
Chance to receive double EXP from humans.

| Level | Value | Cost |
|------|------|------|
| 0/100 | 0% | – |
| 100/100 | 100% | MAXED |

- Same capped behavior as Double Resources

---

**Data status**
- Game version: 4.32
- Last verified: 2026-01-09
