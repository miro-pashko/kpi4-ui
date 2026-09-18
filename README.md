# UI Elements Reference

Two static pages explaining ten common interface elements — radio button, checkbox,
text input, tabs, button, text label, link, tooltip, dropdown list, and data grid.
No frameworks. Plain HTML and CSS, with a small amount of vanilla JavaScript in one
of the two versions.

## Versions

| | Path | Theme | Content |
|---|---|---|---|
| **Interactive specimen sheet** | `index.html` | Light green | Explanation of each element **plus** a working live example (real radios, a sortable/filterable data grid, working tabs, etc.), a top index linking to every section, and a closing comparison of commonly confused pairs. |
| **Theory reference** | `ui-theory/index.html` | Light blue | Explanation only — no navigation index, no live controls. Each element gets a definition, a "use when / avoid when" comparison, a static markup sample, and a short accessibility or convention note. Ends with a summary table and the same closing comparison. |

Pick whichever fits: the green version is a demo page you can click through, the blue
version is a plain-text manual you could print or hand someone as documentation.

## Files

```
index.html          interactive version — markup
styles.css           interactive version — styles
script.js            interactive version — behaviour (tabs, counters, grid sort/filter)

ui-theory/
  index.html          theory version — markup
  styles.css          theory version — styles (no JS file; this version has none)
```

## Running it

No build step and no server required. Open either `index.html` file directly in a
browser, or serve the folder locally, e.g.:

```bash
python3 -m http.server
```

then visit `http://localhost:8000/` for the interactive version or
`http://localhost:8000/ui-theory/` for the theory version.

## Notes

- Both versions are self-contained aside from one Google Fonts stylesheet linked in
  each `<head>`; everything else is local.
- The interactive version's `script.js` only adds convenience (sorting, live counters,
  save-button feedback) — every control in it also works with JavaScript disabled.
- Built and manually checked for balanced tags, valid CSS, and no duplicate IDs.
