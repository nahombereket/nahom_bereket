---
banner: "[[Mekane Hiwet Kids Banner.jpg]]"
name: <% tp.file.title %>
aliases: 
type:
  - NGO
  - Church
tags:
  - type/mekane_hiwet
cssclasses:
  - center-titles
  - center-images
cover: "[[mekane hiwet logo.png]]"
website: https://www.mekanehiwet.org
---
![[mekane hiwet logo.png|150]]
# <% tp.file.title %>
---




```dataview
TABLE
rows.Details as "Details"
Where contains(log, this.file.name)
FLATTEN log as Details
WHERE contains(Details, this.file.name)
GROUP BY file.link as Source
SORT rows.file.day desc
```
