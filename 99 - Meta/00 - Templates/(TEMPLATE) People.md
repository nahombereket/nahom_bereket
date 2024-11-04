---
name: <% tp.file.title %>
aliases: 
date_met: 
location:
  - Asmara, Eritrea
  - Kampala, Uganda
  - Addis Ababa, Ethiopia
  - Edmonton, Canada
type: 
relation: 
tags:
  - type/people-note
cssclasses:
  - center-images
  - center-titles
tel: 
instagram: 
email:
---

![[saturn.jpg|250]]
# <% tp.file.title %>
---
>**Links**
> [(🔗 LinkedIn)]()
>**Relates To**
> - 
> 
> 


```dataview
TABLE
rows.Details as "Details"
Where contains(log, this.file.name)
FLATTEN log as Details
WHERE contains(Details, this.file.name)
GROUP BY file.link as Source
SORT rows.file.day desc
```
