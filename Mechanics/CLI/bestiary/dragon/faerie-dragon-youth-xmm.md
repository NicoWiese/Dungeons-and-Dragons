---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1
- monster/environment/forest
- monster/size/tiny
- monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Faerie Dragon Youth"
---
# [Faerie Dragon Youth](Mechanics\CLI\bestiary\dragon/faerie-dragon-youth-xmm.md)
*Source: Monster Manual (2024) p. 117*  

Faerie dragon youths are quick to use their euphoria-inducing breath on rude or uptight folk.

## Faerie Dragons

*Whimsical Draconic Tricksters*

- **Habitat.** Forest  
- **Treasure.** [Implements](/Mechanics/CLI/tables/random-magic-items-implements.md)  

Faerie dragons are cat-size pranksters with draconic features, butterfly-like wings, and scales of warm hues as youths and cool hues as adults.

```statblock
"name": "Faerie Dragon Youth (XMM)"
"size": "Tiny"
"type": "dragon"
"alignment": "Chaotic Good"
"ac": !!int "13"
"hp": !!int "21"
"hit_dice": "6d4 + 6"
"modifier": !!int "3"
"stats":
  - !!int "3"
  - !!int "16"
  - !!int "12"
  - !!int "12"
  - !!int "12"
  - !!int "14"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Arcana](/Mechanics/CLI/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": "Draconic, Sylvan; telepathy 60 ft. (faerie dragons only)"
"cr": "1"
"traits":
  - "desc": "The dragon has [Advantage](/Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage\
      \ plus 2 (1d4) Psychic damage."
    "name": "Bite"
  - "desc": "*Wisdom Saving Throw:* DC 12, each creature in a 15-foot [Cone](/Mechanics/CLI/variant-rules/cone-area-of-effect-xphb.md).\
      \ *Failure:* The target has the [Incapacitated](/Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition until the end of its next turn and uses all its movement on its\
      \ turn to move in a random direction."
    "name": "Euphoria Breath (Recharge 5-6)"
  - "desc": "The dragon casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 12):\n\n**At\
      \ will:** [Dancing Lights](/Mechanics/CLI/spells/dancing-lights-xphb.md), [Mage\
      \ Hand](/Mechanics/CLI/spells/mage-hand-xphb.md), [Minor Illusion](/Mechanics/CLI/spells/minor-illusion-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The dragon casts [Greater Invisibility](/Mechanics/CLI/spells/greater-invisibility-xphb.md)\
      \ on itself, requiring no spell components and using the same spellcasting ability\
      \ as Spellcasting.\n"
    "name": "Superior Invisibility"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/dragon/token/faerie-dragon-youth-xmm.webp"
```
^statblock

## Environment

forest