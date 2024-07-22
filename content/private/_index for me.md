---
title: Welcome to Quartz
aliases: 
publish: "false"
---

See the [documentation](https://quartz.jzhao.xyz) for how to get started.

check this too:
[Private Page](https://quartz.jzhao.xyz/features/private-pages)

>[!todo]
>> [!hint]
> The folder connected to github by this command:
> git remote add upstream https://github.com/rafifazzaki/my-blog.git
> 
> (also use this): npx quartz sync --no-pull
> you can update the site with this:
>>[!example]
> npx quartz sync
> 
for rendering dataview remember doing this:> 
>>[!note]
 >https://github.com/saberzero1/quartz-syncer
>Quartz Syncer: Open Publication Center



dataview:


```query
tag:#story_review
```


>[!info]
>https://github.com/blacksmithgu/obsidian-dataview/issues/102
>``` dataview
TABLE file.tags as section from #story_review 

>[!note] that includes this too
>
>``` dataview
TABLE WITHOUT ID
  link(file.link, file.path) AS "title",
  foo AS "Foo"
FROM #story_review 

this related but not from the link
dataview
TABLE file.tags as section FROM "Folder_A" WHERE file.name != this.file.name



https://forum.obsidian.md/t/using-the-dataview-plugin-for-last-modified-and-create-time/27672


saved:

``` dataview
LIST Limit 5 
```


mtime vs ctime (modified vs created)
asc vs desc
``` dataview
TABLE WITHOUT ID
  link(file.link, title) AS "Title",
  this.file.mtime AS "Date"
FROM #story_review 
SORT this.file.mtime asc
```



https://lucide.dev/icons/