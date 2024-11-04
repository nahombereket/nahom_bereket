---
name: <% tp.file.title %>
aliases: []
type:
  - series
tags:
  - type/series_note
cssclasses: 
cover: Picture link
---
# <% tp.file.title %>
---
>[!]-
>**Links**
> [(🔗 IMDb)]()
>**Relates To**
> - 
> 
> `="![LinkedinCover|250](" + this.cover + ")"`


```dataview
TABLE
rows.Details as "Details"
Where contains(log, this.file.name)
FLATTEN log as Details
WHERE contains(Details, this.file.name)
GROUP BY file.link as Source
SORT rows.file.day desc
```
