---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xphb
- monster/cr/
- monster/size/medium
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Construct Spirit (Metal)"
---
# [Construct Spirit (Metal)](Mechanics\CLI\bestiary\construct/construct-spirit-metal-xphb.md)
*Source: Player's Handbook (2024) p. 324*  

```statblock
"name": "Construct Spirit (Metal) (XPHB)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac_class": "13 + the spell's level"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "5"
"speed": "30 ft."
"damage_resistances": "poison"
"condition_immunities": "[charmed](/Mechanics/CLI/conditions.md#Charmed), [exhaustion](/Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/Mechanics/CLI/conditions.md#Frightened), [paralyzed](/Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Understands the languages you know"
"traits":
  - "desc": "A creature that hits the spirit with a melee attack or that starts its\
      \ turn in a grapple with the spirit takes 1d10 Fire damage."
    "name": "Heated Body"
"actions":
  - "desc": "The spirit makes a number of Slam attacks equal to half this spell's\
      \ level (round down)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft. *Hit:* 1d8 + 4 + the spell's level Bludgeoning damage."
    "name": "Slam"
"source":
  - "XPHB"
```
^statblock