---
title: Story Review
aliases: 
tags:
  - sections
description: analysis from media like film, games, manga, etc.
links: "true"
---
Why does this section exist? because i want to *~~justify the time to watch/read~~* share my thoughts on the story and the media, and perhaps we can also learn something from it!

>[!tip] Stories
>``` dataview
TABLE WITHOUT ID
  link(file.link, title) AS "Title",
  file.mtime AS "Date"
FROM #story_review 
SORT this.file.mtime asc
>```
