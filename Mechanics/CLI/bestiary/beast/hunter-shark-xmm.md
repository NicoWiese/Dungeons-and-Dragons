---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/2
- monster/environment/underwater
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hunter Shark"
---
# [Hunter Shark](Mechanics\CLI\bestiary\beast/hunter-shark-xmm.md)
*Source: Monster Manual (2024) p. 363. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](/Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](/Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Hunter Shark (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "1"
  - !!int "10"
  - !!int "4"
"speed": "5 ft., swim 40 ft."
"skillsaves":
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"senses": "[Blindsight](/Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 12"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The shark can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Attack Roll:* +6 (with [Advantage](/Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ if the target doesn't have all its [Hit Points](/Mechanics/CLI/variant-rules/hit-points-xphb.md)),\
      \ reach 5 ft. *Hit:* 14 (3d6 + 4) Piercing damage."
    "name": "Bite"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/beast/token/hunter-shark-xmm.webp"
```
^statblock

## Environment

underwater