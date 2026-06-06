---
NoteIcon: Settlement
Tags: Category/Settlement
Community-Size: Outpost
Alignment: Lawful Neutral
Government: Merchant Republic
type: Settlement
politics: Council
leader:
guildsgroups:
  - The Golden Sands
  - The Silver Fins
  - The Sea Rats
  - Harken's Lot
  - The Iron Ledger
region:
size: Small city
population: 0
commonraces:
  - Humans
  - Dwarves
religion:
  - Lathander
exports:
  - Glintscale Ale
  - Fish
  - Shadowshard Crystals
imports:
  - Potions
  - Weapons
  - General Goods
---



> [!infobox]
> # `=this.file.name`
> ![[z_Assets/Misc/MapPlaceholder.png|cover hsmall]]
> [[z_Assets/Misc/MapPlaceholder.png|Show To Players]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Travel (`=[[Party Configuration]].TravelMethod` / `=[[Party Configuration]].HoursPerDay` hrs per day)
> ###### [[DM Board/# Party Configuration]]  / [[Exhaustion]]:  `=[[Party Configuration]].ExhaustionLevel`
> Destination |  Travel Days  |
> ---|---|
> [[Enter Settlement Name]] | 🕓`= round(90 * ([[Party Configuration]].MinutesPerMile * choice([[Party Configuration]].ExhaustionLevel > 1, 2, 1)) / 60 / [[Party Configuration]].HoursPerDay, 1)` |
> ###### Politics
> Type |  Stat |
> ---|---|
> Government Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> Guilds & Groups | `=this.guildsgroups` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |


# `=this.file.name`
## Overview
A city of white stone and a kaleidoscope of colourful flags that stands proudly on the shore of the Singing Stone Isles. Nestled in a natural harbour of towering grey cliffs topped with green pastures, the city serves as a mercantile hub in the South-East. It was already prosperous, but saw even more growth after the recent discovery of [[Shadowshard Crystals]] close to the town of [[Hollowcove]]. 

The city is structured around fishing, trade, and the production of a local speciality: Glintscale Ale. It is situated right next to a vast and colourful natural wonder known as the [[Shimmering Reef]], where a  unique species of fish allows locals to brew their famous ale. 

[[Brightshore]] also looks out directly onto [[The Singing Stones]], enormous ancient chime-like stones that sing at tide's change. Pockmarked throughout the bay however are also natural caves of various sizes that peer into inky depths below the sandy bottom. 

### Placeholder Map
![[z_Assets/Misc/MapPlaceholder.png|Placeholder Map]]
[[z_Assets/Misc/MapPlaceholder.png|open outside]]

### Placeholder Picture
![[z_Assets/Misc/ImagePlaceholder.png|Placeholder Picture]]
[[z_Assets/Misc/ImagePlaceholder.png|open outside]]

Placeholder

## Notable NPCs
Placeholder

## Profile
Placeholder

## Story
Placeholder

## Points of Interest
[[Shimmering Reef]]
[[Whiteharbour]]
[[The Kraken's Maw]]
[[The Broken Tooth]]
[[The Tree of a Thousand Colours]]
[[Songstone Waterfront]]
## Valuables
Placeholder

## Internal Relationships
[[The Three Seats of Brightshore]]

## Outward Relationships
Placeholder

## Background
Placeholder

## Additional Details
Placeholder

`=this.region`


`=link(this.region)`