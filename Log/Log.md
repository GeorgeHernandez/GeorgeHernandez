# Log

summary:: Public log by George Hernandez.
parents:: [[README|Home]]

- [[2024]]
- [[2025]]

```dataview
TABLE summary as "Summary", file.folder as "Folder"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND length(file.name) = 4 AND file.name != "Attachments" AND file.name != "_attachments"
SORT file.name ASC
```
