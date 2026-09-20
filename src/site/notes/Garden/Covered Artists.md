---
{"dg-publish":true,"permalink":"/garden/covered-artists/","updated":"2026-06-16T20:58:33.355-04:00","dg-note-properties":{}}
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
