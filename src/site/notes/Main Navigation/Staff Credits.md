---
{"dg-publish":true,"permalink":"/main-navigation/staff-credits/","updated":"2026-05-22T13:21:58.273-04:00","dg-note-properties":{}}
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
