---
NoteIcon: Point of Interest
Tags: Category/POI
type: POI
parentlocation:
  - - - Brightshore
region:
  - This area
poi-type: Landmark
alignment: Neutral
faction:
  - The Silver Fins
leader:
status: Active
dangerlevel: Low
---



> [!infobox]
> # `=this.file.name`
> ![[z_Assets/Misc/ImagePlaceholder.png|cover hsmall]]
> ###### Location
> Type | Stat |
> ---|---|
> Parent Settlement | `=this.parentlocation` |
> Region | `=this.region` |
> Type | `=this["poi-type"]` |
> ###### Status
> Type | Stat |
> ---|---|
> Status | `=this.status` |
> Danger Level | `=this.dangerlevel` |
> Alignment | `=this.alignment` |
> ###### Control
> Type | Stat |
> ---|---|
> Faction | `=this.faction` |
> Leader | `=this.leader` |

# `=this.file.name`

## Overview
Brief description of the location and its purpose.

## Description
What does it look like? Smells, sounds, atmosphere, layout.

## Notable NPCs
- Name – Role/Description

## Encounters
- Possible combat, social, or exploration encounters

## Secrets
- Hidden truths, clues, or twists

## Loot / Rewards
- Items, gold, or story rewards

## Points of Interest (Internal)
- Sub-locations within this POI

## Story Hooks
- Why would players come here?
- What problems or opportunities exist?

## Relationships
### Internal
- Connections between NPCs/factions inside

### External
- Links to settlement, factions, or other POIs

## Background
History and origin of the location

## Additional Details
Anything extra

---

`=this.parentlocation`

`=link(this.parentlocation)`