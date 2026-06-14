---
{"dg-publish":true,"permalink":"/garden/staff-credits/","updated":"2026-05-22T15:00:09.856-04:00","dg-note-properties":{}}
---



```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("Covers/Published")
        - "!coverRoles.isEmpty()"
    order:
      - releaseDate
      - file.name
      - coverRoles
    sort:
      - property: releaseDate
        direction: ASC

```
