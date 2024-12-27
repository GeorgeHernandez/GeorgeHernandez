# CSE

summary:: Computer Science Engineering (CSE) stuff that I enjoy sharing.

- [Keyboard](Keyboard.md). My personal keyboard requirements and preferences.
- [Time Formatting](TimeFormatting.md). Time formatting for CSE.

```dataview
TABLE summary as "Summary", file.folder as "Folder"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "Attachments" AND file.name != "_attachments"
SORT file.name ASC
```
