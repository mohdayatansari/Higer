# Design Concept, Anatomy & Roadmap

**Higer** is a modern, high-contrast editorial serif typeface built for display headlines, luxury brand identities, and contemporary magazine layouts.

---

## Design Concept & Anatomy

### Etymology & Conceptual Foundation
The name **Higer** brings together two complementary ideas:
* **Phonetic Elevation:** Echoing *"Higher,"* the name reflects vertical momentum, tall proportions, and editorial prestige.
* **Structural Permanence:** Rooted in the Old High German term *Häger* (meaning an enclosure, boundary, or guarded clearing), it signifies architectural discipline and deliberate form.

Visually, the typeface translates the stark geometry of high-altitude alpine terrain into letterforms: towering vertical stems, razor-sharp serifs, and dramatic light-to-shadow contrast reminiscent of sunlit snow ridges beside sheer glacial faces.

### Typographic Anatomy & Construction
Every glyph in Higer was drafted as vector paths in Adobe Illustrator and engineered in FontLab 8 with unified structural rules:

* **High Optical Contrast & Vertical Stress:** Thick primary stems transition sharply into delicate hairline crossbars and curves along a clean `0°` vertical stress axis, giving large display headlines crisp editorial authority[cite: 24, 26].
* **Chiseled Serifs & Ink Traps:** Sharp, lightly bracketed serifs anchor each stem firmly to the baseline and cap line, supported by subtle `2.0` unit ink traps to preserve corner sharpness at high contrast[cite: 24, 26].
* **Double-Storey Lowercase Architecture:** Classic double-storey `a` and `g` structures provide traditional editorial legibility and balanced counter spaces within tall, condensed-leaning proportions[cite: 22].
* **Sculpted Terminals:** Lowercase `f`, `j`, `r`, and `y` feature refined curved terminals that soften the angularity of the serifs without losing tension[cite: 22].
* **Integrated Ligature Joins:** Custom ligatures (`f_i`, `f_l`, `f_f`, `f_f_i`, `f_f_l`, `f_j`, `t_a`, `t_g`, `t_s`, `a_x`, `a_s`, `ij`) merge adjacent crossbars and terminals into single continuous strokes rather than letting glyphs collide[cite: 22].
* **Proportional Spacing System:** Sidebearings are governed by proportional formulas anchored to `H`, paired with class-based kerning pairs (`kern`) calibrated for tight editorial tracking[cite: 11].

### Font Master Dimensions & Vertical Metrics
Engineered on a standard **1000 Units Per Em (UPM)** grid[cite: 24, 25]:

| Metric | Value (Units) | Notes |
| :--- | :--- | :--- |
| **Units Per Em (UPM)** | `1000`[cite: 24, 25] | Standard PostScript/OpenType coordinate grid |
| **Ascender** | `980`[cite: 24, 25] | Tall vertical ascender clearance (`Safe top: 988`)[cite: 25] |
| **Caps Height** | `872`[cite: 24, 26] | High uppercase proportion relative to UPM |
| **x-Height** | `610`[cite: 24, 26] | Generous lowercase torso height (~70% of Caps Height) for editorial readability |
| **Descender** | `-300`[cite: 24, 25] | Deep descender reach (`Safe bottom: -270`)[cite: 25] |
| **Line Gap** | `0`[cite: 24, 25] | Tight default leading suited for multi-line display headlines |
| **Italic Angle** | `0°`[cite: 24, 26] | Upright editorial roman posture |
| **Curve / Corner Tension** | `60%` / `67%`[cite: 24, 26] | Smooth, controlled Bézier curvature across bowls and terminals |
| **Ink Trap Width** | `2.0`[cite: 24, 26] | Micro-notches at tight acute joins to keep sharp edges crisp |

---

## Current Status & Roadmap

### Current Release: v1.0 (Shipped)
* **Style:** `Higer` (Single upright Regular weight)[cite: 24]
* **Formats Available:** OpenType CFF (`.otf`), TrueType (`.ttf`), and Web Open Font Format 2 (`.woff2`)[cite: 15]
* **Character Coverage:** Basic & Extended European Latin (`A–Z`, `a–z`, full diacritics), lining and tabular numerals (`0–9`, `zero.tf`–`nine.tf`), currency symbols (including `₹`, `$`, `€`, `£`, `¥`, `ƒ`), vulgar fractions (`¼`, `½`, `¾`), and editorial punctuation[cite: 22]
* **OpenType Engineering:** 12 custom ligatures (`liga`), class-based kerning (`kern`), localized forms (`locl`), mark positioning (`mark`), fractions (`frac`), superscripts (`sups`), ordinals (`ordn`), and tabular figures (`tnum`)[cite: 11, 22]

### Planned Roadmap
* **Companion Italic:** True editorial italic master engineered with matching high-contrast proportions.
* **Weight Expansion:** Extending Higer into a multi-weight editorial family (`Light`, `Medium`, `SemiBold`, and `Bold`).
* **Variable Font Support:** Single-axis (`wght`) variable font export for responsive web typography.
* **Additional Stylistic Alternates (`ss01`–`ss02`):** Swash capitals and expressive display alternates for magazine mastheads.
