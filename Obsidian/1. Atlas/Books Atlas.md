---
tags:
  - atlas
---

```dataview
TABLE WITHOUT ID
	status as Status,
	rows.file.link as Book
FROM  #book
WHERE !contains(file.path, "Templates")
GROUP BY status
SORT status
```