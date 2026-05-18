---
{"dg-publish":true,"permalink":"/digital-garden/published-covers/","dg-note-properties":{}}
---



```base
properties:
  note.musician:
    displayName: Original Artist
  file.basename:
    displayName: Song
views:
  - type: table
    name: Table
    filters:
      and:
        - status == "done"
    order:
      - file.name
      - musician
      - coverLink
      - coverRoles

```
