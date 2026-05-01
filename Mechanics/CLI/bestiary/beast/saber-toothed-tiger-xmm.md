---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/2
- monster/environment/arctic
- monster/environment/hill
- monster/environment/mountain
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Saber-Toothed Tiger"
---
# [Saber-Toothed Tiger](Mechanics\CLI\bestiary\beast/saber-toothed-tiger-xmm.md)
*Source: Monster Manual (2024) p. 369. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](/Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](/Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Saber-Toothed Tiger (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "17"
  - !!int "15"
  - !!int "3"
  - !!int "12"
  - !!int "8"
"speed": "40 ft."
"saves":
  - "strength": !!int "6"
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": ""
"cr": "2"
"traits":
  - "desc": "With a 10-foot running start, the tiger can [Long Jump](/Mechanics/CLI/variant-rules/long-jump-xphb.md)\
      \ up to 25 feet."
    "name": "Running Leap"
"actions":
  - "desc": "The tiger makes two Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 11 (2d6 + 4) Slashing damage."
    "name": "Rend"
"bonus_actions":
  - "desc": "The tiger takes the [Disengage](/Mechanics/CLI/actions.md#Disengage)\
      \ or [Hide](/Mechanics/CLI/actions.md#Hide) action."
    "name": "Nimble Escape"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/beast/token/saber-toothed-tiger-xmm.webp"
```
^statblock

## Environment

arctic, hill, mountain