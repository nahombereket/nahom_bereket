---
banner: "https://i.pinimg.com/originals/28/e3/42/28e34224e2fe33386e4ce7eefbe8c9ff.gif"
name: <% tp.file.title %>
aliases: 
type:
  - NGO
tags:
  - type/the_rose_project
cssclasses:
  - center-titles
  - center-images
cover: "[[The Rose Project - White Logo Transparent.png]]"
website: https://www.theroseproject.org
---
![[The Rose Project - White Logo Transparent.png|150]]
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
