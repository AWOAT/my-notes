---
tags:
  - Faction
---








~~~base
views:
  - type: cards
    name: CardView
    filters:
      and:
        - file.hasTag("NPC")
        - file.hasTag("Knighthawks")
    order:
      - file.name
    image: note.portrait

~~~





