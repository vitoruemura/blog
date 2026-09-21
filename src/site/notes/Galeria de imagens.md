---
{"dg-publish":true,"permalink":"/galeria-de-imagens/","dg-note-properties":{}}
---


```base
views:
  - type: cards
    name: Gallery
    filters:
      and:
        - file.ext == "png"
    order: []
    sort:
      - property: file.ctime
        direction: DESC
    cardSize: 300
    image: file.file

```
