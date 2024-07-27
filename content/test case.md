---  
title:   
aliases:   
publish: "true"  
---  
  
  
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
  
>[!tip] Stories  
>``` dataview  
TABLE WITHOUT ID  
  link(file.link, title) AS "Title",  
  file.mtime AS "Date"  
FROM #story_review   
SORT this.file.mtime asc  
>```  
  
  
  
``` dataview  
TABLE WITHOUT ID title AS "section", description AS "" FROM #sections   
```  
  
  
>[!warning]  
> - [[./Perfect Blue|Perfect Blue]]  
> - [[./index|index]]  
> - [[../backup old|backup old]]  
> - [[../is this registered|is this registered]]  
> - [[../Saved related links|Saved related links]]  
> - [[test case|test case]]  
> - [[../_index for me|_index for me]]  
> - [[../Section﹕Newest notes|Section﹕Newest notes]]  
> - [[../Section﹕Story Review|Section﹕Story Review]]  
> - [[../quartz default|quartz default]]  
> - [[../Templater Test|Templater Test]]  
>   
  
  
  
| File                                                    |  
| ------------------------------------------------------- |  
| [[./Perfect Blue\|Perfect Blue]]      |  
| [[./index\|index]]                                     |  
| [[../backup old\|backup old]]                   |  
| [[../is this registered\|is this registered]]   |  
| [[../Saved related links\|Saved related links]] |  
| [[test case\|test case]]                     |  
| [[../_index for me\|_index for me]]             |  
| [[../Section﹕Newest notes\|Section﹕Newest notes]]       |  
| [[../Section﹕Story Review\|Section﹕Story Review]]       |  
| [[../quartz default\|quartz default]]         |  
| [[../Templater Test\|Templater Test]]         |  
  
  
  
  
  
| File                                               | notes                                   | date                    |  
| -------------------------------------------------- | --------------------------------------- | ----------------------- |  
| [[../Templater Test\|Templater Test]]    | Templater Test                          | 2:57 PM - July 27, 2024 |  
| [[../quartz default\|quartz default]]    | \-                                      | 2:57 PM - July 27, 2024 |  
| [[./Perfect Blue\|Perfect Blue]] | film analysis: a girl who lost her self | 2:57 PM - July 27, 2024 |  
  
  
  
new  
>[!tip]  Newest notes  
> | File                                               | Date                    |  
> | -------------------------------------------------- | ----------------------- |  
> | [[../Templater Test\|Templater Test]]    | 2:57 PM - July 27, 2024 |  
> | [[../quartz default\|quartz default]]    | 2:57 PM - July 27, 2024 |  
> | [[./Perfect Blue\|Perfect Blue]] | 2:57 PM - July 27, 2024 |  
>   
  
  
  
>[!tip]  Newest notes  
>>``` dataview  
TABLE WITHOUT ID  
  link(file.link, title) AS "Title",  
  file.mtime AS "Date"  
SORT this.file.mtime asc  
LIMIT 20  
>>```  
  
>[!tip]  Newest notes  
>>``` dataview  
TABLE WITHOUT ID  
  link(file.link, title) AS "Title",  
  file.mtime AS "Date"  
SORT this.file.mtime asc  
LIMIT 20  
>>```  
  
