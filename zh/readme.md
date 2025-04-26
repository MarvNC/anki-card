# ZH Anki Card

![anki_Preview_2025-04-20_14-21-16](https://github.com/user-attachments/assets/726ecc38-8780-4ae0-a53e-6a48f8b21e73)

## Features

- **Dual Script Display (Front & Back):** If you have
  [CC-CEDICT](https://github.com/MarvNC/cc-cedict-yomitan/) in
  [Yomitan](https://yomitan.wiki/), the script parses the dictionary and shows
  both simplified and traditional characters in a random order on both the front
  and back of the card.
- **Click-to-Copy Expression (Back):** Click the main expression on the back of
  the card to copy it to the clipboard.
- **Pinyin Display (Back):** Shows the Pinyin reading below the expression.
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
- **Dedicated Audio Buttons (Back):** Separate, clearly labeled buttons for
  playing audio from the `Audio` (Expression), `CantoAudio` (Cantonese), and
  `SentenceAudio` fields.
- **Hint Display (Front):** Shows the content of the `Hint` field on the front
  of the card if provided.
- **Notes Display (Back):** Displays the content of the `Notes` field in a
  dedicated section.
- **Source Linking (Back):** Displays the `Source` field text and automatically
  creates a clickable link using the `URL` and `DocumentTitle` fields.
- **Responsive Design:** The card layout adjusts for better viewing on smaller
  screens.
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
