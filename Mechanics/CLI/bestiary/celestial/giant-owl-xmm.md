---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1-4
- monster/environment/arctic
- monster/environment/forest
- monster/environment/hill
- monster/size/large
- monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Owl"
---
# [Giant Owl](Mechanics\CLI\bestiary\celestial/giant-owl-xmm.md)
*Source: Monster Manual (2024) p. 358. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](/Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](/Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Owl (XMM)"
"size": "Large"
"type": "celestial"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "10"
"speed": "5 ft., fly 60 ft."
"saves":
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "necrotic, radiant"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 16"
"languages": "Celestial; understands Common, Elvish, and Sylvan but can't speak them"
"cr": "1/4"
"traits":
  - "desc": "The owl doesn't provoke an Opportunity Attack when it flies out of an\
      \ enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 7 (1d10 + 2) Slashing damage."
    "name": "Talons"
  - "desc": "The owl casts one of the following spells, requiring no spell components\
      \ and using Wisdom as the spellcasting ability:\n\n**At will:** [Detect Evil\
      \ and Good](/Mechanics/CLI/spells/detect-evil-and-good-xphb.md), [Detect Magic](/Mechanics/CLI/spells/detect-magic-xphb.md)\n\
      \n**1/day:** [Clairvoyance](/Mechanics/CLI/spells/clairvoyance-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/celestial/token/giant-owl-xmm.webp"
```
^statblock

## Environment

arctic, forest, hill