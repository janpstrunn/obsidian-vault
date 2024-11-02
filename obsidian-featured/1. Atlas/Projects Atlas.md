---
tags:
  - atlas
---
```dataview
TABLE aliases, start AS Start, deadline AS Deadline
FROM #project AND !"Archives"
SORT aliases DESC
```


