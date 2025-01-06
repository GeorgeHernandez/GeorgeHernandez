# Dataview

summary:: Dataview is a community plugin that uses metadata in your Markdown files so the files  can be queried like a database.
parents:: [[Obsidian]]

After you've installed and enabled Dataview, then you need to annotate your files with metadata, then you can have any Markdown page query the files.

## Annotate

3 ways to annotate your Markdown files:

1. Frontmatter
2. Inline Fields
3. Implicit Fields

**Frontmatter** is a common Markdown extension which allows for YAML metadata to be added to the top of a page. It is natively supported by Obsidian and explained in its official documentation. Annotation via Frontmatter is hidden. E.g.

```yaml
---
alias: "document"
last-reviewed: 2021-08-17
favorite-numbers: [1, 2, 3]
thoughts:
  rating: 8
  reviewable: false
---
```

**Inline Fields** use `Key:: Value` syntax. Inline Fields are visible and can be anywhere in a file. E.g.

```text
MyField:: Hello there
**Bold Field**:: The End
favorite-numbers:: 1, 2, 3
I give this a [rating:: 5]!
This will not show the (longKeyIDontNeedWhenReading:: key).
Sanitized keys replace UpperCase with lowercase. E.g. MyField becomes myfield.
Sanitized keys replace spaces with dashes. E.g. Bold Field becomes bold-field.
```

**Implicit Fields** are automated. E.g.

```
Creation day:		file.cday
Links in file:	file.outlinks
Tags in file:		file.etags
Lists in file:	file.lists
Tasks in file:	file.tasks
Folder of file:	file.folder
Name of file:		file.name
...
```

## Query

Query your files via Markdown codeblocks. E.g.

```dataview

```
```dataviewjs

```

The types of views:

- LIST
- TABLE
- TASK
- CALENDAR

E.g. But I've replaced `dataview` for display purposes.

```text
TABLE date, summary FROM "Meetings"
WHERE CONTAINS(summary, "Alice") AND LENGTH(file.name) = 4
SORT file.name ASC
```
```text
LIST location AS "State"
WHERE type = "person" AND project = "Zero"
```

Data types for fields:

- Text
  - E.g. `Hi there`, `"Hi there"`
  - YAML allows multiline with its pipe operator.
- Number
  - E.g. `6`, `2.4`, `-80`
- Boolean
  - E.g. `true`, `false`
- Date
  - E.g. `2025-01`, `2021-04-18T04:19:35.000+06:30`. ISO 8601.
  - E.g. `dob.month = date(now).month`
  - Dates like `field.cday` available.
- Duration
  - E.g. `2 hours`, `1hr, 2 minutes`, `15days7hours`
- Link
  - E.g. `[[Page]]`, `"[[Foo]]"`. For Frontmatter, enclose with `"`.
- List
  - E.g. `[one, two, three]`, `"one", "two", "three"`. For Inline, enclose with `"`.
  - Object
    - Only available in YAML.

## References

Official

- https://blacksmithgu.github.io/obsidian-dataview/
- https://blacksmithgu.github.io/obsidian-dataview/annotation/add-metadata/
- https://blacksmithgu.github.io/obsidian-dataview/annotation/types-of-metadata/
- https://blacksmithgu.github.io/obsidian-dataview/annotation/metadata-pages/
- https://blacksmithgu.github.io/obsidian-dataview/queries/dql-js-inline/
- https://blacksmithgu.github.io/obsidian-dataview/queries/structure/ 

Tutorials

- van der Hoeven, Nicole. 2024-12-27 8:23 AM. How to use the Obsidian Dataview plugin. https://www.youtube.com/watch?v=JTObSymEvWA 
