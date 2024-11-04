---
banner: "https://i.pinimg.com/originals/28/e3/42/28e34224e2fe33386e4ce7eefbe8c9ff.gif"
name: <% tp.file.title %>
aliases: 
type:
  - YouTube Script
tags:
  - type/youtube_script
cssclasses:
  - center-titles
  - center-images
cover: "[[The Rose Project - White Logo Transparent.png]]"
website: https://www.youtube.com/itsnahombereket/
---
![[youtube_logo.png|150]]
# <% tp.file.title %>
---
# 1. Pitch Doc
the bulk of the pitch is images

> [!info] 
>one-pager with video concepts



> [!info] Title Options
> - title
> - title


> [!info] thumbnail options (3 things rule)
> - Nahom
> - context
> - text TBD

> [!info] TLDR: Too Long Didn’t Read
> What is the key takeaway from this story?
> .
> .
> .
> What is “huge if true” about this story?
> (The optimistic bit. What about it could be huge and help people?)
> .
> .
> .


> [!info] Visual Abstract: a list of the visuals in theoretical order like an abstract paper for a research paper but visual. Which should make someone curious? Say why is that? A visual pitch! Make the audience root for a breakdown of the concept so they can be hopeful and look forward to the conclusion or the future.
> _Visual List_: in theoretical order
> Intro
> .
> .
> .
> PART I: text
> -  text?
> 	- text?
> -  text?
> 	- text?
> PART II: text
> -  text?
> 	- text?
> -  text?
> 	- text?
> PART III: text
> -  text?
> 	- text?
> -  text?
> 	- text?
> Conclusion
> .
> .
> .




> [!note] key visuals
> It could be a demonstration like how to do something(example of Simone Giertz showing how to make something), the key visual keeps recurring in the video it is the guiding piece that you need to see in order to understand what is going on.
A good video has ke visuals = anything you must draw or show to prove a point, otherwise it should have been left as an essay - there wouldn’t be a point to making a video. It’s the napkin rule, where if you need to draw on somthing and use the word this “this goes here and then does this” then that is a good _visual_. Show dont tell. The visual needs to help the explanation.


# 2. Info Doc




# 3. Outline




# 4. Script


```dataview
TABLE
rows.Details as "Details"
Where contains(log, this.file.name)
FLATTEN log as Details
WHERE contains(Details, this.file.name)
GROUP BY file.link as Source
SORT rows.file.day desc
```
