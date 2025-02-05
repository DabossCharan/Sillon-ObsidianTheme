---
aliases: 
cssclasses: 
tags:
---

```ad-info
collapse: open
**Created**: `=this.file.ctime`
**Modified**: `=this.file.mtime`
```

### This is an example of Dataview.

I use this to make a master list of every idea I ever had. Whether I actually act on them or not is a different story. At least I have them ideas. 

```dataview
TABLE WITHOUT ID file.link AS "Date", file.tasks.text, file.tasks.due
FROM #daily 
WHERE any(file.tasks, (t) => !t.fullyCompleted)
SORT file.name ASC
```

```dataview
TASK
FROM #daily
WHERE !completed
GROUP BY file.link
```

```dataview
TABLE file.tasks.text, file.tasks.created, file.tasks.due, file.tasks.completion
FROM #daily 
WHERE any(file.tasks, (t) => t.fullyCompleted)
```


