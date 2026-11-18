# Character Set & OpenType Features

**Higer** is engineered in FontLab 8 with extended Latin coverage, custom display ligatures, class-based kerning, and 9 compiled OpenType feature tables[cite: 11, 16].

---

## Character Set Overview

* **Uppercase & Lowercase:** Complete Basic Latin (`A–Z`, `a–z`) alongside extended European Latin diacritics and special characters (`Æ`, `æ`, `Ø`, `ø`, `Œ`, `œ`, `IJ`, `ij`, `Ð`, `Þ`, `Ý`, `Ŷ`, `Ÿ`, `Ź`, `Ž`, `Ż`, `ģ`)[cite: 16].
* **Numerals:** Lining figures (`0–9`) and dedicated tabular figures (`zero.tf`–`nine.tf`) for aligned columns, editorial page numbers, and data tables[cite: 11, 16].
* **Punctuation & Currency:** Standard editorial punctuation, brackets, mathematical operators, and currency symbols including the florin (`ƒ`).
* **Metrics & Spacing:** Sidebearing formulas anchored to the structural proportions of `H`, paired with class-based kerning (`kern`) tuned for high-contrast display headlines[cite: 11].

---

## Custom Ligatures (`liga`)

Higer includes 12 custom-drawn ligatures designed to eliminate stroke collisions and preserve crisp horizontal rhythm in display headlines[cite: 11, 16]:

| Ligature | Glyph Name | Description |
| :--- | :--- | :--- |
| **fi, fl, ff, ffi, ffl, fj** | `f_i`, `f_l`, `f_f`, `f_f_i`, `f_f_l`, `f_j` | Classic f-ligatures resolving terminal overlap with ascending and dotted characters[cite: 16] |
| **ta, tg, ts** | `t_a`, `t_g`, `t_s` | Custom crossbar-connected ligatures built for tight editorial wordmarks[cite: 16] |
| **ax, as** | `a_x`, `a_s` | Stylistic lowercase joins[cite: 16] |
| **ij** | `ij` | Dutch digraph ligature[cite: 16] |

---

## OpenType Layout Features

All 9 OpenType feature tables compiled in Higer[cite: 11]:

| Tag | Feature Name | Function in Higer |
| :--- | :--- | :--- |
| **`kern`** | Kerning | Class-based horizontal pair adjustments for balanced headline spacing[cite: 11] |
| **`liga`** | Standard Ligatures | Automatic substitution for all 12 custom ligatures[cite: 11, 16] |
| **`tnum`** | Tabular Figures | Replaces proportional numerals with uniform-width figures (`zero.tf`–`nine.tf`)[cite: 11, 16] |
| **`frac`** | Fractions | Formats slash-separated numbers into diagonal fractions[cite: 11] |
| **`sups`** | Superscripts | Substitutes standard figures with properly scaled superior numerals[cite: 11] |
| **`ordn`** | Ordinals | Automatically formats ordinal indicators (such as `1st`, `2nd`, `Nº`)[cite: 11] |
| **`mark`** | Mark Positioning | Anchor-based attachment for accurate diacritic placement[cite: 11] |
| **`locl`** | Localized Forms | Language-specific glyph substitutions (including Czech/Slovak `lcaron.loclCSZ` and `tcaron.loclCSZ`)[cite: 11, 16] |
| **`aalt`** | Access All Alternates | Exposes all alternate glyphs and ligatures in the Glyphs panel of design software[cite: 11] |
