---

## AssociatedGroup:  
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

// Ask for creature type  
let creatureType = await tp.system.prompt("Enter creature (e.g. Commoner, Guard, Zombie)", "Commoner");  
if (!creatureType) creatureType = "Commoner";  
_%>

> [!infobox]
> 
> # `=this.file.name`
> 
> ![[z_Assets/Misc/ImagePlaceholder.png|cover hsmall]]  
> [[z_Assets/Misc/ImagePlaceholder.png|Show To Players]]
> 
> ###### Basic Information
> 
> |Type|Stat|
> |---|---|
> |Home|`=this.Location`|
> |Group|`=this.AssociatedGroup`|
> |Sex|`=this.gender`|
> |Race|`=this.race`|
> |Age|`=this.age`|
> |Condition|Healthy|
> 
> ###### Rules Info
> 
> |Type|Stat|
> |---|---|
> |Alignment|`=this.alignment`|
> |Class|`=this.class`|
> |Character Role|`=this.character-role`|

# `=this.file.name`

## Profile
> [!info] Statblock
> 
> ```statblock
> name: Individual
> monster: <%* tR += creatureType %>
> columns: 1
> ```

```encounter-table
name: Individual
creatures:
 - 1: <%* tR += creatureType %>
```