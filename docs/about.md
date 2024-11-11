# Features principali

## Impostazioni di navigazione
    - features:
      - navigation.instant
      - navigation.instant.progress
      - navigation.instant.preview
      - navigation.tracking
      - navigation.tabs

## Impostazioni estetiche
    -palette:
    - scheme: default
      primary: purple
      accent: pink
      toggle:
        icon: material/eye
        name: Switch to dark mode

    - scheme: slate
      primary: black
      accent: pink
      toggle:
        icon: material/eye-outline
        name: Switch to light mode

## Estensioni importanti
    markdown_extensions:
    - attr_list
    - pymdownx.emoji:
        emoji_index: !!python/name:material.extensions.emoji.twemoji
        emoji_generator: !!python/name:material.extensions.emoji.to_svg

        markdown_extensions:
    - attr_list
    - md_in_html
    - pymdownx.blocks.caption

## Per i cookies
    extra:
    consent:
        cookies:
         analytics: ti prego, lascia stare la mia famiglia 
        description: >- 
        Gentile Utente, la informiamo che accettando i Termini e le Condizioni di servizio
        saremo in grado di intercettare i suoi dati, di identificare i suoi tratti di ricerca
        quotidiani e, occasionalmente, verificare mediante i suoi dispositivi muniti di videocamera
        e/o strumenti di videosorveglianza se ha consumato almeno tre pasti completi al giorno.

