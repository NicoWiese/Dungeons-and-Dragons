---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/0
- monster/environment/arctic
- monster/environment/forest
- monster/environment/hill
- monster/size/tiny
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Owl"
---
# [Owl](Mechanics\CLI\bestiary\beast/owl-xmm.md)
*Source: Monster Manual (2024) p. 366, Player's Handbook (2024) p. 354. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](/Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](/Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Owl (XMM)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"modifier": !!int "1"
"stats":
  - !!int "3"
  - !!int "13"
  - !!int "8"
  - !!int "2"
  - !!int "12"
  - !!int "7"
"speed": "5 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 15"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The owl doesn't provoke [Opportunity Attacks](/Mechanics/CLI/actions.md#Opportunity%20Attack)\
      \ when it flies out of an enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 1 Slashing damage."
    "name": "Talons"
"source":
  - "XMM"
  - "XPHB"
"image": "/Mechanics/CLI/bestiary/beast/token/owl-xmm.webp"
```
^statblock

## Environment

arctic, forest, hill