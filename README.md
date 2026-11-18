# HIGER

**Higer** is a modern, high-contrast editorial serif typeface designed for display headlines, luxury branding, and contemporary magazine layouts. Currently released in its foundational **Regular** weight, Higer pairs tall, commanding vertical proportions with razor-sharp, chiselled serifs.

<img width="2160" height="1440" alt="P22HIGER" src="https://github.com/user-attachments/assets/e92ba373-5dff-4605-853a-60806695dec6" />

## Quick Sections
* [Installation Guide](./INSTALL.md) — Desktop setup and `@font-face` web embedding
* [Glyph & Features](./FEATURES.md) — Complete character map and OpenType tables
* [Concept & Anatomy](./ANATOMY.md) — Alpine design philosophy and vertical metrics
* [Roadmap](./Roadmap.md) — Release v1.0 overview and planned family expansion
* [Structure](./STRUCTURE.md) — Repository directory breakdown and file tree
* [License](./LICENSE.md) — Commercial and personal usage terms
* [Glyph Showcase](./GLYPHS.md) — Comprehensive visual specimen and animated glyph set

---

## Design Concept & Anatomy

The name **Higer** draws from two complementary ideas: phonetically echoing *"Higher"* to evoke vertical elevation and ambition, while nodding to its Old High German linguistic root (*Häger*), which signifies structure, boundary, and permanence.

Visually, the typeface translates the raw geometry of high-altitude alpine terrain into typographic form:

* **High Optical Contrast:** Thick, authoritative vertical stems contrast sharply against delicate hairline crossbars and curves, mirroring blinding snowfields beside sheer glacial shadows.
* **Chiselled Terminals & Serifs:** Crisp, angled serifs anchor each letterform to the baseline with structural certainty.
* **Tall Proportions:** Extended ascenders give headlines an effortless, aristocratic presence suited for print spreads, fashion mastheads, and minimalist digital interfaces.

---

## Character Set & OpenType Features

**Higer Regular (v1.0)** is engineered with refined spacing, custom kerning classes, and essential OpenType features for clean editorial typesetting:

* **Uppercase & Lowercase:** Full basic Latin alphabet (`A-Z`, `a-z`)
* **Numerals & Punctuation:** Lining figures (`0-9`), standard punctuation, brackets, and editorial symbols
* **Currency Symbols:** Includes standard currencies (`$`, `€`, `£`, `¥`, `₹`, `ƒ`)
* **Standard & Discretionary Ligatures (`liga`, `dlig`):** Custom-drawn ligatures including `fi`, `fl`, and `t_g` for seamless glyph flow
* **Metrics & Kerning (`kern`):** Custom sidebearing formulas and class-based kerning pairs tuned for large display sizes

---

## Installing & Using Higer

### Desktop (Print & Graphic Design)
1. Download the latest release from the [Releases](../../releases) page or navigate to the `Fonts/OpenType-PS/Higer.otf` directory.
2. Select `Higer.otf` (recommended for Adobe Illustrator, InDesign, Photoshop, and Figma).
3. Double-click the file and click **Install Font** (macOS) or right-click and select **Install** (Window.


<table>
  <tr>
    <td width="50%">
      <video src="https://github.com/user-attachments/assets/148faa82-06e7-46d8-aac0-e57be38570c8" controls="controls" muted="muted" autoplay="autoplay" loop="loop" width="100%"></video>
    </td>
    <td width="50%">
      <video src="https://github.com/user-attachments/assets/e029a77d-497e-4e19-b116-cb29270a06cf" controls="controls" muted="muted" autoplay="autoplay" loop="loop" width="100%"></video>
    </td>
  </tr>
</table>


### Web (`@font-face`)
For optimal web performance, use the compressed `WOFF2` format found in `Fonts/Web-PS/Higer.woff2`:

```css
@font-face {
  font-family: 'Higer';
  src: url('fonts/woff2/Higer-Regular.woff2') format('woff2'),
       url('fonts/ttf/Higer-Regular.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

h1, .editorial-headline {
  font-family: 'Higer', Georgia, serif;
  font-weight: 400;
  letter-spacing: -0.02em;
}
