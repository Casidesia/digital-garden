---
{"dg-publish":true,"permalink":"/main-navigation/published-covers/","updated":"2026-05-22T14:43:41.932-04:00","dg-note-properties":{}}
---

Latest Release:
<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?si=veksO2ce01ttd0nU&amp;list=PLgeIqO-svJ3MfGo5PcmsO-uCMvfv_nvSe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


```base
properties:
  note.musician:
    displayName: Original Artist
  file.name:
    displayName: Song
  note.coverRoles:
    displayName: Roles
  note.coverType:
    displayName: Collab/Solo
  note.releaseDate:
    displayName: Release Date
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
      note.musician: 174

```

