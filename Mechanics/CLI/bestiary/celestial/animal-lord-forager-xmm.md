---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/20
- monster/environment/beastlands
- monster/environment/planar
- monster/size/medium
- monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Animal Lord; Forager"
---
# [Animal Lord; Forager](Mechanics\CLI\bestiary\celestial/animal-lord-forager-xmm.md)
*Source: Monster Manual (2024) p. 15*  

```statblock
"name": "Animal Lord; Forager (XMM)"
"size": "Medium"
"type": "celestial"
"alignment": "Neutral"
"ac": !!int "19"
"hp": !!int "323"
"hit_dice": "34d8 + 170"
"modifier": !!int "19"
"stats":
  - !!int "24"
  - !!int "25"
  - !!int "20"
  - !!int "19"
  - !!int "23"
  - !!int "22"
"speed": "60 ft., fly 60 ft. (hover), swim 60 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "12"
"skillsaves":
  - "name": "[Acrobatics](/Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+13"
  - "name": "[Athletics](/Mechanics/CLI/skills.md#Athletics)"
    "desc": "+13"
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+18"
  - "name": "[Stealth](/Mechanics/CLI/skills.md#Stealth)"
    "desc": "+13"
"damage_resistances": "cold, fire, necrotic, psychic, radiant"
"condition_immunities": "[charmed](/Mechanics/CLI/conditions.md#Charmed), [frightened](/Mechanics/CLI/conditions.md#Frightened),\
  \ [stunned](/Mechanics/CLI/conditions.md#Stunned)"
"senses": "[Truesight](/Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 28"
"languages": "all"
"cr": "20"
"traits":
  - "desc": "An animal lord represents a Forager, Hunter, or Sage (DM's choice), which\
      \ determines certain traits in this stat block."
    "name": "Animal Lordship"
  - "desc": "If the animal lord fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
  - "desc": "*Wisdom Saving Throw:* DC 20, any enemy that starts its turn in a 30-foot\
      \ [Emanation](/Mechanics/CLI/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the animal lord. *Failure:* The target has the [Charmed](/Mechanics/CLI/conditions.md#Charmed)\
      \ condition until the end of its next turn. While [Charmed](/Mechanics/CLI/conditions.md#Charmed),\
      \ the target has the [Incapacitated](/Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition."
    "name": "Lordly Presence"
  - "desc": "The animal lord has [Advantage](/Mechanics/CLI/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The animal lord makes two attacks, using Rend or Radiant Ray in any combination,\
      \ and uses Animal Spirit."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +13, reach 5 ft. *Hit:* 14 (2d6 + 7) Slashing damage\
      \ plus 7 (2d6) Force damage."
    "name": "Rend"
  - "desc": "*Ranged Attack Roll:* +12, range 120 ft. *Hit:* 20 (4d6 + 6) Radiant\
      \ damage."
    "name": "Radiant Ray"
  - "desc": "The animal lord conjures an animal spirit that strikes at a creature\
      \ and then disappears. *Dexterity Saving Throw:* DC 20, one creature the animal\
      \ lord can see within 120 feet. *Failure:* 28 (4d10 + 6) Radiant damage. *Success:*\
      \ Half damage. *Failure or Success:* The animal lord gains 20 [Temporary Hit\
      \ Points](/Mechanics/CLI/variant-rules/temporary-hit-points-xphb.md)."
    "name": "Animal Spirit"
  - "desc": "The animal lord casts one of the following spells, requiring no Material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 20):\n\
      \n**At will:** [Animal Friendship](/Mechanics/CLI/spells/animal-friendship-xphb.md),\
      \ [Animal Messenger](/Mechanics/CLI/spells/animal-messenger-xphb.md), [Speak\
      \ with Animals](/Mechanics/CLI/spells/speak-with-animals-xphb.md)\n\n**2/day\
      \ each:** [Awaken](/Mechanics/CLI/spells/awaken-xphb.md), [Greater Restoration](/Mechanics/CLI/spells/greater-restoration-xphb.md)\n\
      \n**1/day each:** [Animal Shapes](/Mechanics/CLI/spells/animal-shapes-xphb.md),\
      \ [Sunburst](/Mechanics/CLI/spells/sunburst-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The animal lord shape-shifts into a Huge or smaller version of the animal\
      \ it represents or a Medium or Small Humanoid, or it returns to its true form.\
      \ Its game statistics, other than its size, are the same in each form. Any equipment\
      \ it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the animal lord; forager can expend a use to take one of the following actions.\
  \ The animal lord; forager regains all expended uses at the start of each of its\
  \ turns."
"legendary_actions":
  - "desc": "The animal lord moves up to its [Speed](/Mechanics/CLI/variant-rules/speed-xphb.md)\
      \ without provoking [Opportunity Attacks](/Mechanics/CLI/actions.md#Opportunity%20Attack),\
      \ and it makes one Rend attack."
    "name": "Feral Strike"
  - "desc": "The animal lord makes one Radiant Ray attack."
    "name": "Radiant Strike"
"source":
  - "XMM"
```
^statblock

## Environment

planar, beastlands