---
banner: 
date: <%tp.date.now("YYYY-MM-DD")%>T<%tp.date.now("HH:mm")%>
workout:
tags:
  - type/daily-note
cssclasses:
  - daily
  <% "- " + tp.date.now("dddd", 0, tp.file.title, "YYYYMMDD").toLowerCase() %>
---
> **Prev::** [[<% tp.date.now("YYYYMMDD", -1, tp.file.title, "YYYYMMDD") %>]]
>
> **Next::** [[<% tp.date.now("YYYYMMDD", 1, tp.file.title, "YYYYMMDD") %>]]
---
 [Google Calendar🔗]([https://calendar.google.com/](https://calendar.google.com/calendar/)
 [Cronometer 🔗](https://cronometer.com/))


# DAILY NOTE
## <% tp.date.now("dddd, MMMM Do, YYYY", 0, tp.file.title, "YYYYMMDD") %>
***
### The One With / The One Where
#### TIME
##### Log Morning


##### Evening Review


***

### Things To Get Done Today
---
- [ ] Task 1

### Extra Things If I Feel Like It
---
- [ ] Task 1

### 📅 Schedule
---
- 06:00 Wake Up
- 07:00 Breakfast

### Log
---

### 👟 Exercise
---


### 🍽️ Consumables
---

### 🃏 Habits
---

### ⌚ Time Tracking
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
