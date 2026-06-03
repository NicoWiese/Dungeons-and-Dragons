---
AssociatedGroup: 
Gender: 
Race: 
Age: 
Class: 
Alignment: 
Character-Role: 
Location: 
NoteIcon: npc
---

<% await tp.file.move("DM Board/The World/Non-Player Characters/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}

const statblockName = await tp.system.prompt("Enter Statblock Name", "Commoner");
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
> Condition | Healthy |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.Alignment` |
> Class | `=this.Class` |
> Character Role | `=this["Character-Role"]` |

# `=this.file.name`

## Profile

<% tp.file.cursor() %>
**<Add description here, extend it with AI Text Generator using Ctrl J>**

> [!info] Statblock
> ```statblock
> name: <% statblockName %>
> monster: <% statblockName %>
> columns: 1
> ```

```encounter-table
name: <% statblockName %>
creatures:
 - 1: <% statblockName %>