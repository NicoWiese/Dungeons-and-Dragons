---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1-4
- monster/environment/forest
- monster/environment/mountain
- monster/environment/underdark
- monster/environment/urban
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Bats"
---
# [Swarm of Bats](Mechanics\CLI\bestiary\beast/swarm-of-bats-xmm.md)
*Source: Monster Manual (2024) p. 370. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](/Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](/Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Swarm of Bats (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d10"
"modifier": !!int "2"
"stats":
  - !!int "5"
  - !!int "15"
  - !!int "10"
  - !!int "2"
  - !!int "12"
  - !!int "4"
"speed": "5 ft., fly 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/Mechanics/CLI/conditions.md#Charmed), [frightened](/Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/Mechanics/CLI/conditions.md#Grappled), [paralyzed](/Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/Mechanics/CLI/conditions.md#Petrified), [prone](/Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/Mechanics/CLI/conditions.md#Restrained), [stunned](/Mechanics/CLI/conditions.md#Stunned)"
"senses": "[Blindsight](/Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 11"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny bat. The swarm\
      \ can't regain [Hit Points](/Mechanics/CLI/variant-rules/hit-points-xphb.md)\
      \ or gain [Temporary Hit Points](/Mechanics/CLI/variant-rules/temporary-hit-points-xphb.md)."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (2d4) Piercing damage,\
      \ or 2 (1d4) Piercing damage if the swarm is [Bloodied](/Mechanics/CLI/conditions.md#Bloodied)."
    "name": "Bites"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/beast/token/swarm-of-bats-xmm.webp"
```
^statblock

## Environment

forest, mountain, underdark, urban