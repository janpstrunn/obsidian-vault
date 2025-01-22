# My Obsidian Vault: Minimal

![Obsidian Vault](https://raw.githubusercontent.com/janpstrunn/obsidian-vault/refs/heads/main/Embed/footage.jpg)

Specially for new users Obsidian can be challenging to configure and make it truly unique to you, but this only applies for those who want the ultimate note-taking system, which we all know that doesn't exist.

Over my three years of Obsidian experience, I've used several plugins, templates, themes and UI configuration. I can absolutely tell that Obsidian is a great tool, but it is too easy to use it in the way it was not intended to. I'm talking about some plugins like: Excalidraw, Kanban, Tasks, Day Planner, Projects, Spaced Repetition, and Dataview.

**Obsidian barebones is great** enough to give all the necessary tools to level up your note-taking. Can I list all the Obsidian features that make this possible? Sure! Here are them: Bi-directional linking, tagging, properties, bookmarks, outliner, fuzzy finder search, templates, preview edit and vim. That's enough for a minimal experience.

My Obsidian was never fully minimalist for a long usage period, but I'm getting more into it, and thus I want to share how to tiny things about Obsidian make it a great tool.

The main **philosophy** in this vault is to **keep thing simple**, easy to manage, blazingly fast and close to the Obsidian vanilla experience.

## Who is this vault for?

- For beginners that want an **overview** of what is Obsidian experience like from a experienced user
- For people who want to **focus in writing**, and nothing else
- For those who want to **improve their own Obsidian** the "right way"
- For those who are **considering leaving Obsidian**, because it's "too complex"

## Who is this vault not for?

- For ambitious tinkerers who want to **create the perfect Obsidian vault**
- For people who want to **combine multiple workflows** into Obsidian
- For people who want to **over-scale all sorts of things**

## Using it

1. Download the source code from it, rename the vault (to your liking) and open it in your Obsidian
2. Clone the repository using `git`

```bash
git clone https://github.com/janpstrunn/obsidian-vault.git
```

## Getting Started

This vault is relatively minimal with very **few plugins** (10), that doesn't add any further than what Obsidian does well as a Markdown Text Editor. I mean: No Task Management, Kanban, Dataview and other big plugins that add breaking changes to Obsidian. **These tasks should be solved by other softwares**

### Understand the Vault Peculiarities

#### Vim Text Editor

- This is a text editor widely used for those who appreciate the advanced typing without touching the mouse. The best part of it? It's supported by default!
- The [Relative Line Numbers](https://github.com/nadavspi/obsidian-relative-line-numbers)  and [Scroll Offset](https://github.com/lijyze/scroll-offset) plugins are supposed to be used along with Vim, if you don't want to use it, so you can ignore them
- Vim is not a straight away tool. It will require a lot of practice to see its advantages over standard typing. I recommend checking some cheat sheets and videos before trying it
- To enable Vim go to Editor > Advanced > Vim key bindings
	- Don't fear the intimidating confirmation popup. Crossing this line, means you leveled up your Obsidian experience

#### The Folder Structure

It's a deviated philosophy of keeping no folders, but for good reasons.

##### Notes

- To keep all notes truly organized, this is the only folder where notes live
	- This enforces a better filename and note tags choice for a better note retrieval
	- This folder also includes fleeting notes
		- You can keep aware of your fleeting notes by tagging it as it, and then use queries or search for them
	- This style makes sure **you will never have to deal with file management** ever again
- To get back to your notes, use the Quick Switcher instead of the built-in file explorer

> Tip, if you need to apply a new convention to your notes, do it as you get to them, and not all at once. It's a very time consuming task if you are not scripting the process.

##### Journals

- The home for your daily notes (optionally)
- It's subdivided into three more folders: Daily, Week and Month (optionally)
	- I do use [Templater](https://github.com/SilentVoid13/Templater), so different note templates are applied to each folder. That's the only reason why it's divided like this
	- If you plan to use it, set the `Journal - Week Note` as your Week template, else use `Journal - Week Note - Vanilla`
		- The Templater Week Note requires to be created at **SUNDAY** to it apply correctly

> I'll be talking more in depth about templates in a further section.

##### Embed

- The place for images, videos, audio and any other file that is not a markdown file
- You don't need to be aware of it, all files are sent there automatically once added to your vault
- The reason why it exists, it to allow better image searching only. Image it as if it was a **gallery**, which you can easily search for you images through a **good naming convention**

> I'll be also talking about naming convention in a further section.

##### Templates

- This is important for a better template convenience, so the popup will always display templates only, which having to name it Template and search for it

#### Files
##### Frontmatter

This was one of my major challenges over my experience. How to keep the frontmatter powerful, easy to manage and simple? I ended with only four properties.

###### Aliases

You can use aliases in two ways, to set "quickmarks" like a specialized bookmark to retrieve a note with few keystrokes, or to allow two names refers to the same note.

###### Tags

This was another of my major challenges. What tags should I use? How to keep thing simple, so tagging is the easiest part of taking notes? The only way I could be aware of all my tags and correctly set them up is by keeping a strict amount of tags available.

You may take the advantages of nested tagging: `#tag/nested`.

Here are some examples on how you could be tagging your notes in a way it doesn't matter what it is, it just works:

- **Information Type**
	- `#procedure` - Any note that contains a practical step-by-step on how to do something
	- `#analogy` - Relate something you already know to something new
	- `#concept` - A new fact
	- `#evidence` - A fact that complements a concept
	- `#reference` - A fact that doesn't complement a concept
- **Broader Area**
	- `#personal`
		- `#personal/hobbies`
		- `#personal/feel`
	- `#work`
		- `#work/programming`
		- `#work/medicine`
		- `#work/engineering`
		- `#work/law`
- **Source**
	- `#source`
		- `#source/article`
		- `#source/book`
		- `#source/video`
- **Entity**
	- `#people`
		- `#people/coworker`
		- `#people/familiar`
		- `#people/friend`
	- `#place`
	- `#object`
- **Priority**
	- `#important`
	- `#urgent`
- **Relevance**
	- `#useful`
- **Special Tags**
	- `#query` - Notes that contains Obsidian queries. Allows to query queries, yep
	- `#index` - Notes that contains a collection of other notes to guide you

###### Source

Whenever you take notes from something you found somewhere else, note down where you obtained that information for later usage. You never know when you are gonna need it again!

By keeping the original content saved, you can now focus in writing in your own way, the way you understand and would teach it, rather than copy-pasting.

###### CSS Classes

The used snippets in this vault are from [janpstrunn/obsidian-snippets](https://github.com/janpstrunn/obsidian-snippets), which includes the `colorizer` and `elegantvagrant`

1. `img` - This centers all images
2. `justify` - Justify text (disabled by default)
3. `colorizer` - Changes note colors
	- Available colors are: `red green pink red blue yellow orange purple black grey`
	- You may use this to visually categorize notes
		- Example: All notes dedicated to people are green, year notes are red, and so on
4. `elegantvagrant` - The dark theme this vault uses

##### Templates

This vault has currently 23 templates, which you can use and take inspiration from. 

- **Information Type**
	- To easily apply information type tags, without having to manually insert it, there are the five tags I mentioned before as templates:
		- `Procedure - Template`
		- `Analogy - Template`
		- `Concept - Template`
		- `Evidence - Template`
		- `Reference - Template`
- **Journal**
	- Each daily note type has their own templates, as I mentioned before, as follows:
		- `Journal - Daily`
		- `Journal - Month`
		- `Journal - Week Note`
		- `Journal - Week Note - Vanilla`
	- The Journal Daily has four sections: Agenda, Journal, Diary and Review
		- **Agenda** - For all your today's tasks you are about to do, or completed
		- **Journal** - What you have been doing throughout the day. Use timestamps
		- **Diary** - Subdivided as:
			- Key-words - Few words, that defines you whole day
			- Emotions - What have you felt during the day?
			- Gratitude - What are the three things you are grateful for?
		- **Review** - Your thoughts you had in that day, with some other commented questions to help you reflect
- **Source**
	- `Source - Template`
		- If your note can include the original work, use it 
	- To easily apply source tags, just like information type templates
		- `Source - Article`
		- `Source - Blog Template`
		- `Source - Book Template`
		- `Source - Video Template`
- **Note types**
	- `Minimal - Template`
		- Standard template, if you wish
	- `Fleeting - Template`
		- For all your new created ephemeral notes
	- `Index - Template`
		- Tags `#index` for  you
- **Other creative**
	- Blogging - Template
	- Book - Template
	- People - Template
	- Project - Template
	- Project Proposal Note

##### Naming Convention

Naming files correctly is the core for better retrieval. Here are some tips on how you can set these conventions yourself.

```markdown
# Images

## Wallpaper
wppr-horizon.jpg
## Avatar
avatar-me.jpg
## Meme
meme-risitas.jpg
## People
pp-john-doe.jpg

# Markdown

## Languages
lang-german.md
lang-python-pandoc.md
## Templates
template-article.md
## Memories
mem-letter.md
```

#### Tabs

##### The File Explorer

As I mentioned before, all notes are sent to the right folders, except for Template notes. **This makes file management useless**, thus it is disabled. If you ever need to reach your files, I do recommend using your system explorer instead, and to do so quickly, you can open it pressing `Alt + -` (minus), and if you want to move a note to another folder use `Ctrl + ]` (right square bracket).

##### Outliner

Found at the top left sidebar. Press `Alt + 1` to quickly show the outliner and use your arrow keys to move across headings in the current files.

##### Bookmarks

Found at the top left sidebar. Press `Alt + 2` to quickly show it. This feature is fairly more interesting to deal with most frequent notes. Some predefined bookmarks are set.

- **Clean Graph**
	- It is a bookmarked Graph that hides Journals and Template folders
- **File Types**
	- Contains obsidian queries for different file types (PDF, Video, Audio, Image and Canvas)
- **Quickmarks**
	- Just like I mentioned in the aliases section, but set out from the note
	- The predefined bookmark called T takes you to this file [[Tips]]
		- Press  `Ctrl + O` (Quick Switcher) and type Tips to access it
		- As Obsidian's Quick Switcher allows fuzzy finder, you don't actually have to rely heavily on this. It's just an idea on how you can use it

##### Tags

Found at the top left sidebar. Press `Alt + 3` to quickly move to it.

##### Search

Found at the top left sidebar. Press `Ctrl + Shift + F` to quickly move to it.

##### Backlinks

Found at the top right sidebar. Visible all the time. If you plan to use Calendar, I do recommend allocating it above the backlinks.

#### Splitting

This vault sets the following keybindings to address the splitting workflow, if you wish to use it.

- `Alt + Shift + [ArrowKeys OR Vim Motion Keys]` - Move to different group
- `Ctrl + Shift + H` - Split horizontally
- `Ctrl + Shift + V` - Split vertically
- `Ctrl + W` - Close note or split note

#### Plugins

This vault doesn't have any plugins installed. That's totally in purpose, so you are aware of your own plugin configuration. But I have a list of all the must have plugins.

If you are up to using plugins, these fits perfectly into Obsidian vanilla experience, without adding any extra functionality.

##### Vim Must Have

- [Obsidian Relative Line Numbers](https://github.com/nadavspi/obsidian-relative-line-numbers) 
	- Line numbers are relative to cursor position.
- [Scroll Offset](https://github.com/lijyze/scroll-offset)
	- When scrolling using hotkeys, the page moves before the cursor reaches the bottom of the screen

##### Must Have

- [Copy Block Link](https://github.com/mgmeyers/obsidian-copy-block-link)
	- Allows you to easily copy the block reference or embed reference through your mouse or set hotkey
- [Obsidian Footnotes](https://github.com/MichaBrugger/obsidian-footnotes)
	- Allows to easily create footnotes and navigate them using keybindings
- [Journals](https://github.com/srg-kostyrko/obsidian-journal)
	- Substitute to the outdated [Calendar](https://github.com/liamcain/obsidian-calendar-plugin) and [Periodic Notes](https://github.com/liamcain/obsidian-periodic-notes) plugins
	- Has both calendar and periodic note types (daily, week, month, quaterly and year note) in a single plugin, plus some extra additions
- [Obsidian Linter](https://github.com/platers/obsidian-linter)
	- Put your markdown into standards, by allowing it to fix all markdown syntax typos for you
		- Adjust the whole file to keep it looking nice by removing extra lines, ordering footnotes...
	- When installing it, you must configure it before using!
		- Configure it to properly fix the `Linter` note, present in this vault
- [Tag Wrangler](https://github.com/pjeby/tag-wrangler)
	- To manage quickly and efficiently tags in bulk
- [Templater](https://github.com/SilentVoid13/Templater)
	- Automate boring template usage
	- The Journal Templates use this plugin
- [Obsidian Various Complements](https://github.com/tadashi-aikawa/obsidian-various-complements-plugin)
	- Gives auto-completion to Obsidian
	- Allows to easily type note pages without opening brackets (`[[Note]]`)
	- As your file gets richer in details, often used words will know display a suggestion to auto-complete it
- [Zen Mode](https://github.com/paperbenni/obsidian-zenmode)
	- Hide all UI

##### Extra

- ~~[Image Converter](https://github.com/xryul/obsidian-image-converter)~~
	- ~~Allows you to convert images to compress them~~
		- ~~Recommended to set JPG at 75% quality~~
		- ~~An alternative to JPG is AVIF, which is not supported by Image Converter, but has higher compression results~~
			- ~~I have my own alternative to that, if you know `shell script`, check this out!~~
	- Obsidian is not an image converter. You may use an external tool for image compression, like I've done myself
		- [janpstrunn/__convert-avif.sh](https://github.com/janpstrunn/dotfiles/blob/main/scripts/__convert-avif.sh)
		- [janpstrunn/__update-image-links.sh](https://github.com/janpstrunn/dotfiles/blob/main/scripts/__update-image-links.sh)
- [Janitor](https://github.com/Canna71/obsidian-janitor)
	- Looks for orphan notes and unused embeds, and optionally removes them
- [Multi Properties](https://github.com/technohiker/obsidian-multi-properties)
	- Same as Tag Wrangler, but for Properties
		- Properties don't change often, so it's a once a year plugin
- [Paste Image Rename](https://github.com/reorx/obsidian-paste-image-rename)
	- Allows you to rename images when pasting to Obsidian

#### Daily Notes

Have you ever thought about, making daily notes is a **waste of time**? Maybe, because they grow constantly and you can't review them all. That's why there are week, month and year based notes, so you can distill only **what matters** for you from these daily notes. Once you finish your year note, you can now take the gold nuggets from it and add them to your `Life` note. If you could only choose one note from your whole vault to keep, this should be the one you would keep.

## That's it!

This is all about this vault. Feel free to change it to your personal needs, but remember the philosophy behind this vault. Adding too much complexity will deteriorate your workflow.

# License

This repository is licensed under the MIT License, a very permissive license that allows you to use, modify, copy, distribute and more.