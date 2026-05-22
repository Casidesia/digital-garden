---
{"dg-publish":true,"permalink":"/main-navigation/published-covers/","updated":"2026-05-22T12:46:00.275-04:00","dg-note-properties":{}}
---



```base
formulas:
  Untitled: "releaseDate.toString() "
properties:
  note.musician:
    displayName: Original Artist
  file.basename:
    displayName: Song
  file.name:
    displayName: Song
  note.coverRoles:
    displayName: Roles
  note.coverType:
    displayName: Collab/Solo
  note.completedDate:
    displayName: Release Date
  formula.Untitled:
    displayName: Release Date
  note.releaseDate:
    displayName: Release
views:
  - type: table
    name: Table
    filters:
      and:
        - status == "done"
    groupBy:
      property: coverType
      direction: DESC
    order:
      - releaseDate
      - file.name
      - musician
      - coverRoles
    sort:
      - property: releaseDate
        direction: ASC
    columnSize:
      note.musician: 141

```

Latest Release:
<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?si=veksO2ce01ttd0nU&amp;list=PLgeIqO-svJ3MfGo5PcmsO-uCMvfv_nvSe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>