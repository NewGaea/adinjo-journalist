---
aliases: <% tp.date.now("YYYY-MMM-DD", 0, tp.file.title, "YYYY-MM-DD") %>
Origin Date: <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD") %>
---

# Daily Log - <% tp.file.title %>

## Added Pages

```base
filters:
  or:
    - note["Origin Date"] == "<% tp.file.title %>"
    - coinDate == "<% tp.file.title %>"
views:
  - type: table
    name: Table
    filters:
      and:
        - '!file.inFolder("_meta/daily")'

```
