---
{"dg-publish":true,"permalink":"/galeria/","dg-note-properties":{}}
---

```base
filters: file.tags.contains("desenho")
views:
  - type: cards
    name: Galeria
    order:
      - file.name
    sort:
      - property: date
        direction: DESC
    image: note.cover
      - imageFit: cover

```