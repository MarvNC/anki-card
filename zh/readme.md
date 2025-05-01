# ZH Anki Card

| ![anki_Preview_2025-04-30_18-50-24](https://github.com/user-attachments/assets/648b2d93-e89d-41c1-bd18-3f87c93c0d0b) | ![anki_Preview_2025-04-30_18-47-13](https://github.com/user-attachments/assets/27728e63-63b6-496b-9191-949e0744871b) |
| :------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: |

## Features ✨

- **🔀 Dual Script Display**
  <details>
  <summary>More Info</summary>

  Leverages [CC-CEDICT](https://github.com/MarvNC/cc-cedict-yomitan/) via [Yomitan](https://yomitan.wiki/) to automatically display both simplified and traditional characters. The order is randomized on both the front and back for varied practice!
  </details>

- **🔄 Customizable Glossary Order**
  <details>
  <summary>More Info</summary>

  Easily reorder Yomitan glossary entries across all cards. Switch between bilingual or monolingual views anytime, or prioritize your favorite dictionaries.
  - Customize the default order via the `GLOSSARY_ORDER` variable (uses Regex) in the card template's back side.
  - **Prioritize definitions per card:** Bold a dictionary name (`Ctrl+B` or `Cmd+B` in the editor) within the `Glossary` field to make its definition appear first for that specific card. 🔥
  </details>

- **🖱️ Click-to-Copy Expression**
  <details>
  <summary>More Info</summary>

  Need the expression quickly? Just click the main word/phrase on the back of the card, and it's instantly copied to your clipboard.
  </details>

- **💬 Sentence Display with Ruby/Hanzi Toggle**
  <details>
  <summary>More Info</summary>

  Shows the example sentence. If you provide pinyin/zhuyin in the `SentenceReading` field, a handy button appears to toggle between Hanzi-only and Ruby character display.
  </details>

- **✨ Expression Highlighting in Sentence**
  <details>
  <summary>More Info</summary>

  The main expression is automatically highlighted within the example sentence, making it easy to spot in context (works for both Hanzi and Ruby views).
  </details>

- **📖 Minimal Glossary**
  <details>
  <summary>More Info</summary>

  Keeps the card clean by initially showing only the first dictionary definition. Click the "Glossary" header to expand and see all entries when needed.
  </details>

- **🖼️ Image Lightbox**
  <details>
  <summary>More Info</summary>

  Images added to the `Media` field are displayed as thumbnails. Click them to open a full-screen lightbox view.
  </details>

- **🌙 Night Mode Ready**
  <details>
  <summary>More Info</summary>

  The card styling automatically adapts when you switch Anki to night mode for comfortable viewing.
  </details>

## Fields 📋

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
