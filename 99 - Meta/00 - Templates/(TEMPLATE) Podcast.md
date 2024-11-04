---
name: <% tp.file.title %>
aliases: 
type:
  - podcast
tags:
  - type/podcast-note
cssclasses: 
media: 
cover: Picture link
---
`="![Cover|250](" + this.cover + ")"`
# <% tp.file.title %>
---
>**Links**
> [(🔗 LinkedIn)]()
>**Relates To**
> - 



```dataview
TABLE
rows.Details as "Details"
Where contains(log, this.file.name)
FLATTEN log as Details
WHERE contains(Details, this.file.name)
GROUP BY file.link as Source
SORT rows.file.day desc
```
