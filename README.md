# ✦ Clean Slate

> **A Quality of Life mod for Stellaris that adds tools for resetting, reorganising, and automating your empire's planets and infrastructure.**

![Stellaris](https://img.shields.io/badge/Stellaris-v4.3.*-blue)
![Version](https://img.shields.io/badge/Version-1.0.2-green)

---

## Overview
Clean Slate gives you a set of practical tools to cut through the tedium of empire management. Whether you want to wipe a planet clean and start fresh, rapidly relocate a population, or accelerate construction at a cost — this mod has you covered. All features are player-only and designed to complement any playstyle without touching AI behaviour.

---

## Features

### Decisions

---

#### 🧹 Clear World
Removes all buildings and districts from a planet, resetting it to a blank colony ready for redevelopment. The appropriate capital building is automatically restored based on your empire type.

- **Cost:** 500 Unity
- **Enactment Time:** 30 days
- Works for regular empires, hive minds (including wilderness), machine empires, and habitats

---

#### 👥 Relocate Population
Resettles all pop groups on a planet to other planets within the same sector. If the planet is the only one in its sector, pops are sent to a random planet elsewhere in your empire.
If planet is not in a sector, randomly sends to all other planets in empire.
Basically a faster way of abandoning a colony. Each pop group is moved as a group, which can be uneven!

- **Cost:** 25 Influence, 500 Unity
- **Enactment Time:** 30 days
- Requires at least one other planet in your empire to resettle to

---

#### 🏗️ Rapid Construction (Toggle)
A per-planet toggle that dramatically increases building speed at the cost of proportionally higher building costs. Automatically upgrades when you research the relevant engineering technology.

| Tier | Required Tech | Speed & Cost Increase |
|---|---|---|
| T1 | None | +250% |
| T2 | Assembly Pattern | +500% |
| T3 | Construction Templates | +750% |
| T4 | Megaengineering | +1000% |

- **Enable Cost:** 50 Unity
- Cannot be activated while buildings are already under construction
- Upgrades automatically on all active planets when a relevant tech is researched

---

### Edicts

---

#### 🧬 Accelerated Genetic Modification
Infuses genetic modification facilities with exotic gases to accelerate genetic changes across your population.

- **Activation Cost/Upkeep:** Exotic Gases (scaled by empire size)
- **Effect:** +50 flat sub-species integration, +200% sub-species integration speed
- Requires: Gene Tailoring technology

---

#### ☠️ Accelerated Purge Protocols
Keeps undesirable populations in a compliant state using exotic gases, dramatically accelerating purge operations empire-wide.

- **Activation Cost/Upkeep:** Exotic Gases (scaled by empire size)
- **Effect:** +200% pop purge speed
- Requires: At least one species being purged

---

### Defines

---

#### 💸 Reduced Colony Abandon Cost
Reduces the influence surcharge for abandoning a colony (resettling the last pop) from **200** down to **25**.

---

## Compatibility

This mod is fully additive — it does not overwrite any vanilla files. All content is new decisions, edicts, policies, and a single defines override for the colony abandon cost.

Any mod that also overrides `RESETTLE_DESTROY_COLONY_COST` in defines will conflict on that value.

---

## Credits
- **Mod Author:** Hamzah Hayat
