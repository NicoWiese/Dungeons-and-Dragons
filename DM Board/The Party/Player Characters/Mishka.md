---
type: Character
level: "1"
hp: "10"
ac: "10"
modifier: "2"
---

# Mishka

> [!infobox]
> ## Mishka
> Level: 1  
> HP: 10 | AC: 10 | Speed: 30  
> Initiative: +0  
> Passive Perception: 10

---

## Ability Scores & Saving Throws

```dataviewjs

const DATA = {
  level: 1,
  str: 10,
  dex: 10,
  con: 10,
  int: 10,
  wis: 10,
  cha: 10,
  hp: 10,
  ac: 10,
  speed: "30",

  prof_str: false,
  prof_dex: false,
  prof_con: false,
  prof_int: false,
  prof_wis: false,
  prof_cha: false
};


const prof = Math.ceil(DATA.level / 4) + 1;

function mod(x){ return Math.floor((x-10)/2); }
function fmt(x){ return x >= 0 ? "+"+x : ""+x; }

function save(stat, profFlag){
  let base = mod(stat);
  return profFlag ? base + prof : base;
}

dv.table(
["Stat","Score","Mod","Save"],
[
["STR", DATA.str, fmt(mod(DATA.str)), fmt(save(DATA.str, DATA.prof_str))],
["DEX", DATA.dex, fmt(mod(DATA.dex)), fmt(save(DATA.dex, DATA.prof_dex))],
["CON", DATA.con, fmt(mod(DATA.con)), fmt(save(DATA.con, DATA.prof_con))],
["INT", DATA.int, fmt(mod(DATA.int)), fmt(save(DATA.int, DATA.prof_int))],
["WIS", DATA.wis, fmt(mod(DATA.wis)), fmt(save(DATA.wis, DATA.prof_wis))],
["CHA", DATA.cha, fmt(mod(DATA.cha)), fmt(save(DATA.cha, DATA.prof_cha))]
]
);
```

---

## Skills

```dataviewjs

const DATA = {
  level: 1,
  str: 10,
  dex: 10,
  con: 10,
  int: 10,
  wis: 10,
  cha: 10,
  hp: 10,
  ac: 10,
  speed: "30",

  prof_str: false,
  prof_dex: false,
  prof_con: false,
  prof_int: false,
  prof_wis: false,
  prof_cha: false
};


const prof = Math.ceil(DATA.level / 4) + 1;

function mod(x){ return Math.floor((x-10)/2); }
function fmt(x){ return x >= 0 ? "+"+x : ""+x; }

function skill(stat, prof=false){
  return prof ? mod(stat) + prof : mod(stat);
}

dv.table(
["Skill","Value"],
[
["Acrobatics (DEX)", fmt(skill(DATA.dex))],
["Animal Handling (WIS)", fmt(skill(DATA.wis))],
["Arcana (INT)", fmt(skill(DATA.int))],
["Athletics (STR)", fmt(skill(DATA.str))],
["Deception (CHA)", fmt(skill(DATA.cha))],
["History (INT)", fmt(skill(DATA.int))],
["Insight (WIS)", fmt(skill(DATA.wis))],
["Intimidation (CHA)", fmt(skill(DATA.cha))],
["Investigation (INT)", fmt(skill(DATA.int))],
["Medicine (WIS)", fmt(skill(DATA.wis))],
["Nature (INT)", fmt(skill(DATA.int))],
["Perception (WIS)", fmt(skill(DATA.wis))],
["Performance (CHA)", fmt(skill(DATA.cha))],
["Persuasion (CHA)", fmt(skill(DATA.cha))],
["Religion (INT)", fmt(skill(DATA.int))],
["Sleight of Hand (DEX)", fmt(skill(DATA.dex))],
["Stealth (DEX)", fmt(skill(DATA.dex))],
["Survival (WIS)", fmt(skill(DATA.wis))]
]
);
```

---

## Attacks

| Name | To Hit | Damage | Notes |
|------|--------|--------|-------|
| Weapon |  |  |  |

---

## Inventory

Gold:  
Items:

---

## Features & Notes
