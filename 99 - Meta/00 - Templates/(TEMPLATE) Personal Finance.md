---
name: <% tp.file.title %>
tags:
  - type/personal_finance
cssclasses:
  - center-titles
  - center-images
website:
---
![[Money Bag Emoji.png|150]]
# Financial Blueprint
---
> [!Attention] Overview
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
