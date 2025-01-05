# CSE

summary:: Computer Science Engineering (CSE) stuff that I enjoy sharing.
parents:: [[Cognition]]

- [[GoogleWishList|Google Wish List]]. Just a few personal requests for Google.
- [[Keyboard]]. My personal keyboard requirements and preferences.
- [[Markdown]]. Notes on Markdown, a lightweight markup language that converts into HTML.
- [[Obsidian]]. Notes on Obsidian, a personal knowledge base and note-taking software application that operates on Markdown files in a Vault (repo or directory).
- [[TimeFormatting|Time Formatting]]. Time formatting for CSE.

```dataview
TABLE summary as "Summary", file.folder as "Folder"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "Attachments" AND file.name != "_attachments"
SORT file.name ASC
```
