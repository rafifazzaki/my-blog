---
title: 
aliases:
---
Here you can see my 20 newest notes:

>[!tip]  Newest notes
>>``` dataview
TABLE WITHOUT ID
  link(file.link, title) AS "Title",
  file.mtime AS "Date"
SORT this.file.mtime asc
LIMIT 20
>>```

>[!tip]  Newest notes
>>``` 
TABLE WITHOUT ID
  link(file.link, title) AS "Title",
  file.mtime AS "Date"
SORT this.file.mtime asc
LIMIT 20
>>```

```dataview
TABLE file.mtime AS "Date" SORT file.mtime asc
```


>[!tip]
>```dataview
>TABLE file.mtime AS "Date" SORT file.mtime asc
>```

