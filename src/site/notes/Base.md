---
{"dg-publish":true,"permalink":"/base/","dg-note-properties":{}}
---

```base
filters:
  and:
    - file.hasTag("desenho")

formulas:
  capa: file.embeds.filter(["png"].contains(value.asFile().ext))[0]

properties:
  file.name:
    displayName: Título

views:
  - type: cards
    name: Desenhos
    order:
      - file.name
    sort:
      - property: file.ctime
        direction: DESC
    image: formula.capa
    imageFit: cover
    imageAspectRatio: 1
    cardSize: 300

```