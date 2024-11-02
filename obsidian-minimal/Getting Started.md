# This Obsidian Vault Template

- This template is relatively minimal with very **few plugins** (10), that doesn't add any further than what Obsidian is design for: Note-taking
- The **philosophy** behind this is to **keep it simple** and aligned to the software purpose itself ^tj1e6d
	- I mean: No Task Management, Kanban, Dataview and other big plugins that add breaking changes to Obsidian

# Understanding this vault peculiarities

## Vim

- This is a text editor widely used for those who appreciate the advanced typing without touching the mouse and it's supported by default
- The [[Getting Started#^25d1b0|Relative Line Numbers]] plugin is supposed to be used along with Vim, if you don't want to use it, so you can remove the plugin
- To enable it go to Editor > Advanced > Vim key bindings

## Tabs

- ## File Explorer
	- At top left sidebar
	- Press **Alt + 1** to quickly show it
	- It has few folders organized like this
		- ### Atoms
			- Its supposed to contain all the notes of the vault
			- Distinguishing notes is supposed to be done with the tag feature
		- ### Ideas
			- Everything you just captured
			- Try creating a new note with **Ctrl + N** and it will be created in this folder by default
			- As you work with your ideas and they become actual notes, so they now belong to *Atoms*
		- ### Journals
			- Is where all daily notes live
			- Now, the Journals is organized in Daily, Week and Month folders due to [[Getting Started#^vsxqag|Templater]] plugin to automate the template insertion into those notes
			- Daily notes automatically links to respective week notes, only if the week note is created at **SUNDAY**
				- To understand why, go to [[Week Note]]
		- ### Resources
			- This is where all files that aren't markdown files live, is it a image, pdf, video or an audio
				- For images, I quite recommend using the [Image Converter](https://github.com/xryul/obsidian-image-converter) (not installed) plugin to keep them tiny
					- Change the image format to JPG in a 75% quality
						- It barely affects quality, but removes transparent background from PNG files
		- ### Tags
			- This is were all note-tags live
				- Differently from the built-in tag feature, this allows to easily see the tiny things from our lives, and to allow us to work deeply with them
			- They are related to emotions ([[Joy]], [[Love]], [[Hate]], [[Frustration]]), thoughts ([[Thought]], [[Idea]], [[Question]], [[Focus]]) and others 
		- ### Templates
			- There are many relevant templates for project notes, journal notes, templates for the Templater plugin and more
- ## Bookmarks
	- At top left sidebar
	- Press **Alt + 2** to quickly show it
	- This feature is the actual way to move across notes in your vault instead of using the File Explorer
	- Some predefined bookmarks are set
		- ### Clean Graph
			- It is a bookmarked Graph that hides Journals and Template folders
		- ### File Types
			- Contains obsidian queries for different file types (PDF, Video, Audio and Canvas
		- ### Quickmarks
			- The predefined bookmark called GS takes you to this file [[Getting Started]]
				- Just type **Ctrl + O** and write GS to quickly come back
				- As Obsidian quick switcher allows fuzzy finder, you don't actually have to rely heavily on this. It's just an idea on how you can use it
- ## Outliner
	- Bottom left sidebar
	- Press **Ctrl + '** to quickly show the outliner and manage across headings in the current file
		- Use arrow keys to move from heading to heading
- ## Search
	- Bottom left sidebar
	- Press **Ctrl + Shift + F** to quickly move to it
- ## Calendar
	- Top right sidebar
- ## Backlinks
	- Top right sidebar
	- Press **Alt + 3** to quickly show it
- ## Tags
	- It's supposed to be visible all the time for easier file querying as an alternative to creating dataview queries
	- Press **Alt + 4** to quickly move to it

## Plugins

- #### Calendar, Periodic Notes & Templater ^vsxqag
	- This is a triad plugin to manage daily notes, weekly notes, monthly notes and yearly notes
	- All Templater templates are included in the @Templates folder
		- [[Journal Note]] for Daily Notes
		- [[Week Note]]
			- The [[Old Week Note]] doesn't rely on Templater to be used
		- [[Month and Year Note]]
- #### Copy Block Link
	- The hotkey is **Ctrl + Q** for copying references, and **Ctrl + Shift + Q** for copying embed references
- #### Linter
	- The hotkey is **Ctrl + Shift + L**
	- This will adjust the whole file to keep it looking nice by removing extra lines, ordering footnotes...
	- To showcase it go to [[Linter Showcase|this note]]
- #### Relative Line Numbers ^25d1b0
	- As the Vim built-in feature is turned on, having this plugin helps to easily move around the file
- #### Style Settings
	- This plugin is configured only on Dark Mode using the Minimal Theme
- #### Footnotes Shortcut
	- This plugin will make the footnote feature usage much simpler and desired to be used
	- The hotkey is Ctrl + (backtick)
- #### Tag Wrangler
	- To manage quickly and efficiently tags in bulk
- #### Various Complements
	- Allows to easily type note pages without opening brackets (`[[Note]]`)
	- As your file gets richer in details, often used words will know display a suggestion to auto-complete it
		- Try typing `note`

## CSS Snippets

- `img`
	- All images will be centered
- `justify`
	- Justify all text
- `Notebook CSS Classes`
	- Made by CyanVoxel
	- Change the style of notes
	- All styles are in the [[Notebook CSS Classes]] note
	- To use it simply create a note and add a cssclasses property in it

# The End

- This is all about this vault. Feel free to change it to your personal needs, but remember the [[Getting Started#^tj1e6d|philosophy]] behind this vault
	- Adding too much complexity will deteriorate your worklfow