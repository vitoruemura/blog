---
{"dg-publish":true,"permalink":"/galeria-de-imagens/","dg-note-properties":{}}
---


```base
filters: file.inFolder("Images")
views:
  - type: cards
    name: Gallery
    order: []
    sort:
      - property: file.ctime
        direction: DESC
    cardSize: 300
    image: file.file

```
