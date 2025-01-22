# Obsidian

summary:: Notes on Obsidian, a personal knowledge base and note-taking software application that operates on Markdown files in a Vault (repo or directory).
parents:: [[CSE]]

## Basic formatting

Obsidian uses [[Markdown]] as well as Markdown-like syntax that only works in Obsidian. I like how Obsidian automatically adds a little icon to signify external links.

Internal links:
- The Markdown syntax, e.g. `[Hello world](Hi%20world.md)` or `[Hello world](<Hi world.md>)`, works in & out of Obsidian.
- The Wikilink syntax, e.g. `[[Hi world|Hello world]]`, only works within Obsidian. 

External links: 
- Markdown syntax, e.g. `[An Example](https://example.com/foo%20bar "my tooltip")` or `[An Example](<https://example.com/foo  bar> "my tooltip)`, work in & out of Obsidian. 

Comments:
- HTML comments work in & out of Obsidian. E.g. `The <!-- best --> dog`  is rendered as: The <!-- best --> dog. 
- Obsidian comments only work in Obsidian editing view and are implemented with double-percentage (`%%`) syntax. E.g.
```text
The %%best%% dog.

%%
Block comments
can span
multiple lines
%%
```

is rendered as:
The %%best%% dog.

%%
Block comments
can span
multiple lines
%%

The Markdown image syntax works in & out of Obsidian:
- Alt, URL. E.g. `![Example](https://example.com/foo.jpg)`.
- Alt, URL, title. E.g. `![Example](https://example.com/foo.jpg "a tooltip")`.
- Alt, URL, title, href. Enclose like a regular link. E.g. `[![Example](https://example.com/foo.jpg "a tooltip")](https://example.com/foo.jpg)`.

The Obsidian image syntax only works in Obsidian:
- `![[2025-01-02_Musk_Trump_fire_This_is_fine.jpg]]`
- `![[2025-01-02_Musk_Trump_fire_This_is_fine.jpg|100]]`. Scale by width

References:
- https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax
- https://help.obsidian.md/Editing+and+formatting/HTML+content
- https://help.obsidian.md/Linking+notes+and+files/Internal+links

## Plugins

Plugins extend the functionality of Obsidian. 

Core plugins are built into Obsidian. I almost immediately configured these core plugins:
- Daily notes
- Templates

Community plugin are optional. 

Community plugins I'm using:
- [[Dataview]]. Uses metadata in your Markdown files so the files  can be queried like a database.
- Editing Toolbar
- Git
- Natural Language Dates. Allows you to enter dates with syntax like `@yesterday`. 
- Table of Contents
  - The outline available in the Obsidian interface works fine within Obsidian. It should default to be on the left, but thankfully you can just drag it to the left instead.
  - Use the Table of Contents plugin if you want a table of contents for just page for people NOT viewing the page in Obsidian. 
  - I used to manage table of contents with the "Markdown All In One" extension for Visual Studio Code.
  - If a page is so large that it needs a huge table of contents, then perhaps the page should be split into smaller pages. 

Community plugins I'm considering:
- Advanced Tables
- DataLoom
- Excalidraw
- Mxmind Mindmap
- Remotely Save

## Shortcuts

Personally I love these 2 shortcuts from spreadsheets:
- Date: `ctrl + ;`
- Time: `ctrl + :`
- FYI: In Visual Studio Code I approximate it with:
  - Now via shortcut: `ctrl + k t`
  - Now via snippet: `ctrl + space now`
- The Natural Language Dates plugin allows you to enter dates with syntax like `@yesterday`. 

Multiple cursors:
- For very specific locations:  `alt+click`
- For consecutive lines: `shift+alt+drag`
- To cancel multiple cursors: `click`

References:
- https://help.obsidian.md/User+interface/Hotkeys
- https://help.obsidian.md/Editing+and+formatting/Editing+shortcuts
- https://help.obsidian.md/Editing+and+formatting/Multiple+cursors

## Callouts

Callouts are blocks of foldable content within your notes. E.g.

The following:
```
> [!tip]
> This is a `tip` callout.
```

is rendered as:
> [!tip]
> This is a `tip` callout.

Callout formatting:
- Callouts come with an icon, a title of its type (by default), and different formatting. 
- To display as folded, suffix with a minus (-). E.g. `[!tip]-`.
- Instead of the default title, you can add your own on the first line. E.g. `[!tip] My Tip`.
- Callouts can be nested.

The types of Callouts available include: 
  -`> [!abstract]`. Aliases: `summary`, `tldr`
  -`> [!bug]`
  -`> [!danger]`. Aliases: `error`
  -`> [!example]`
  -`> [!failure]`. Aliases: `fail`, `missing`
  -`> [!info]`
  -`> [!question]`. Aliases: `help`, `faq`
  -`> [!quote]`. Aliases: `cite`
  -`> [!success]`. Aliases: `check`, `done`
  -`> [!tip]`. Aliases: `hint`, `important`
  -`> [!todo]`
  -`> [!warning]`. Aliases: `caution`, `attention`

References:
- https://help.obsidian.md/Editing+and+formatting/Callouts.

## Tags

Tag your notes to make them more searchable. E.g. Filter by tags in graph view.

Method 1: Add a tag anywhere in a note with hashtag syntax. E.g. `#meeting`. 

Method 2: Tags can be added as property in YAML provided as a list. E.g.
```yaml
---
tags:
  - meeting
  - public
```

Tag are case-insensitive and can only use these characters:
- Alphabetical. Tags MUST contain at least 1 non-numeric. It is a decades long convention that variables not start with a number.
- Numeric
- Underscore (`_`)
- Hyphen (`-`)
- Slash (`/`) for nested tags. E.g. `#meeting/public`.

Some ideas for tags:
- `#towatch`
- `#giftideas`

References:
- https://help.obsidian.md/Editing+and+formatting/Tags

## References

Official Site:
- https://obsidian.md/. Official site.
- https://obsidian.md/mobile 
- https://obsidian.md/sync. $4/mo.
- https://help.obsidian.md/Home   
- https://help.obsidian.md/Editing+and+formatting/Advanced+formatting+syntax. Tables, diagrams (with [Mermaid](https://mermaid.js.org/)), math (with [MathJax](https://www.mathjax.org/) and [LaTeX](https://en.wikipedia.org/wiki/LaTeX)).
- https://help.obsidian.md/Plugins/Bookmarks
- https://help.obsidian.md/Plugins/Templates. Boilerplates for different kinds of new notes.

Tutorials:
- https://obsidian.rocks/
- https://obsidian.rocks/getting-started-with-obsidian-a-beginners-guide/    
- https://obsidian.rocks/an-introduction-to-obsidian-properties/
- https://elizabethbutlermd.com/obsidian-notes/    
- https://bobbypowers.net/beginners-guide-to-obsidian/

Obsidian for Genealogy & Family Trees:
- https://forum.obsidian.md/t/exploring-obsidian-with-genealogy-family-trees/6855/22?page=2    
- https://www.reddit.com/r/ObsidianMD/comments/148bbep/how_can_i_make_a_family_tree_using_obsidian/

zEnd:
- https://en.wikipedia.org/wiki/Obsidian_(software)
- https://www.reddit.com/r/ObsidianMD/comments/ojclli/is_it_possible_to_use_git_with_obsidian_mobile/
- https://www.reddit.com/r/ObsidianMD/comments/k0po5z/which_is_better_wikilinks_or_markdown_links/