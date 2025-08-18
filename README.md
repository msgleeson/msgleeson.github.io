# msgleeson.github.io

# Teaching Portfolio Site (COMP208 Demo)

A simple, standards-based portfolio as an example for pre-service teachers completing COMP208.
Built with **semantic HTML**, **external CSS** (`starter.css`), and a little **JavaScript** to demonstrate good front-end practice. Deployed with **GitHub Pages**.

- **Pages:** Home, About, Teaching, Samples of Work (card layout), Projects/Showcase (card layout), Resources, Resume, Contact (styled form)
- **Goals:** Clean structure, accessible typography/colour, and beginner-friendly CSS patterns (box model, flexbox, cards, nav)
- **Live:** https://msgleeson.github.io/

## Tech
- HTML5 + CSS3 (external stylesheet)
- Vanilla JavaScript (light enhancement)
- GitHub Pages for hosting

## Colour & Contrast (Adobe Color Contrast Checker)

| Context / Element                  | Foreground | Background | Contrast Ratio | WCAG Notes* |
|-----------------------------------|-----------:|-----------:|---------------:|-------------|
| Body text                         | `#222222`  | `#FFFFFF`  | **15.91:1**    | AAA (normal + large) |
| Navigation links / text           | `#FFFFFF`  | `#333333`  | **12.63:1**    | AAA (normal + large) |
| Card text on card background      | `#333333`  | `#D8DFF7`  | **9.52:1**     | AAA (normal + large) |
| Primary button text on button     | `#FFFFFF`  | `#1F6FEB`  | **4.63:1**     | AA (normal), AAA (large ≥18.66px/14px bold) |
| Muted text / secondary meta text  | `#666666`  | `#FFFFFF`  | **5.74:1**     | AA (normal), AAA (large) |

\* **WCAG quick guide:**  
- **AA normal text:** ≥ 4.5:1  
- **AA large text (≥ 18pt / 24px, or 14pt / 18.66px bold):** ≥ 3:1  
- **AAA normal text:** ≥ 7:1

> **Notes**
> - Ratios were verified with **Adobe Color Contrast Checker** against the hex pairs above.  
> - If you change colours in `starter.css`, re-check them to keep accessibility guarantees.

## Editing / Contributing
1. Edit HTML sections using semantic tags (`<main>`, `<section>`, `<nav>`, `<footer>`).
2. Put all styling in `starter.css` (avoid inline styles).
3. Commit to `main` and confirm the site updates at `https://username.github.io/`.

_Last updated: 18 Aug 2025 (AEST)._
