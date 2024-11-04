---
banner: "https://i.pinimg.com/originals/28/e3/42/28e34224e2fe33386e4ce7eefbe8c9ff.gif"
name: <% tp.file.title %>
aliases: 
type:
  - YouTube Note
tags:
  - type/youtube_note
cssclasses:
  - center-titles
  - center-images
cover: "[[youtube_logo.png]]"
website: https://www.youtube.com/itsnahombereket/
---
![[youtube_logo.png|150]]
# <% tp.file.title %>
---
insert video here
CTRL + SHIFT + T to time stamp

# Transcription
# Notes
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
