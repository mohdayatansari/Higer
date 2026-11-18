# Installing & Using Higer

Instructions for installing **Higer** on your desktop system and embedding it via CSS `@font-face` on the web.

---

## Desktop Installation

1. **Download & Extract:** Open the latest release folder and locate the `Fonts/` directory.
2. **Choose Your Format:**
   * **OpenType-PS (`.otf`):** Recommended for print design, Adobe Creative Cloud apps (Illustrator, Photoshop, InDesign), and high-end desktop publishing.
   * **OpenType-TT (`.ttf`):** Recommended for Microsoft Office, system-wide desktop apps, and general office documents.
3. **Install:**
   * **macOS:** Double-click the `.ttf` or `.otf` file and click **Install Font** in Font Book.
   * **Windows:** Right-click the font file and select **Install** (or install for all users).

---

## Web Embedding (`@font-face`)

To use Higer on your website or Framer portfolio (`ayat.framer.website`), use the production-ready WOFF2 file located in `Fonts/Web-PS/`:

```css
@font-face {
  font-family: 'Higer';
  src: url('./Fonts/Web-PS/Higer.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

/* Example Usage for Display Headlines */
h1, .display-heading {
  font-family: 'Higer', serif;
  font-weight: 400;
  letter-spacing: -0.02em;
}
