# portfolio

Personal site — [jovanspinjo.github.io/portfolio](https://kaizennnnnnnnn.github.io/portfolio/)

One `index.html`. No build step, no framework, no dependencies. Three typefaces from
Google Fonts, one canvas, and a colour grade that cools as the page descends.

## Structure

The page is one document printed in two grades. Sections 00–02 sit in the **construct**
— lifted warm green-black, tungsten amber as the only saturated colour — and hold the
two products built by directing coding agents. Section 03 is the **seam**, where the
grade ramps and the ambient motion starts. Section 04 is the **real** — crushed
blue-steel — and holds everything written by hand. Section 05 flips to the one light
surface on the site.

The authorship disclosure is not a footnote; it is section 01, formatted as data.

## Running it

Open `index.html`. That is the whole story — there is nothing to install and nothing
to compile. For the relative links to behave exactly as they do in production, serve
the folder instead of opening the file directly:

```
python -m http.server 8000
```

## Still to add

- `cv.pdf` at the repo root — the rail and section 05 both link to it.
- Screenshots for the three plates: `eren.png`, `outrank.png`, `murmur.png`.
  Until they exist each plate renders a labelled placeholder rather than a broken image.
