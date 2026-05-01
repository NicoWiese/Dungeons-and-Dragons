---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/5
- monster/environment/feywild
- monster/environment/forest
- monster/environment/planar
- monster/size/tiny
- monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pixie Wonderbringer"
---
# [Pixie Wonderbringer](Mechanics\CLI\bestiary\fey/pixie-wonderbringer-xmm.md)
*Source: Monster Manual (2024) p. 244*  

Energetic entertainers, wonderbringers use their magic in defense of the wilderness when they must.

## Pixies

*Friends of the Forest*

- **Habitat.** Forest, Planar (Feywild)  
- **Treasure.** [Arcana](/Mechanics/CLI/tables/random-magic-items-arcana.md)  

Barely a foot tall, pixies resemble diminutive elves with gossamer wings. They invisibly observe those who enter their wooded homes, revealing themselves to those with friendly intentions. Those who are unfriendly become the targets of pixies' pranks.

```statblock
"name": "Pixie Wonderbringer (XMM)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "15"
"hp": !!int "60"
"hit_dice": "24d4"
"modifier": !!int "5"
"stats":
  - !!int "2"
  - !!int "20"
  - !!int "10"
  - !!int "11"
  - !!int "14"
  - !!int "18"
"speed": "10 ft., fly 30 ft."
"skillsaves":
  - "name": "[Arcana](/Mechanics/CLI/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"senses": "passive Perception 15"
"languages": "Common, Elvish, Sylvan"
"cr": "5"
"traits":
  - "desc": "The pixie has [Advantage](/Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The pixie makes two Faerie Dust attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +7, reach 5 ft. or range 60 ft. *Hit:*\
      \ 15 (2d10 + 4) Radiant damage, and the target has the [Charmed](/Mechanics/CLI/conditions.md#Charmed)\
      \ or [Poisoned](/Mechanics/CLI/conditions.md#Poisoned) condition (pixie's choice)\
      \ until the start of the pixie's next turn."
    "name": "Faerie Dust"
  - "desc": "The pixie casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 15):\n\n**At\
      \ will:** [Dancing Lights](/Mechanics/CLI/spells/dancing-lights-xphb.md), [Druidcraft](/Mechanics/CLI/spells/druidcraft-xphb.md),\
      \ [Invisibility](/Mechanics/CLI/spells/invisibility-xphb.md) (self only)\n\n\
      **1/day each:** [Detect Thoughts](/Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [Fly](/Mechanics/CLI/spells/fly-xphb.md), [Major Image](/Mechanics/CLI/spells/major-image-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The pixie casts [Entangle](/Mechanics/CLI/spells/entangle-xphb.md), [Polymorph](/Mechanics/CLI/spells/polymorph-xphb.md),\
      \ or [Tasha's Hideous Laughter](/Mechanics/CLI/spells/tashas-hideous-laughter-xphb.md),\
      \ requiring no Material components and using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Burst of Wonder (Recharge 5-6)"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/fey/token/pixie-wonderbringer-xmm.webp"
```
^statblock

## Environment

forest, planar, feywild