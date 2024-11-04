---
banner: "https://i.pinimg.com/originals/28/e3/42/28e34224e2fe33386e4ce7eefbe8c9ff.gif"
name: <% tp.file.title %>
aliases: 
type:
  - relationship
tags:
  - type/relationship_note
cssclasses:
  - center-titles
  - center-images
cover: "[[Sparkling Pink Heart Emoji.png]]"
website:
---
![[Sparkling Heart Emoji.png]]
# <% tp.file.title %>
---
> [!Outline] Overview
> ...




```dataview
TABLE
rows.Details as "Details"
Where contains(log, this.file.name)
FLATTEN log as Details
WHERE contains(Details, this.file.name)
GROUP BY file.link as Source
SORT rows.file.day desc
```
