# Log

summary:: Public log by George Hernandez.

- [2024](2024/2024.md)
- [2025](2025/2025.md)

```dataview
TABLE summary as "Summary", file.folder as "Folder"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND length(file.name) = 4 AND file.name != "Attachments" AND file.name != "_attachments"
SORT file.name ASC
```
