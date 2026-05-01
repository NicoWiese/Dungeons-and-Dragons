---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1
- monster/environment/desert
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Hyena"
---
# [Giant Hyena](Mechanics\CLI\bestiary\beast/giant-hyena-xmm.md)
*Source: Monster Manual (2024) p. 357. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](/Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](/Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Hyena (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "2"
  - !!int "12"
  - !!int "7"
"speed": "50 ft."
"skillsaves":
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": ""
"cr": "1"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Piercing damage."
    "name": "Bite"
"bonus_actions":
  - "desc": "Immediately after dealing damage to a creature that was already [Bloodied](/Mechanics/CLI/conditions.md#Bloodied),\
      \ the hyena can move up to half its [Speed](/Mechanics/CLI/variant-rules/speed-xphb.md),\
      \ and it makes one Bite attack."
    "name": "Rampage (1/Day)"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/beast/token/giant-hyena-xmm.webp"
```
^statblock

## Environment

desert, forest, grassland, hill