# Templates

summary:: My Obsidian templates.

- [Log](Log.md)
- [Note](Note.md)

```dataview
TABLE summary as "Summary", file.folder as "Folder"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "Attachments" AND file.name != "_attachments"
SORT file.name ASC
```