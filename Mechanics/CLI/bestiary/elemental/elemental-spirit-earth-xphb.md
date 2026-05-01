---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xphb
- monster/cr/
- monster/size/medium
- monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Elemental Spirit (Earth)"
---
# [Elemental Spirit (Earth)](Mechanics\CLI\bestiary\elemental/elemental-spirit-earth-xphb.md)
*Source: Player's Handbook (2024) p. 325*  

```statblock
"name": "Elemental Spirit (Earth) (XPHB)"
"size": "Medium"
"type": "elemental"
"alignment": "Neutral"
"ac_class": "11 + the spell's level"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "17"
  - !!int "4"
  - !!int "10"
  - !!int "16"
"speed": "40 ft., burrow 40 ft."
"damage_resistances": "piercing, slashing"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/Mechanics/CLI/conditions.md#Exhaustion), [paralyzed](/Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/Mechanics/CLI/conditions.md#Petrified), [poisoned](/Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Primordial, understands the languages you know"
"actions":
  - "desc": "The spirit makes a number of Slam attacks equal to half this spell's\
      \ level (round down)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft.. *Hit:* 1d10 + 4 + the spell's level Bludgeoning damage."
    "name": "Slam"
"source":
  - "XPHB"
```
^statblock