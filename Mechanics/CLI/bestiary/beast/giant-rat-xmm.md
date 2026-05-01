---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1-8
- monster/environment/forest
- monster/environment/swamp
- monster/environment/underdark
- monster/environment/urban
- monster/size/small
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Rat"
---
# [Giant Rat](Mechanics\CLI\bestiary\beast/giant-rat-xmm.md)
*Source: Monster Manual (2024) p. 358. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](/Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](/Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Rat (XMM)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "7"
"hit_dice": "2d6"
"modifier": !!int "3"
"stats":
  - !!int "7"
  - !!int "16"
  - !!int "11"
  - !!int "2"
  - !!int "10"
  - !!int "4"
"speed": "30 ft., climb 30 ft."
"saves":
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "The rat has [Advantage](/Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ on an attack roll against a creature if at least one of the rat's allies is\
      \ within 5 feet of the creature and the ally doesn't have the [Incapacitated](/Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 feet. *Hit:* 5 (1d4 + 3) Piercing damage."
    "name": "Bite"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/beast/token/giant-rat-xmm.webp"
```
^statblock

## Environment

forest, swamp, underdark, urban