---
title: First note for you
aliases:
  - Welcome notes
publish: "true"
share: "true"
---
# Hello, 
welcome to my blog!
this is the first note that you see when navigating this blog/garden..

You can see some newest pages/notes or browse through section that i publish here:

# Newest Notes
You can see my three newest-updated notes here (it will always updated!)
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID link(file.link, title) AS "Notes", file.ctime AS Date WHERE contains(publish, "true") SORT file.mtime asc LIMIT 3
```
%%

| Notes                                                                         | Date                    |
| ----------------------------------------------------------------------------- | ----------------------- |
| [[Notes (unsorted)/Perfect Blue.md\|film analysis: a girl who lost her self]] | 2:57 PM - July 27, 2024 |
| [[Section﹕Story Review.md\|Story Review]]                                     | 4:10 PM - July 27, 2024 |
| [[index.md\|First note for you]]                                              | 4:10 PM - July 27, 2024 |

%% DATAVIEW_PUBLISHER: end %%
# Navigating this Garden
You can see some topic that you may interested on the left (desktop) or if you are on mobile you can see some topic here!
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID link(file.link, title) AS "Section", description AS "Description" FROM #sections WHERE contains(publish, "true") 
```
%%

| Section                                           | Description                                       |
| ------------------------------------------------- | ------------------------------------------------- |
| [[Section﹕Story Review.md\|Story Review]]         | analysis from media like film, games, manga, etc. |
| [[Section﹕Newest notes.md\|Section﹕Newest notes]] | \-                                                |

%% DATAVIEW_PUBLISHER: end %%


# Graph? Backlinks?
You can see on each note what notes it connected with using *Graph View* and you can also see what note referenced your opened note on *Backlinks*.

# Thank you!
I think that's all
Thank you, and happy reading!