# UI Elements — Theory Reference

A static page explaining ten common interface elements — radio button, checkbox,
text input, tabs, button, text label, link, tooltip, dropdown list, and data grid.
Plain HTML and CSS only, no JavaScript and no frameworks.

This version is theory only: no page navigation and no live/interactive examples.
Each element is documented with a definition, when to use it, when to avoid it,
and a static markup sample.

## Files

```
ui-theory/
  index.html    markup and content
  styles.css    styles (light blue theme)
```

## Structure of each entry

Every one of the ten elements follows the same layout:

1. **Definition** — one sentence stating what the element is.
2. **Explanation** — a few paragraphs on why it exists and what makes it work.
3. **Use when / Avoid when** — a two-column comparison of good and bad fits.
4. **Markup** — a static, non-interactive HTML code sample.
5. **Note** — a short aside tagged Accessibility, Security, Convention, etc.

The page closes with a summary table (element, the question it answers, its
typical mistake) and a short comparison of three commonly confused pairs
(radio vs. dropdown, radio vs. checkbox, button vs. link).


## Notes

- Self-contained aside from one Google Fonts stylesheet linked in `<head>`
  (IBM Plex Sans, Serif, and Mono).
- No JavaScript, no form controls, no internal navigation — pure reference text.
- Checked for balanced tags, valid CSS, and no duplicate IDs.
