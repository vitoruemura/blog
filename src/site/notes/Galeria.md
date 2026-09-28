---
{"dg-publish":true,"permalink":"/galeria/","dg-note-properties":{}}
---

```base
views:
  - type: cards
    name: Galeria
    filters:
  and:
    - file.tags.contains("desenho")
    order:
	  - file.name
    sort:
      - property: file.ctime
        direction: DESC
    image: note.cover

```