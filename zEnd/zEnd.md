# zEnd

summary:: A category for items that don't fit neatly into my schema.
parents:: [[README|Home]]

## Directory Table of Contents

- [[DateAndTime-ISO8601|Date and Time: ISO 8601]]. ISO 8601 is an international standard covering the worldwide exchange and communication of date and time-related data.

```dataview
TABLE summary as "Summary", file.folder as "Folder"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "Attachments" AND file.name != "_attachments"
SORT file.name ASC
```