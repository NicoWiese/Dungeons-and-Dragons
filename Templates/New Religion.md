---
NoteIcon: Religion
Tags: Category/Religion
type: Religion
name: New Religion
alignment: Neutral
pantheon: []
founder: Unknown
deity: []
tenets: []
holy-days: []
followers: 0
clergy: []
sacred-sites: []
rituals: []
taboos: []
region:
  - This area
influence: Low
---

<% await tp.file.move("/DM Board/The World/Religions/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewReligion");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Religion Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
> ![[z_Assets/Misc/ImagePlaceholder.png|cover hsmall]]
> ###### Basic Info
> Type | Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Founder | `=this.founder` |
> Pantheon | `=this.pantheon` |
> Deities | `=this.deity` |
> Followers | `=this.followers` |
> Influence | `=this.influence` |
> Region | `=this.region` |
> ###### Society
> Type | Stat |
> ---|---|
> Clergy | `=this.clergy` |
> Holy Days | `=this["holy-days"]` |
> ###### Practices
> Type | Stat |
> ---|---|
> Tenets | `=this.tenets` |
> Rituals | `=this.rituals` |
> Taboos | `=this.taboos` |
> Sacred Sites | `=this.sacred-sites` |

# `=this.file.name`

## Overview
Brief description of the religion, its purpose, and general philosophy.

## Deities / Divine Beings
List of major gods, spirits, or supernatural entities with descriptions.

## Tenets & Beliefs
- Core beliefs
- Moral codes
- Ethical guidelines

## Rituals & Holy Practices
- Daily rituals
- Ceremonies
- Festivals / holy days

## Clergy & Organization
- Hierarchy of priests
- Orders, sects, or monastic groups
- Training / initiation

## Sacred Sites
- Temples, shrines, holy locations
- Pilgrimage paths

## Taboos & Restrictions
- Forbidden actions
- Social / moral rules

## Followers & Influence
- Demographics
- Geographic influence
- Political or social power

## History & Origin
- Founder and foundation story
- Historical evolution

## Conflicts & Controversies
- Schisms, heresies
- Wars, persecution, rival religions

## Additional Notes
Extra lore, flavor, or hooks for campaigns

---

`=this.region`
