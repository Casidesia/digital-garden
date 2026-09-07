---
{"dg-publish":true,"permalink":"/garden/staff-credits/","updated":"2026-06-16T20:58:32.852-04:00","dg-note-properties":{}}
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
