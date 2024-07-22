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
> - [[./index|index]]  
> - [[./Film analysis﹕a girl who lost her self|Film analysis﹕a girl who lost her self]]  
> - [[../backup old|backup old]]  
> - [[../Saved related links|Saved related links]]  
> - [[../_index for me|_index for me]]  
> - [[test case|test case]]  
> - [[./Section﹕Newest notes|Section﹕Newest notes]]  
> - [[./Section﹕Story Review|Section﹕Story Review]]  
> - [[../quartz default|quartz default]]  
> - [[../Templater Test|Templater Test]]  
>   
  
  
  
| File                                                                                                   |  
| ------------------------------------------------------------------------------------------------------ |  
| [[./index\|index]]                                                                                    |  
| [[./Film analysis﹕a girl who lost her self\|Film analysis﹕a girl who lost her self]] |  
| [[../backup old\|backup old]]                                                                  |  
| [[../Saved related links\|Saved related links]]                                                |  
| [[../_index for me\|_index for me]]                                                            |  
| [[test case\|test case]]                                                                    |  
| [[./Section﹕Newest notes\|Section﹕Newest notes]]                                                      |  
| [[./Section﹕Story Review\|Section﹕Story Review]]                                                      |  
| [[../quartz default\|quartz default]]                                                        |  
| [[../Templater Test\|Templater Test]]                                                        |  
  
  
  
  
  
| File                                                    | notes          | date                     |  
| ------------------------------------------------------- | -------------- | ------------------------ |  
| [[../Templater Test\|Templater Test]]         | Templater Test | 7:30 PM - July 21, 2024  |  
| [[../quartz default\|quartz default]]         | \-             | 7:30 PM - July 21, 2024  |  
| [[../Saved related links\|Saved related links]] | \-             | 11:22 PM - July 21, 2024 |  
  
  
  
new  
>[!tip]  Newest notes  
> | File                                                    | Date                     |  
> | ------------------------------------------------------- | ------------------------ |  
> | [[../Templater Test\|Templater Test]]         | 7:30 PM - July 21, 2024  |  
> | [[../quartz default\|quartz default]]         | 7:30 PM - July 21, 2024  |  
> | [[../Saved related links\|Saved related links]] | 11:22 PM - July 21, 2024 |  
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
  
