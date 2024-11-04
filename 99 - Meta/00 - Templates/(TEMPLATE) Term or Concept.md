---
banner: "https://i.pinimg.com/originals/28/e3/42/28e34224e2fe33386e4ce7eefbe8c9ff.gif"
name: <% tp.file.title %>
aliases: 
type:
  - permanent_note
tags:
  - type/permanent_note
cssclasses:
  - center-titles
  - center-images
cover: "[[deciduous-tree.png]]"
website:
---
![[deciduous-tree.png]]
# <% tp.file.title %>
---
> [!Outline] Overview
> ...


add tag on/... 
add emoji as well


```dataview
TABLE
rows.Details as "Details"
Where contains(log, this.file.name)
FLATTEN log as Details
WHERE contains(Details, this.file.name)
GROUP BY file.link as Source
SORT rows.file.day desc
```
