---
{"dg-publish":true,"permalink":"/base/","dg-note-properties":{}}
---

```base
views:
  - type: cards
    name: Galeria
    filters:
      and:
        - file.hasTag("desenho")
    order:
      - file.name
    sort:
      - property: date
        direction: DESC
    image: file.file
    cardSize: 300

```