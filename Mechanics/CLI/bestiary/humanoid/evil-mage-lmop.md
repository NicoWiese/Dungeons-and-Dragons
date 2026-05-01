---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/lmop
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Evil Mage"
---
# [Evil Mage](Mechanics\CLI\bestiary\humanoid/evil-mage-lmop.md)
*Source: Lost Mine of Phandelver p. 57*  

Evil mages (such as Iarno Albrek and Hamun Kost) hunger for arcane power and dwell in isolated places, where they can perform terrible magical experiments without interference.

```statblock
"name": "Evil Mage (LMoP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Arcana](/Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[History](/Mechanics/CLI/skills.md#History)"
    "desc": "+5"
"gear":
  - "[quarterstaff](/Mechanics/CLI/items/quarterstaff-xphb.md)"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "1"
"traits":
  - "desc": "The mage is a 4th-level spellcaster that uses Intelligence as its spellcasting\
      \ ability (spell save DC 13; +5 to hit with spell attacks). The mage knows the\
      \ following spells from the wizard's spell list:\n\n**Cantrips (at will):**\
      \ [light](/Mechanics/CLI/spells/light-xphb.md), [mage hand](/Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [shocking grasp](/Mechanics/CLI/spells/shocking-grasp-xphb.md)\n\n**1st level\
      \ (4 slots):** [charm person](/Mechanics/CLI/spells/charm-person-xphb.md), [magic\
      \ missile](/Mechanics/CLI/spells/magic-missile-xphb.md)\n\n**2nd level (3 slots):**\
      \ [hold person](/Mechanics/CLI/spells/hold-person-xphb.md), [misty step](/Mechanics/CLI/spells/misty-step-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +1 to hit, reach 5 ft., one target. *Hit:* 3 (1d8\
      \ - 1) bludgeoning damage."
    "name": "Quarterstaff"
"source":
  - "LMoP"
"image": "/Mechanics/CLI/bestiary/humanoid/token/evil-mage-lmop.webp"
```
^statblock