---
{"dg-publish":true,"permalink":"/galeria/","dg-note-properties":{}}
---

```base
filters: file.tags.contains("desenho")
views:
  - type: cards
    name: Galeria
    imageFit: cover
    cardSize: 200
    order:
      - file.name
    sort:
      - property: date
        direction: DESC
    image: note.cover

```