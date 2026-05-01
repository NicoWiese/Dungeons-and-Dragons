---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/lmop
- monster/cr/8
- monster/size/large
- monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Venomfang"
---
# [Venomfang](Mechanics\CLI\bestiary\npc/venomfang-lmop.md)
*Source: Lost Mine of Phandelver p. 63*  

```statblock
"name": "Venomfang (LMoP)"
"size": "Large"
"type": "dragon"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "12"
  - !!int "17"
  - !!int "16"
  - !!int "13"
  - !!int "15"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "6"
  - "wisdom": !!int "4"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Deception](/Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Perception](/Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/Mechanics/CLI/senses.md#Blindsight) 30 ft., [darkvision](/Mechanics/CLI/senses.md#Darkvision)\
  \ 120 ft., passive Perception 17"
"languages": "Common, Draconic"
"cr": "8"
"traits":
  - "desc": "Venomfang can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "Venomfang makes three attacks: one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:* 15\
      \ (2d10 + 4) piercing damage plus 7 (2d6) poison damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Claw"
  - "desc": "Venomfang exhales poisonous gas in a 30-foot cone. Each creature in that\
      \ area must make a DC 14 Constitution saving throw, taking 42 (12d6) poison\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Poison Breath (Recharge 5-6)"
"source":
  - "LMoP"
"image": "/Mechanics/CLI/bestiary/npc/token/venomfang-lmop.webp"
```
^statblock