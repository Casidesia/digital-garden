---
{"dg-publish":true,"permalink":"/covers/covered-artists/raise-a-suilen/","updated":"2026-05-22T14:03:30.492-04:00","dg-note-properties":{}}
---


```base
filters:
  and:
    - file.inFolder("Covers/Published")
views:
  - type: table
    name: Morning Musume
    filters:
      or:
        - musician == link("Morning Musume")
        - musician == "Morning Musume"
        - musician == link("Muten Musume")
    order:
      - releaseDate
      - file.name
    sort:
      - property: releaseDate
        direction: ASC
  - type: table
    name: Carrie Underwood
    filters:
      and:
        - musician == "Carrie Underwood"
        - musician == link("Carrie Underwood")
    order:
      - releaseDate
      - file.name
    sort:
      - property: releaseDate
        direction: ASC
  - type: table
    name: ANGERME
    filters:
      and:
        - musician == "ANGERME"
        - musician == link("ANGERME")
    order:
      - releaseDate
      - file.name
    sort:
      - property: releaseDate
        direction: ASC
  - type: table
    name: Melon Kinenbi
    filters:
      and:
        - musician == "Melon Kinenbi"
        - musician == link("Melon Kinenbi")
    order:
      - releaseDate
      - file.name
    sort:
      - property: releaseDate
        direction: ASC
  - type: table
    name: RAISE A SUILEN
    filters:
      and:
        - musician == "RAISE A SUILEN"
        - musician == link("RAISE A SUILEN")
    order:
      - releaseDate
      - file.name
    sort:
      - property: releaseDate
        direction: ASC
  - type: table
    name: Nana Mizuki
    filters:
      and:
        - musician == "Nana Mizuki"
        - musician == link("Nana Mizuki")
    order:
      - releaseDate
      - file.name
    sort:
      - property: releaseDate
        direction: ASC
  - type: table
    name: Tanpopo
    filters:
      and:
        - musician == "Tanpopo"
        - musician == link("Tanpopo")
    order:
      - releaseDate
      - file.name
    sort:
      - property: releaseDate
        direction: ASC
  - type: table
    name: Changin' My Life
    filters:
      and:
        - musician == "Changin' My Life"
        - musician == link("Changin' My Life")
    order:
      - releaseDate
      - file.name
    sort:
      - property: releaseDate
        direction: ASC

```
