---
type: Character
---

<%*
const name = await tp.system.prompt("Character Name");
await tp.file.rename(name);

const level = Number(await tp.system.prompt("Level"));

const str = Number(await tp.system.prompt("STR"));
const dex = Number(await tp.system.prompt("DEX"));
const con = Number(await tp.system.prompt("CON"));
const intStat = Number(await tp.system.prompt("INT"));
const wis = Number(await tp.system.prompt("WIS"));
const cha = Number(await tp.system.prompt("CHA"));

const hp = Number(await tp.system.prompt("HP"));
const ac = Number(await tp.system.prompt("AC"));
const speed = await tp.system.prompt("Speed");

/* PRE-CALC (safe for infobox) */
function mod(x){ return Math.floor((x-10)/2); }
function fmt(x){ return x >= 0 ? `+${x}` : `${x}`; }

const initiative = fmt(mod(dex));
const passivePerception = 10 + mod(wis);

/* SHARED DATA BLOCK */
const dataBlock = `
const DATA = {
  level: ${level},
  str: ${str},
  dex: ${dex},
  con: ${con},
  int: ${intStat},
  wis: ${wis},
  cha: ${cha},
  hp: ${hp},
  ac: ${ac},
  speed: "${speed}",

  prof_str: false,
  prof_dex: false,
  prof_con: false,
  prof_int: false,
  prof_wis: false,
  prof_cha: false
};
`;

tR += `# ${name}

> [!infobox]
> ## ${name}
> Level: ${level}  
> HP: ${hp} | AC: ${ac} | Speed: ${speed}  
> Initiative: ${initiative}  
> Passive Perception: ${passivePerception}

---

## Ability Scores & Saving Throws

\`\`\`dataviewjs
${dataBlock}

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
\`\`\`

---

## Skills

\`\`\`dataviewjs
${dataBlock}

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
\`\`\`

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
`;
%>