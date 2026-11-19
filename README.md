# HIGER

**Higer** is a modern, high-contrast editorial serif typeface designed for display headlines, luxury branding, and contemporary magazine layouts. Currently released in its foundational **Regular** weight, Higer pairs tall, commanding vertical proportions with razor-sharp, chiselled serifs.

<img width="2160" height="1440" alt="P22HIGER" src="https://github.com/user-attachments/assets/e92ba373-5dff-4605-853a-60806695dec6" />

## Quick Sections
- [Installation Guide](./Install.md) — Desktop setup and `@font-face` web embedding
- [Glyphs](./Glyphs.md) — Comprehensive visual specimen and animated glyph set
- [Features](./Features.md) — Complete character map and OpenType tables
- [Concept & Anatomy](./Anatomy.md) — Alpine design philosophy and vertical metrics
- [Roadmap](./Roadmap.md) — Release v1.0 overview and planned family expansion
- [Structure](./Structure.md) — Repository directory breakdown and file tree
- [License](./OFL-1.1%20license.md) — Commercial and personal usage terms

---

## Introduction

The name **Higer** draws from two complementary ideas: phonetically echoing *"Higher"* to evoke vertical elevation and ambition, while nodding to its Old High German linguistic root (*Häger*), which signifies structure, boundary, and permanence.

Visually, the typeface translates the raw geometry of high-altitude alpine terrain into typographic form:

- **High Optical Contrast:** Thick, authoritative vertical stems contrast sharply against delicate hairline crossbars and curves, mirroring blinding snowfields beside sheer glacial shadows.
- **Chiselled Terminals & Serifs:** Crisp, angled serifs anchor each letterform to the baseline with structural certainty.
- **Tall Proportions:** Extended ascenders give headlines an effortless, aristocratic presence suited for print spreads, fashion mastheads, and minimalist digital interfaces.

---

## Character Sets

**Higer Regular (v1.0)** is engineered with refined spacing, custom kerning classes, and essential OpenType features for clean editorial typesetting:

- **Uppercase & Lowercase:** Full basic Latin alphabet (`A-Z`, `a-z`) and extended European diacritics
- **Numerals & Punctuation:** Proportional and tabular lining figures (`0-9`), fractions, brackets, and editorial symbols
- **Currency Symbols:** Includes standard currencies (`$`, `€`, `£`, `¥`, `₹`, `ƒ`)
- **Standard & Discretionary Ligatures (`liga`, `dlig`):** Custom-drawn ligatures including `fi`, `fl`, `ffi`, `ffl`, `fj`, `ta`, `tg`, `ts`, `ax`, `as`, and `ij` for seamless glyph flow

---

## OpenType Features

Higer includes built-in OpenType layout features accessible in Adobe Creative Cloud, Figma, and modern CSS (`font-feature-settings`):

| Feature Tag | Name | Function |
| :--- | :--- | :--- |
| **`liga`** | Standard Ligatures | Automatically joins `fi`, `fl`, `ffi`, `ffl`, and `fj` to prevent terminal collisions |
| **`dlig`** | Discretionary Ligatures | Unlocks bespoke editorial joins (`ta`, `tg`, `ts`, `ax`, `as`, `ij`) for expressive display headlines |
| **`tnum`** | Tabular Figures | Switches default proportional figures to monospaced numerals (`zero.tf`–`nine.tf`) for vertical column alignment |
| **`kern`** | Pair Kerning | Class-based spacing adjustments tuned specifically for tight display headlines |

*For complete glyph tables and CSS activation snippets, see [Features.md](./Features.md).*

---

<table>
  <tr>
    <td width="50%">
      <img width="100%" alt="P16" src="https://github.com/user-attachments/assets/60dac66a-4b41-435a-a228-8a066a11d9b1" />
    </td>
    <td width="50%">
      <img width="100%" alt="P8" src="https://github.com/user-attachments/assets/8326c1c9-3b31-4677-85e0-c6425beedd75" />
    </td>
  </tr>
</table>

---

## Installing

### Desktop (Print & Graphic Design)
1. Download the latest release from the [Releases](../../releases) page or navigate to the `Fonts/OpenType-PS/Higer.otf` directory.
2. Select `Higer.otf` (recommended for Adobe Illustrator, InDesign, Photoshop, and Figma).
3. Double-click the file and click **Install Font** (macOS) or right-click and select **Install** (Windows).

### Web (`@font-face`)
For optimal web performance, use the compressed `WOFF2` format found in `Fonts/Web-PS/Higer.woff2`[cite: 12]:

```css
@font-face {
  font-family: 'Higer';
  src: url('Fonts/Web-PS/Higer.woff2') format('woff2'),
       url('Fonts/OpenType-TT/Higer.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

h1, .editorial-headline {
  font-family: 'Higer', Georgia, serif;
  font-weight: 400;
  letter-spacing: -0.02em;
}
