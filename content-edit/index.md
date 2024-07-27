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
>```dataview
LIST
>```

```dataview
TABLE
```


>[!tip] Stories
>``` dataview
TABLE WITHOUT ID
  link(file.link, title) AS "Title",
  file.mtime AS "Date"
FROM #story_review 
SORT this.file.mtime asc
>```

```dataview
TABLE title AS "notes", file.ctime AS date SORT file.mtime asc LIMIT 3 
```



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

