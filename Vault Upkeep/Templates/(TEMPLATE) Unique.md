<%*
let title = tp.file.title
if (title.startsWith("Untitled")){
	title = await tp.system.prompt("Title");
	await tp.file.rename(title);
}
tR += "---"
%>
aliases: []
cssclasses: []
tags: []

---

```ad-info
collapse: open
**Created**: `=this.file.ctime`
**Modified**: `=this.file.mtime`
```
