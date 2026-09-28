---
{"dg-publish":true,"permalink":"/galeria/","dg-note-properties":{}}
---

```base
filters:
  and:
    - file.tags.contains("desenho")
views:
  - type: cards
    name: Galeria
    sort:
      - property: note.date
        direction: DESC
    image: note.cover

```