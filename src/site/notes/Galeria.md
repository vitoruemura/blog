---
{"dg-publish":true,"permalink":"/galeria/","dg-note-properties":{}}
---

```base
filters:
  and:
    - file.tags.contains("desenho")
views:
  - type: cards
    name: Imagens
    sort:
      - property: file.ctime
        direction: DESC
    image: note.cover
```