---
tags:
  - atlas
---
```dataviewjs
let c = Object.entries(dv.app.metadataCache.fileCache)
   .filter( ([name, stats]) => name.endsWith(".canvas") )
   .map( ([name, stats]) => {
     const matches = name.match(/([^/]+)\.canvas$/)
     return dv.fileLink(name, false, (matches ? matches[1] : name))
   })

dv.list(dv.array(c).sort(l => l.display, 'ASC'))
```


