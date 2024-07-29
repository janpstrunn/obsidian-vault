---
cssclasses:
  - dashboard
---

# Quick Action

- ## Recent Files
	- `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(8).file.link)`
- ## To do
	- `$=dv.list(dv.pages().where(p => p.status == "TODO").sort(f=>f.file.name,"desc").limit(8).file.link)`
- ## Waiting
	- `$=dv.list(dv.pages().where(p => p.status == "WAITING").sort(f=>f.file.name,"desc").limit(8).file.link)`

# Favorites

- ## Vault
	- [[Inbox]]
- ## Journal
	- [[Life]]
- ## Books
	- `$=dv.list(dv.pages('#book').sort(f=>f.file.name,"desc").limit(4).file.link)`

# Projects

 - ## Highlights
 - ## Guidelines

# Reports

- ## [[2024]]
	- [[May, 2024]]
	- [[June, 2024]]
	- [[July, 2024]]
	- [[August, 2024]]
	- [[September, 2024]]
	- [[October, 2024]]
	- [[November, 2024]]
	- [[December, 2024]]
- ## [[2025]]

# Stats

- ## Files (`$=dv.pages().length`)
- ## Fleetings (`$=dv.pages('"Fleetings"').length`)