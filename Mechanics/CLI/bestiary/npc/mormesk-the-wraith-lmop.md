---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/lmop
- monster/cr/3
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mormesk the Wraith"
---
# [Mormesk the Wraith](Mechanics\CLI\bestiary\npc/mormesk-the-wraith-lmop.md)
*Source: Lost Mine of Phandelver p. 59*  

A wraith is the incorporeal remnant of a particularly hateful being. Most wraiths can transform those they have slain into spectral undead servitors. Mormesk chooses not to, preferring to let the dead stay dead.

```statblock
"name": "Mormesk the Wraith (LMoP)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "16"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "15"
"speed": "0 ft., fly 60 ft."
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks that aren't silvered"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/Mechanics/CLI/conditions.md#Charmed), [grappled](/Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/Mechanics/CLI/conditions.md#Paralyzed), [petrified](/Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/Mechanics/CLI/conditions.md#Poisoned), [prone](/Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common, Infernal"
"cr": "3"
"traits":
  - "desc": "The wraith can move through an object or another creature, but can't\
      \ stop there."
    "name": "Incorporeal Movement"
  - "desc": "While in sunlight, the wraith has disadvantage on attack rolls and on\
      \ Wisdom ([Perception](/Mechanics/CLI/skills.md#Perception)) checks that rely\
      \ on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:* 16\
      \ (3d8 + 3) necrotic damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. If this attack reduces the target's hit point maximum to 0,\
      \ the target dies. This reduction to the target's hit point maximum lasts until\
      \ the target finishes a long rest."
    "name": "Life Drain"
"source":
  - "LMoP"
"image": "/Mechanics/CLI/bestiary/npc/token/mormesk-the-wraith-lmop.webp"
```
^statblock