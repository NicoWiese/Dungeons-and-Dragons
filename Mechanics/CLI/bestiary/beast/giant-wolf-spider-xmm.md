---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1-4
- monster/environment/coastal
- monster/environment/desert
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/medium
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Wolf Spider"
---
# [Giant Wolf Spider](Mechanics\CLI\bestiary\beast/giant-wolf-spider-xmm.md)
*Source: Monster Manual (2024) p. 362. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](/Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](/Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Wolf Spider (XMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "3"
  - !!int "12"
  - !!int "4"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"senses": "[Blindsight](/Mechanics/CLI/senses.md#Blindsight) 10 ft., [Darkvision](/Mechanics/CLI/senses.md#Darkvision)\
  \ 60 ft., passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The spider can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage\
      \ plus 5 (2d4) Poison damage."
    "name": "Bite"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/beast/token/giant-wolf-spider-xmm.webp"
```
^statblock

## Environment

coastal, desert, forest, grassland, hill