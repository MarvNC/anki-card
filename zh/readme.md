# ZH Anki Card

| ![anki_Preview_2025-04-30_18-50-24](https://github.com/user-attachments/assets/648b2d93-e89d-41c1-bd18-3f87c93c0d0b) | ![anki_Preview_2025-04-30_18-47-13](https://github.com/user-attachments/assets/27728e63-63b6-496b-9191-949e0744871b) |
| :------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: |

## Features

- **Dual Script Display (Front & Back):** If you have
  [CC-CEDICT](https://github.com/MarvNC/cc-cedict-yomitan/) in
  [Yomitan](https://yomitan.wiki/), the script parses the dictionary and shows
  both simplified and traditional characters in a random order on both the front
  and back of the card.
- **Reordering of Glossary (Back):** Yomitan glossary entries can be reordered
  at any time for all cards, so you can choose to have bilingual or monolingual
  cards and change your mind at any time, or just change your mind on what
  dictionary is best.
  - You can customize the order by modifying the `GLOSSARY_ORDER` variable in
    the back of the card. The array uses Regex to match the dictionary names.
  - Entries with bolded dictionary names (primary definitions) appear first, so
    you can decide for a specific card what you want the primary definition to
    be just by selecting the dictionary name and pressing `Ctrl + B` to bold it
    in the Anki editor.
- **Click-to-Copy Expression (Back):** Click the main expression on the back of
  the card to copy it to the clipboard.
- **Sentence Display with Ruby/Hanzi Toggle (Back):** Displays the example
  sentence. If furigana/ruby data (`SentenceReading` field) is provided, a
  button allows toggling between the Hanzi-only version and the version with
  ruby characters.
- **Expression Highlighting in Sentence (Back):** The main expression is
  automatically highlighted within the example sentence (works for both Hanzi
  and Ruby versions).
- **Minimal Glossary (Back):** The glossary section initially shows only the
  first dictionary entry to reduce clutter. Click the header to expand and view
  all entries.
- **Image Lightbox (Back):** Images added to the `Media` field are displayed on
  the card and open in a full-screen lightbox when clicked.
- **Night Mode Support:** Automatically adapts styles for Anki's night mode.

## Fields

- Expression
- Glossary
- Reading
- Audio
- CantoAudio (optional)
- Sentence
- SentenceAudio
- Media
- Notes
- Hint
- Source
- DocumentTitle
- URL
