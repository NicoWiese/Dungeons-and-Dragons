---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/12
- monster/environment/any
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Questing Knight"
---
# [Questing Knight](Mechanics\CLI\bestiary\humanoid/questing-knight-xmm.md)
*Source: Monster Manual (2024) p. 184*  

Questing knights travel in pursuit of a cause, such as slaying a villain, defeating a monster, recovering an Artifact, or restoring their lost honor.

## Knights

*Battle Masters and Heroic Wanderers*

- **Habitat.** Any  
- **Treasure.** [Armaments](/Mechanics/CLI/tables/random-magic-items-armaments.md), Individual  

Knights are skilled warriors trained for war and tested in battle. Many serve the rulers of a realm, a religion, or an order devoted to a cause.

```statblock
"name": "Questing Knight (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "202"
"hit_dice": "27d8 + 81"
"modifier": !!int "7"
"stats":
  - !!int "20"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "12"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "7"
  - "wisdom": !!int "5"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Athletics](/Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Persuasion](/Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+8"
"condition_immunities": "[charmed](/Mechanics/CLI/conditions.md#Charmed), [frightened](/Mechanics/CLI/conditions.md#Frightened)"
"gear":
  - "[greatsword](/Mechanics/CLI/items/greatsword-xphb.md)"
  - "[longbow](/Mechanics/CLI/items/longbow-xphb.md)"
  - "[plate armor](/Mechanics/CLI/items/plate-armor-xphb.md)"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "12"
"traits":
  - "desc": "Creatures of the knight's choice in a 30-foot [Emanation](/Mechanics/CLI/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from it have [Immunity](/Mechanics/CLI/variant-rules/immunity-xphb.md)\
      \ to the [Charmed](/Mechanics/CLI/conditions.md#Charmed) and [Frightened](/Mechanics/CLI/conditions.md#Frightened)\
      \ conditions while there."
    "name": "Aura of Bravery"
"actions":
  - "desc": "The knight makes three attacks, using Greatsword or Longbow in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage\
      \ plus 22 (5d8) Radiant damage."
    "name": "Greatsword"
  - "desc": "*Ranged Attack Roll:* +7, range 150/600 ft. *Hit:* 12 (2d8 + 3) Piercing\
      \ damage plus 22 (5d8) Radiant damage."
    "name": "Longbow"
  - "desc": "The knight casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 16):\n\n**1/day each:** [Daylight](/Mechanics/CLI/spells/daylight-xphb.md),\
      \ [Dispel Evil and Good](/Mechanics/CLI/spells/dispel-evil-and-good-xphb.md),\
      \ [Greater Restoration](/Mechanics/CLI/spells/greater-restoration-xphb.md),\
      \ [Phantom Steed](/Mechanics/CLI/spells/phantom-steed-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/humanoid/token/questing-knight-xmm.webp"
```
^statblock

## Environment

any