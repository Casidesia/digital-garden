---
{"dg-publish":true,"permalink":"/digital-garden/published-covers/","dg-note-properties":{}}
---



```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("Covers")
        - Status == "done"
    order:
      - file.name
      - musician
      - soloLines
      - coverLink
      - coverRoles
      - coverType
      - completedDate
    sort: []
    columnSize: {}

```
