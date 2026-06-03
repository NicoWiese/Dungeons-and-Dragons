---
AssociatedGroup: 
Gender: 
Race: 
Age: 
Occupation: 
Disposition: 
Location: 
NoteIcon: npc
---

<% await tp.file.move("DM Board/The World/Non-Player Characters/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewMinorNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Minor NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
> ![[z_Assets/Misc/ImagePlaceholder.png|cover hsmall]]
> [[z_Assets/Misc/ImagePlaceholder.png|Show To Players]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `=this.Location` |
> Group | `=this.AssociatedGroup` |
> Sex | `=this.Gender` |
> Race | `=this.Race` |
> Age | `=this.Age` |
> Occupation | `=this.Occupation` |
> Disposition | `=this.Disposition` |

# `=this.file.name`

## Quick Profile

<% tp.file.cursor() %>
**<Add a brief description here, such as appearance, personality, and role in the scene>**

## At a Glance
- First impression:
- Mannerisms:
- Voice:
- Wants:
- Knows:
- Useful rumor:
- Secret:

## Roleplay Notes
- How they react to strangers:
- How they react to danger:
- What they might ask the party for:
- What they might offer the party:

## Connections
- Associated group:
- Important relationships:
- Regular location:

## Additional Notes
Extra details or DM notes