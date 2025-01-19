---
aliases:
  - GS
source: https://github.com/janpstrunn/obsidian-vault
tags:
  - reference
---

# Getting Started

- This template is relatively minimal with very **few plugins** (10), that doesn't add any further than what Obsidian is design for: Markdown Text Editor.
- The **philosophy** behind this is to **keep it simple** and aligned to the software purpose itself ^tj1e6d
	- I mean: No Task Management, Kanban, Dataview and other big plugins that add breaking changes to Obsidian
	- These tasks should be solved by other softwares

> [!important] Hey!
> This is a guide on how you should use this vault efficiently, by my three years of Obsidian experience. If you don't want to follow it, don't excitate to delete this file!

# Understanding this vault peculiarities

## Vim

- This is a text editor widely used for those who appreciate the advanced typing without touching the mouse. The best part of it? It's supported by default!
- The [[Getting Started#^1e5577|Relative Line Numbers]] and [[Getting Started#^5cb940|Scroll Offset]] plugins are supposed to be used along with Vim, if you don't want to use it, so you can ignore them
- To enable Vim go to Editor > Advanced > Vim key bindings
	- Don't fear the intimidating confirmation popup. Crossing this line, means you leveled up your Obsidian experience

## Folders

- ### Root Directory
	- This is where your Obsidian Vault lives, and where all notes are created by the first time
- ### Notes
	- This is were all notes should live, specifically the notes that are not ephemeral
	- No matter how you tag or categorize it, they should live all in the same place. This will make you be more intentional when naming your notes to make them more retrievable
	- The Quick Switcher is a fuzzy finder tool that is just too good to be left
- ### Journals
	- Is where all daily notes live
	- Now, the Journals is organized in Daily, Week and Month folders due to [[Getting Started#^vsxqag|Templater]] plugin to automate the template insertion into those notes
	- Daily notes automatically links to respective week notes, only if the week note is created at **SUNDAY**
		- To understand why, go to [[Journal - Week Note]]
		- If you don't want to use this template, check the [[Journal - Week Note - Vanilla]] instead
- ### Embed
	- This is where all files that aren't markdown files live, is it a image, pdf, video or an audio
	- When you add any file that is not markdown to Obsidian, it sends it there automatically
- ### Templates
	- There are many relevant templates for project notes, journal notes, templates for the Templater plugin and more

## Frontmatter

- A easy to manage frontmatter should be simple, so I'll recommend only four

### Aliases

- Every time you find a note that could be mentioned in an alternative way but refers to the same thing, the alias is the way
### Tags

- Tags is the main core of note organization, and I'm not talking about 100+ tags. Try to be very restrictive to them, so you don't get overwhelmed about which tag you should use to your note.
	- The experience should be: Create a note, immediately recognize what the note is and tag it, or let Templater do that for you
- # Some examples
	- You may also refer to [[Homepage#Tags]]
	- ## Tagging by information type
		- Procedure - Any note that contains a practical step-by-step on how to do something
		- Analogy - Relate something you already know to something new
		- Concept - A new fact
		- Evidence - A fact that complements a concept
		- Reference - A fact that doesn't complement a concept
	- ## Tagging by broader area
		- Programming
		- Medicine
		- Engineering
		- Law
		- Personal
	- ## Tagging by entity
		- People
		- Place
		- Object
	- ## Tagging by priority
		- Important
		- Urgent
	- ## Tagging by relevance
		- Useful
	- ## Special Tags
		- query - Notes that contains Obsidian queries such as [[Image]], [[Video]] and [[Audio]]
		- index - Notes that contains a collection of other notes to guide you
			- Use the [[Index - Template]] to easily apply it

### Source

- Always good to note down where have you obtained information from for later usage. You never know when you are gonna need it again

### CSS Classes

- This vault has a CSS Snippet called `colorizer` that can change the page color, based on what is in the cssclasses frontmatter
	- Just create the cssclasses frontmatter and all possibilities will popup
		- `pallette` is always required to be present!
	- You can use it to visually categorize your notes
		- Examples
			- All people dedicated notes have the green color, for year notes it's red, and so on 
			- [[People - Template]]
- This vault also have the `img` snippet, which centers all images in the vault
- The `justify` snippet allows you to justify text
- Finally the `elegantvagrant` snippet which is the theme this vault uses

## Tabs

> [!note] The File Explorer
> Where is the File Explorer tab? Well, it's turned off. As I mentioned [[Getting Started#^tj1e6d|before]] Obsidian is a Markdown Text Editor, so the  File Management should be accomplished by another tool.
> Easily open the system explorer with **Alt + -** (minus).
> Perhaps, want to easily move a note to another folder? **Ctrl + ]** (right square bracket)

- ## Outliner
	- At top left sidebar
	- Press **Alt + 1** to quickly show the outliner and move across headings in the current file
- ## Bookmarks
	- At top left sidebar
	- Press **Alt + 2** to quickly show it
	- This feature is the actual way to move across notes in your vault instead of using the File Explorer
	- Some predefined bookmarks are set
		- ### Clean Graph
			- It is a bookmarked Graph that hides Journals and Template folders
		- ### File Types
			- Contains obsidian queries for different file types (PDF, Video, Audio, Image and Canvas)
		- ### Quickmarks
			- The predefined bookmark called GS takes you to this file [[Getting Started]]
				- Just type **Ctrl + O** and write GS to quickly come back
				- As Obsidian quick switcher allows fuzzy finder, you don't actually have to rely heavily on this. It's just an idea on how you can use it
- ## Search
	- Top left sidebar
	- Press **Ctrl + Shift + F** to quickly move to it
- ## Backlinks
	- Top right sidebar
- ## Tags
	- Top left sidebar
	- It's supposed to be visible all the time for easier file querying as an alternative to creating dataview queries
	- Press **Alt + 3** to quickly move to it

## Splitting

- This vault sets the following keybindings to address splitting workflow
	- Alt + Shift + [ArrowKeys OR Vim Motion Keys]
		- Move to different group
	- Ctrl + Shift + H - Split horizontally
	- Ctrl + Shift + V - Split vertically
	- Ctrl + W - Close note or split note

## Plugins

> [!warning] Attention
> This vault doesn't have any plugin installed.

### Vim Users Must Have

- [Obsidian Relative Line Numbers](https://github.com/nadavspi/obsidian-relative-line-numbers) ^1e5577
	- Line numbers are relative to cursor position. Great for Vim users
- [Scroll Offset](https://github.com/lijyze/scroll-offset) ^5cb940
	- When scrolling using hotkeys, the page moves before the cursor reaches the bottom of the screen. Great for Vim users

### Must Have

- [Copy Block Link](https://github.com/mgmeyers/obsidian-copy-block-link)
	- Allows you to easily copy the block reference or embed reference through your mouse or set hotkey
- [Obsidian Footnotes](https://github.com/MichaBrugger/obsidian-footnotes)
	- Allows to easily create footnotes and navigate them using keybindings
- [Journals](https://github.com/srg-kostyrko/obsidian-journal)
	- Substitute to Calendar and Periodic Notes
	- Has both calendar and periodic note types in a single plugin, plus some extra additions
- [Obsidian Linter](https://github.com/platers/obsidian-linter)
	- Put your markdown into standards, by allowing it to fix all markdown syntax typos for you
		- Adjust the whole file to keep it looking nice by removing extra lines, ordering footnotes...
	- If you install Linter, configure it to properly fix [[Linter|this note]]
- [Tag Wrangler](https://github.com/pjeby/tag-wrangler) ^fca866
	- To manage quickly and efficiently tags in bulk
- [Templater](https://github.com/SilentVoid13/Templater)
	- Automate boring template usage
	- All Templater templates are included in the @Templates folder
		- [[Journal - Daily]] for Daily Notes
		- [[Journal - Week Note]]
			- The [[Journal - Week Note - Vanilla]] doesn't rely on Templater to be used
		- [[Journal - Month]] for Monthly and Yearly notes
- [Obsidian Various Complements](https://github.com/tadashi-aikawa/obsidian-various-complements-plugin)
	- Gives auto-completion to Obsidian
	- Allows to easily type note pages without opening brackets (`[[Note]]`)
	- As your file gets richer in details, often used words will know display a suggestion to auto-complete it
		- Try typing `note`
- [Zen Mode](https://github.com/paperbenni/obsidian-zenmode)
	- Hide all UI

### Extra

- [Image Converter](https://github.com/xryul/obsidian-image-converter)
	- Allows you to convert images to compress them
		- Recommended to set JPG at 75% quality
		- An alternative to JPG is AVIF, which is not supported by Image Converter, but has higher compression results
			- I have my own alternative to that, if you know `shell script`, check this out!
				- [janpstrunn/__convert-avif.sh](https://github.com/janpstrunn/dotfiles/blob/main/scripts/__convert-avif.sh)
				- [janpstrunn/__update-image-links.sh](https://github.com/janpstrunn/dotfiles/blob/main/scripts/__update-image-links.sh)
- [Janitor](https://github.com/Canna71/obsidian-janitor)
	- Looks for orphan notes and unused embeds, and optionally removes them
- [Multi Properties](https://github.com/technohiker/obsidian-multi-properties)
	- Same as [[Getting Started#^fca866|Tag Wrangler]], but for Properties
- [Paste Image Rename](https://github.com/reorx/obsidian-paste-image-rename)
	- Allows you to rename images when pasting to Obsidian

## Daily Notes

- Have you ever thought about, making daily notes is a ==waste of time==? Maybe, because they grow constantly and you can't review them all
- That's why there are week, month and year based notes, so you can distill only ==what matters== for you from these daily notes. Once you finish your year note, you can not take the gold nuggets from it and add them to your [[Life]] note
	- If you could only choose one note from your whole vault to keep, this should be the one you would keep

# That's it!

- This is all about this vault. Feel free to change it to your personal needs, but remember the [[Getting Started#^tj1e6d|philosophy]] behind this vault
	- Adding too much complexity will deteriorate your workflow