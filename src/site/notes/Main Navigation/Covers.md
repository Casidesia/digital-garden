---
{"dg-publish":true,"permalink":"/main-navigation/covers/","updated":"2026-05-22T15:39:41.866-04:00","dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("Covers/Published")
        - '!file.fullname.contains(".base")'
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

```


<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?si=veksO2ce01ttd0nU&amp;list=PLgeIqO-svJ3MfGo5PcmsO-uCMvfv_nvSe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>