---
{"dg-publish":true,"permalink":"/main-navigation/covered-artists/","updated":"2026-05-22T15:00:18.000-04:00","dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("Covers/Covered Artists")
        - '!file.fullname.contains(".base")'
    order:
      - file.name

```
