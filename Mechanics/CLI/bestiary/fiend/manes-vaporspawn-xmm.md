---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1
- monster/environment/abyss
- monster/environment/planar
- monster/size/medium
- monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Manes Vaporspawn"
---
# [Manes Vaporspawn](Mechanics\CLI\bestiary\fiend/manes-vaporspawn-xmm.md)
*Source: Monster Manual (2024) p. 201*  

Vaporspawn arise from evil souls shattered by unspeakable torments or the depredations of more powerful demons. These distorted manes undergo endless, painful contortions, and they share their torment with whatever creatures they encounter.

## Manes

*Demons of Panic and Frenzy*

- **Habitat.** Planar (Abyss)  
- **Treasure.** None  

The lowest form of demons, manes appear when truly loathsome souls are condemned to the Abyss. These misshapen demons have distorted features and bodies that crawl with Abyssal parasites. Overwhelmed by demonic urges and constant terror, manes know only shock and frenzied outbursts.

```statblock
"name": "Manes Vaporspawn (XMM)"
"size": "Medium"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "15"
  - !!int "5"
  - !!int "8"
  - !!int "3"
"speed": "30 ft."
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/Mechanics/CLI/conditions.md#Charmed), [exhaustion](/Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/Mechanics/CLI/conditions.md#Frightened), [grappled](/Mechanics/CLI/conditions.md#Grappled),\
  \ [poisoned](/Mechanics/CLI/conditions.md#Poisoned), [restrained](/Mechanics/CLI/conditions.md#Restrained)"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 9"
"languages": "understands Abyssal but can't speak"
"cr": "1"
"traits":
  - "desc": "The manes can move through a space as narrow as 1 inch without expending\
      \ extra movement to do so."
    "name": "Contortionist"
  - "desc": "*Constitution Saving Throw:* DC 12, each creature in a 5-foot [Emanation](/Mechanics/CLI/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the manes at the end of the manes's turn. *Failure:* The\
      \ target has the [Incapacitated](/Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition until the end of its next turn. *Success:* The target is immune\
      \ to this manes's Sickening Vapors for 24 hours."
    "name": "Sickening Vapors"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Slashing damage\
      \ plus 5 (2d4) Necrotic damage."
    "name": "Claw"
"bonus_actions":
  - "desc": "While in [Dim Light](/Mechanics/CLI/variant-rules/dim-light-xphb.md)\
      \ or [Darkness](/Mechanics/CLI/variant-rules/darkness-xphb.md), the manes takes\
      \ the [Hide](/Mechanics/CLI/actions.md#Hide) action."
    "name": "Shadow Stealth"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/fiend/token/manes-vaporspawn-xmm.webp"
```
^statblock

## Environment

planar, abyss