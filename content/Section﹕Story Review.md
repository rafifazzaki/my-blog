---
title: Story Review
aliases: 
tags:
  - sections
description: analysis from media like film, games, manga, etc.
publish: "true"
---
Why does this section exist? because i want to *~~justify the time to watch/read~~* share my thoughts on the story and the media, and perhaps we can also learn something from it!
# Stories
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
  link(file.link, title) AS "Title",
  file.mtime AS "Date"
FROM #story_review
WHERE contains(publish, "true") 
SORT this.file.mtime asc
```
%%

| Title                                                                         | Date                    |
| ----------------------------------------------------------------------------- | ----------------------- |
| [[Notes (unsorted)/Perfect Blue.md\|film analysis: a girl who lost her self]] | 8:46 PM - July 21, 2024 |

%% DATAVIEW_PUBLISHER: end %%


