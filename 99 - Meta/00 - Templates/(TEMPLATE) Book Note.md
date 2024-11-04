---
banner: 
tags:
  - type/book_note
title: "{{title}}"
subtitle: "{{subtitle}}"
author:
  - "{ author }": 
category:
  "{ category }": 
publisher:
  "{ publisher }": 
publish:
  "{ publishDate }": 
total:
  "{ totalPage }": 
cover:
  "{ coverUrl }": 
rating: 
status: unread
created:
  "{ DATE:YYYY-MM-DD HH:mm:ss }": 
updated:
  "{ DATE:YYYY-MM-DD HH:mm:ss }": 
cssclasses:
  - center-titles
  - center-images
---
![[{{localCoverImage}}|150]]

# {{title}}
---










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