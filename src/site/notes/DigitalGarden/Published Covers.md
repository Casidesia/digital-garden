---
{"dg-publish":true,"permalink":"/digital-garden/published-covers/","dg-note-properties":{}}
---



```base
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
views:
  - type: table
    name: Table
    filters:
      and:
        - status == "done"
    order:
      - file.name
      - musician
      - coverRoles
      - completedDate
      - coverType

```


<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?si=veksO2ce01ttd0nU&amp;list=PLgeIqO-svJ3MfGo5PcmsO-uCMvfv_nvSe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>