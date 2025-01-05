# CSE

summary:: Computer Science Engineering (CSE) stuff that I enjoy sharing.
parents:: [[Cognition]]

- [Google Wish List](GoogleWishList.md). Just a few personal requests for Google.
- [Keyboard](Keyboard.md). My personal keyboard requirements and preferences.
- [Markdown](Markdown.md). Notes on Markdown, a lightweight markup language that converts into HTML.
- [Time Formatting](TimeFormatting.md). Time formatting for CSE.

```dataview
TABLE summary as "Summary", file.folder as "Folder"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "Attachments" AND file.name != "_attachments"
SORT file.name ASC
```
