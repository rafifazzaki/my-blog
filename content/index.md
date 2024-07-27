---  
title: First note for you  
aliases:  
  - Welcome notes  
publish: "true"  
share: "true"  
---  
Hey, welcome to my blog!  
this is the first note that you see when navigating this blog/garden..  
  
You can see some newest pages/notes that i publish here:  
  
>[!cite]  Newest notes  
>``` dataview  
TABLE WITHOUT ID title AS "notes", file.ctime AS date SORT file.mtime asc LIMIT 3  
>```  
  
  
Or you can see some topic that you may interested on the left (desktop) or if you are on mobile you can see some topic here!  
  
>[!tip] Navigating this garden  
> ``` dataview  
>TABLE WITHOUT ID title AS "section", description AS "" FROM #sections   
>```  
  
  
You can also see what notes connected with this note on the *Graph View* and which note referenced this note on *Backlinks*.  
  
I think that's all  
Thank you, and happy reading!  
  
``` dataview  
TABLE WITHOUT ID title AS "section", description AS "" FROM #sections   
```  
  
  
>[!warning]  
> - [[./Perfect Blue|Perfect Blue]]  
> - [[index|index]]  
> - [[../backup old|backup old]]  
> - [[../is this registered|is this registered]]  
> - [[../Saved related links|Saved related links]]  
> - [[./test case|test case]]  
> - [[../_index for me|_index for me]]  
> - [[../Section﹕Newest notes|Section﹕Newest notes]]  
> - [[../Section﹕Story Review|Section﹕Story Review]]  
> - [[../quartz default|quartz default]]  
> - [[../Templater Test|Templater Test]]  
>   
  
| File                                                    |  
| ------------------------------------------------------- |  
| [[./Perfect Blue\|Perfect Blue]]      |  
| [[index\|index]]                                     |  
| [[../backup old\|backup old]]                   |  
| [[../is this registered\|is this registered]]   |  
| [[../Saved related links\|Saved related links]] |  
| [[./test case\|test case]]                     |  
| [[../_index for me\|_index for me]]             |  
| [[../Section﹕Newest notes\|Section﹕Newest notes]]       |  
| [[../Section﹕Story Review\|Section﹕Story Review]]       |  
| [[../quartz default\|quartz default]]         |  
| [[../Templater Test\|Templater Test]]         |  
  
  
  
>[!tip] Stories  
>``` dataview  
TABLE WITHOUT ID  
  link(file.link, title) AS "Title",  
  file.mtime AS "Date"  
FROM #story_review   
SORT this.file.mtime asc  
>```  
  
| File                                               | notes                                   | date                    |  
| -------------------------------------------------- | --------------------------------------- | ----------------------- |  
| [[../Templater Test\|Templater Test]]    | Templater Test                          | 2:57 PM - July 27, 2024 |  
| [[../quartz default\|quartz default]]    | \-                                      | 2:57 PM - July 27, 2024 |  
| [[./Perfect Blue\|Perfect Blue]] | film analysis: a girl who lost her self | 2:57 PM - July 27, 2024 |  
  
  
  
  
>[!tip] Stories  
>``` dataview  
TABLE WITHOUT ID  
  link(file.link, title) AS "Title",  
  file.mtime AS "Date"  
FROM #story_review   
SORT this.file.mtime asc  
>```  
  
>[!tip] Stories  
>``` dataview  
TABLE link(file.link, title) AS "Title",  
  file.mtime AS "Date"  
FROM #story_review   
SORT this.file.mtime asc  
>```  
  
