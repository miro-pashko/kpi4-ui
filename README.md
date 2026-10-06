# UI Elements — Theory Reference with Live Examples

A static page explaining ten common interface elements — radio button, checkbox,
text input, tabs, button, text label, link, tooltip, dropdown list, and data grid.
Plain HTML, CSS, and vanilla JavaScript; no frameworks, no build step.

All page content is in Ukrainian (`<html lang="uk">`).

This version pairs the theory with a working, interactive example for each
element. Usage/misuse guidance ("Use when / Avoid when") and static markup
samples have been removed.

## Files

```
ui-theory/
  index.html    content, live examples, and the inline script
  styles.css    styles (light blue theme)
```

Open `index.html` directly in a browser — no server is required. Keep both files
in the same folder.

## Structure of each entry

Every one of the ten elements follows the same layout:

1. **Definition** — one sentence stating what the element is.
2. **Explanation** — two paragraphs on why it exists and what makes it work.
3. **Live example** — a framed demo the reader can click, type into, or switch,
   with a status line that reports the current state where relevant.

The page closes with a summary table (element and the question it answers);
each element name links to its section.

## Live examples

| #  | Element          | What the demo does |
|----|------------------|--------------------|
| 01 | Radio button     | Delivery options; the chosen option and its price are shown below. |
| 02 | Checkbox         | A parent checkbox over three channels, showing the indeterminate state when only some are ticked. |
| 03 | Text input       | Email field with live format check, a narrow postcode field, and a comment box with a character counter. |
| 04 | Tabs             | Three tabs; arrow keys, Home and End switch them, and text typed in one tab survives switching away and back. |
| 05 | Button           | Primary, plain, and danger buttons; save shows a brief loading state, delete asks for confirmation. |
| 06 | Text label       | Password field with label, helper text, and live status text; a clickable "Show password" label; a toggle that highlights the three kinds of text. |
| 07 | Link             | In-page, external (new tab), and email links; the target address appears on hover or focus. |
| 08 | Tooltip          | Icon-only toolbar and an abbreviation; tooltips appear on hover, keyboard focus, and tap, and Esc hides them. |
| 09 | Dropdown list    | A grouped category list and an alphabetical city list; the current selection is reported. |
| 10 | Data grid        | Sortable columns, a text filter, row selection with "select all", a bulk action, and a sticky header; a status line reports rows shown, rows selected, and the sort order. |

No data is sent anywhere; every action is simulated in the page.

## Notes

- Self-contained aside from one Google Fonts stylesheet linked in `<head>`
  (IBM Plex Sans, Serif, and Mono, all with Cyrillic support).
- JavaScript is a single inline `<script>` at the end of `index.html`.
- Uses native form controls and ARIA roles and states (`tablist`, `tooltip`,
  `aria-sort`, `aria-live`, etc.) so the demos work with keyboard and screen readers.
- Respects `prefers-reduced-motion`; includes a print stylesheet.
- Checked for script syntax errors, duplicate IDs, and broken ID references and
  in-page anchors.
