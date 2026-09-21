---
{"dg-publish":true,"permalink":"/teste/","dg-note-properties":{}}
---


```base
views:
  - type: cards
    name: View
    filters:
      and:
        - file.inFolder("Images")
    order: []
    sort:
      - property: file.ctime
        direction: DESC
    image: file.file
    cardSize: 300

```
