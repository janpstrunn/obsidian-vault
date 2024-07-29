---

kanban-plugin: board

---

## ![[flower.gif|50]]<h1 style="text-align: center;">Stats</h1>

- [ ] # Files (`$=dv.pages().length`)
- [ ] # Fleetings (`$=dv.pages('"1. Projects/Fleetings"').length`)
- [ ] # Recent Files
	`$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(10).file.link)`
- [ ] # To do
	`$=dv.list(dv.pages('#TODO').sort(f=>f.file.name,"desc").limit(4).file.link)`


## ![[book.gif|50]]<h1 style="text-align: center;">Personal</h1>

- [ ] # Journal
- [ ] # Books


## ![[diamond.gif|50]]<h1 style="text-align: center;">Projects</h1>

- [ ] # Monthly




%% kanban:settings
```
{"kanban-plugin":"board","list-collapse":[false,false,false]}
```
%%