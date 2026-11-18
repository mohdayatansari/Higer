# Character Set & OpenType Features

**Higer** is engineered in FontLab 8 with comprehensive Extended Latin coverage, editorial symbols, 12 custom display ligatures, class-based kerning, and 9 compiled OpenType feature tables.

---

## Complete Glyph Coverage

* **Basic & Extended Latin (`A–Z`, `a–z` + Diacritics):** Full support for Western, Central, and Eastern European languages, including accented forms of `A`, `C`, `D`, `E`, `G`, `H`, `I`, `J`, `K`, `L`, `N`, `O`, `R`, `S`, `T`, `U`, `W`, `Y`, and `Z`, alongside `Æ`, `æ`, `Ø`, `ø`, `Œ`, `œ`, `IJ`, `ij`, `Ð`, `ð`, `Þ`, `þ`, `ß` / `ẞ` equivalents, and dotless `ı` / `ȷ`.
* **Numerals, Fractions & Superiors:**
  * Default proportional lining figures (`0–9`)
  * Monospaced tabular figures (`zero.tf`–`nine.tf`) for aligned data, magazine folios, and pricing columns
  * Pre-built vulgar fractions (`¼`, `½`, `¾`) and superior numerals (`¹`, `²`, `³`)
* **Currency & Mathematical Symbols:** Indian Rupee (`₹`), Dollar (`$`), Euro (`€`), Cent (`¢`), Sterling (`£`), Yen (`¥`), Florin (`ƒ`), generic currency (`¤`), plus standard math operators (`+`, `−`, `×`, `÷`, `=`, `≠`, `≤`, `≥`, `±`, `¬`, `µ`, `°`, `‰`).
* **Editorial Punctuation & Marks:** Guillemets (`«`, `»`, `‹`, `›`), curly quotes, en-dash (`–`), em-dash (`—`), ellipsis (`…`), bullet (`•`), dagger (`†`), double dagger (`‡`), directional arrows (`←`, `→`), trademark (`™`), registered (`®`), and copyright (`©`).
* **Spacing & Kerning Engineering:** Sidebearing formulas anchored to the structural proportions of `H`, paired with class-based kerning (`kern`) calibrated for high-contrast display typography.

---

## Custom Ligatures (`liga`)

Higer includes 12 custom-drawn ligatures designed to eliminate stroke collisions and preserve crisp horizontal rhythm in display headlines:

| Ligature | Glyph Name | Description |
| :--- | :--- | :--- |
| **fi, fl, ff, ffi, ffl, fj** | `f_i`, `f_l`, `f_f`, `f_f_i`, `f_f_l`, `f_j` | Classic f-ligatures resolving terminal overlap with ascending and dotted characters |
| **ta, tg, ts** | `t_a`, `t_g`, `t_s` | Custom crossbar-connected ligatures crafted for tight editorial wordmarks |
| **ax, as** | `a_x`, `a_s` | Stylistic lowercase joins |
| **ij** | `ij` | Dutch digraph ligature |

---

## OpenType Layout Features

All 9 OpenType feature tables compiled in Higer:

| Tag | Feature Name | Function in Higer |
| :--- | :--- | :--- |
| **`kern`** | Kerning | Class-based horizontal pair adjustments for balanced headline spacing |
| **`liga`** | Standard Ligatures | Automatic substitution for all 12 custom ligatures |
| **`tnum`** | Tabular Figures | Replaces proportional numerals with uniform-width figures (`zero.tf`–`nine.tf`) |
| **`frac`** | Fractions | Formats slash-separated numbers into diagonal fractions |
| **`sups`** | Superscripts | Substitutes standard figures with properly scaled superior numerals |
| **`ordn`** | Ordinals | Automatically formats ordinal indicators (such as `1st`, `2nd`, `Nº`) |
| **`mark`** | Mark Positioning | Anchor-based attachment for accurate diacritic placement |
| **`locl`** | Localized Forms | Language-specific glyph substitutions (including Czech/Slovak `lcaron.loclCSZ` and `tcaron.loclCSZ`, plus comma-accent forms) |
| **`aalt`** | Access All Alternates | Exposes all alternate glyphs and ligatures in the Glyphs panel of design software |
