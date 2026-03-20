---
cssclasses:
  - four-column-list
---
### published
```dataviewjs
const pages = dv.pages("").where(p => p.file.path.includes("content/") && (p.draft === false) ); const grouped = pages.groupBy(p => p.file.folder); for (let group of grouped) { dv.header(6, group.key); dv.list(group.rows.map(p => p.file.link)); 
}
```
### unpublished
```dataviewjs
const pages = dv.pages("").where(p => p.file.path.includes("content/") && (p.draft === true || p.draft === undefined || p.draft === null) ); const grouped = pages.groupBy(p => p.file.folder); for (let group of grouped) { dv.header(6, group.key); dv.list(group.rows.map(p => p.file.link)); 
}
```
