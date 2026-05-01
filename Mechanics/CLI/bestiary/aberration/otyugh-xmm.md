---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/5
- monster/environment/underdark
- monster/size/large
- monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Otyugh"
---
# [Otyugh](Mechanics\CLI\bestiary\aberration/otyugh-xmm.md)
*Source: Monster Manual (2024) p. 233. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Otyugh

*Garbage-Heap Gourmand*

- **Habitat.** Underdark  
- **Treasure.** Any  

Otyughs live to eat—the more disgusting the meal, the better. They consider all non-otyughs that come within reach dishes in life's endless buffet. In dumps, sewers, polluted ruins, and similar murky depths, otyughs devour garbage, carcasses, and anything else their tentacles can cram in their expansive maws. Some creatures ply otyughs with trash to recruit them as watchful—if disgusting—guardians.

Otyughs often bury themselves amid trash heaps and observe their surroundings with their eye-studded stalk. They use glittery trash and telepathic urgings to coax creatures close, then burst from hiding, attacking with their spiny tentacles and filthy maws. Roll on or choose a result from the Otyugh Lures table to inspire how an otyugh tempts prey close.

**Otyugh Lures**

| dice: 1d4 | To Attract Potential Meals, the Otyugh... |
|-----------|-------------------------------------------|
| 1 | Disguises its tentacles with garbage puppets. |
| 2 | Sings an enticing song in Otyugh. |
| 3 | Telepathically transmits a message like "Happy good stuff here!" or "Help now! I'm too delicious?" |
| 4 | Telepathically transmits an image of a large gemstone, crooked weapon, or soggy pastry. |
^otyugh-lures

```statblock
"name": "Otyugh (XMM)"
"size": "Large"
"type": "aberration"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "104"
"hit_dice": "11d10 + 44"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "19"
  - !!int "6"
  - !!int "13"
  - !!int "6"
"speed": "30 ft."
"saves":
  - "constitution": !!int "7"
"senses": "[Darkvision](/Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 11"
"languages": "Otyugh; telepathy 120 ft. (doesn't allow the receiving creature to respond\
  \ telepathically)"
"cr": "5"
"actions":
  - "desc": "The otyugh makes one Bite attack and two Tentacle attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 12 (2d8 + 3) Piercing damage,\
      \ and the target has the [Poisoned](/Mechanics/CLI/conditions.md#Poisoned) condition.\
      \ Whenever the [Poisoned](/Mechanics/CLI/conditions.md#Poisoned) target finishes\
      \ a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md), it is subjected\
      \ to the following effect. *Constitution Saving Throw:* DC 15. *Failure:* The\
      \ target's [Hit Point](/Mechanics/CLI/variant-rules/hit-points-xphb.md) maximum\
      \ decreases by 5 (1d10) and doesn't return to normal until the [Poisoned](/Mechanics/CLI/conditions.md#Poisoned)\
      \ condition ends on the target. *Success:* The [Poisoned](/Mechanics/CLI/conditions.md#Poisoned)\
      \ condition ends."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +6, reach 10 ft. *Hit:* 12 (2d8 + 3) Piercing damage.\
      \ If the target is a Medium or smaller creature, it has the [Grappled](/Mechanics/CLI/conditions.md#Grappled)\
      \ condition (escape DC 13) from one of two tentacles."
    "name": "Tentacle"
  - "desc": "*Constitution Saving Throw:* DC 14, each creature [Grappled](/Mechanics/CLI/conditions.md#Grappled)\
      \ by the otyugh. *Failure:* 16 (3d8 + 3) Bludgeoning damage, and the target\
      \ has the [Stunned](/Mechanics/CLI/conditions.md#Stunned) condition until the\
      \ start of the otyugh's next turn. *Success:* Half damage only."
    "name": "Tentacle Slam"
"source":
  - "XMM"
"image": "/Mechanics/CLI/bestiary/aberration/token/otyugh-xmm.webp"
```
^statblock

## Environment

underdark