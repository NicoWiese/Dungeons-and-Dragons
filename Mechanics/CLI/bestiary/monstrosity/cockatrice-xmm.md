---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1-2
- monster/environment/grassland
- monster/size/small
- monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cockatrice"
---
# [Cockatrice](Mechanics\CLI\bestiary\monstrosity/cockatrice-xmm.md)
*Source: Monster Manual (2024) p. 75. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Cockatrices often try to claim eye-catching structures—such as ruins and secluded farms—as roosts.

## Cockatrices

*Accursed Avians with the Power to Petrify*

- **Habitat.** Grassland  
- **Treasure.** None  

Cockatrices combine the features of irate roosters and starving reptiles. They petrify those they bite, their slightest peck turning their prey to stone.

```statblock
"name": "Cockatrice (XMM)"
"size": "Small"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"modifier": !!int "1"
"stats":
  - !!int "6"
  - !!int "12"
  - !!int "12"
  - !!int "2"
  - !!int "13"
  - !!int "5"
"speed": "20 ft., fly 40 ft."
"condition_immunities": "[petrified](/Mechanics/CLI/conditions.md#Petrified)"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": ""
"cr": "1/2"
"actions":
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 3 (1d4 + 1) Piercing damage.\
      \ If the target is a creature, it is subjected to the following effect. *Constitution\
      \ Saving Throw:* DC 11. *1St Failure:* The target has the [Restrained](/Mechanics/CLI/conditions.md#Restrained)\
      \ condition. The target repeats the save at the end of its next turn if it is\
      \ still [Restrained](/Mechanics/CLI/conditions.md#Restrained), ending the effect\
      \ on itself on a success. *2Nd Failure:* The target has the [Petrified](/Mechanics/CLI/conditions.md#Petrified)\
      \ condition, instead of the [Restrained](/Mechanics/CLI/conditions.md#Restrained)\
      \ condition, for 24 hours."
    "name": "Petrifying Bite"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/monstrosity/token/cockatrice-xmm.webp"
```
^statblock

## Environment

grassland