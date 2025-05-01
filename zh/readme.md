# ZH Anki Card

| ![anki_Preview_2025-04-30_18-50-24](https://github.com/user-attachments/assets/648b2d93-e89d-41c1-bd18-3f87c93c0d0b) | ![anki_Preview_2025-04-30_18-47-13](https://github.com/user-attachments/assets/27728e63-63b6-496b-9191-949e0744871b) |
| :------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: |

## ✨ Features

- **🈶 Dual Script Display (Front & Back)**  
  Shows both simplified & traditional characters randomly.

  <details>
  <summary>More info</summary>

  Requires [CC-CEDICT](https://github.com/MarvNC/cc-cedict-yomitan/) +
  [Yomitan](https://yomitan.wiki/). Dual script display appears on both sides of
  the card using dictionary parsing.

  </details>

- **📖 Glossary Reordering**  
  Reorder and customize dictionary entries at will.

  <details>
  <summary>More info</summary>

  - Modify the `GLOSSARY_ORDER` variable (Regex-based) to reorder glossary
    entries.
  - Bold a dictionary name (`Ctrl + B`) to make it show first for a specific
    card.

  </details>

- **🖱️ Click-to-Copy Expression**  
  Click the expression on the back to copy it.

- **💬 Sentence Display with Ruby Toggle**  
  Switch between Hanzi-only and ruby-annotated sentences.

  <details>
  <summary>More info</summary>

  Requires `SentenceReading` field. Toggle button switches between plain Hanzi
  and version with ruby/furigana.

  </details>

- **🌟 Expression Highlighting**  
  Auto-highlights the expression in the sentence.

- **📚 Minimal Glossary View**  
  Only shows the first definition initially to reduce clutter.

  <details>
  <summary>More info</summary>

  Click the glossary header to expand and reveal all definitions.

  </details>

- **🖼️ Image Lightbox**  
  Images from the `Media` field display and open full-screen on click.

- **🌙 Night Mode Support**  
  Style adapts automatically to Anki night mode.

---

## 🗂️ Fields

- `Expression`
- `Glossary`
- `Reading`
- `Audio`
- `CantoAudio` (optional)
- `Sentence`
- `SentenceAudio`
- `Media`
- `Notes`
- `Hint`
- `Source`
- `DocumentTitle`
- `URL`
