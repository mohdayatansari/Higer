# Installing 

Guide for installing **Higer-Regular** on your local operating system and embedding it on the web using CSS `@font-face`.

---

## Desktop Installation

### macOS
1. Double-click the font file (`Higer-Regular.otf`) to open **Font Book**.
2. Click **Install Font**.
3. Alternatively, drag and drop the files into your user `Library/Fonts` folder.

### Windows (10 / 11)
1. Right-click `Higer-Regular.otf`.
2. Select **Install** (or *Install for all users*).
3. The font will be available immediately across Adobe Creative Cloud, Affinity, and Office applications.

---

## Web Embedding (`@font-face`)

To use Higer on your website, host the WOFF2 file (`Higer-Regular.woff2`) on your server and include this snippet in your CSS:

```css
@font-face {
  font-family: 'Higer';
  src: url('fonts/Higer.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

h1, h2, .display-headline {
  font-family: 'Higer', serif;
  font-weight: 400;
  font-style: normal;
}
