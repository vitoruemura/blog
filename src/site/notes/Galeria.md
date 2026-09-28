---
{"dg-publish":true,"permalink":"/galeria/","dg-note-properties":{}}
---

```base
filters:
  and:
    - file.tags.contains("desenho")
formulas:
	capa: file.embeds.filter(["png"].contains(value.asFile().ext))[0]
views:
  - type: cards
    name: Imagens
    sort:
      - property: file.ctime
        direction: DESC
    image: note.cover
```