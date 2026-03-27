---
{"dg-publish":true,"permalink":"/home-directory/","title":"Home Dir","tags":["gardenEntry"],"dg-note-properties":{"title":"Home Dir"}}
---



```base
views:
  - type: cards
    name: Movie (List)
    filters:
      and:
        - file.hasTag("movie")
        - '!file.inFolder("Templates")'
    order:
      - file.name
      - watch time
      - watch-status
    image: note.cover
    cardSize: 180
    imageFit: contain
    imageAspectRatio: 1.45

```
