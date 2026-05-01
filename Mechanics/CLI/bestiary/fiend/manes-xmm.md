---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1-8
- monster/environment/abyss
- monster/environment/planar
- monster/size/small
- monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Manes"
---
# [Manes](Mechanics\CLI\bestiary\fiend/manes-xmm.md)
*Source: Monster Manual (2024) p. 201*  

Manes lash out at creatures that appear weaker than themselves—or that react to them with fear—and strive to avoid more powerful demons. When manes escape from the Abyss, they go on reckless rampages and inflict as much harm as possible.

## Manes

*Demons of Panic and Frenzy*

- **Habitat.** Planar (Abyss)  
- **Treasure.** None  

The lowest form of demons, manes appear when truly loathsome souls are condemned to the Abyss. These misshapen demons have distorted features and bodies that crawl with Abyssal parasites. Overwhelmed by demonic urges and constant terror, manes know only shock and frenzied outbursts.

```statblock
"name": "Manes (XMM)"
"size": "Small"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "9"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"modifier": !!int "-1"
"stats":
  - !!int "10"
  - !!int "9"
  - !!int "13"
  - !!int "3"
  - !!int "8"
  - !!int "4"
"speed": "20 ft."
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/Mechanics/CLI/conditions.md#Charmed), [frightened](/Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 9"
"languages": "understands Abyssal but can't speak"
"cr": "1/8"
"actions":
  - "desc": "*Melee Attack Roll:* +2, reach 5 ft. *Hit:* 5 (2d4) Slashing damage."
    "name": "Claw"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/fiend/token/manes-xmm.webp"
```
^statblock

## Environment

planar, abyss