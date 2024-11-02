---
tags:
  - atlas
---

# Week Reviews

```dataview
list 
from #week and !"templates"
sort file.name desc
LIMIT 10
```

# Month Reviews

```dataview
list 
from #month and !"templates"
sort file.name asc
LIMIT 12
```

# Year Reviews

```dataview
list 
from #year and !"templates"
sort file.name desc
LIMIT 12
```
