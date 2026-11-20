# Ymir site

- `index.html` — the page. All content, styles and effects live here. Edit text, colors and layout directly.
- `evidence.html` — detailed results. Add figures by searching for `[ Figure` and replacing the placeholder with an `<img>` (put images in a `figures/` folder).
- `support.js` — page runtime. Don't edit; keep it next to `index.html`.
- Videos stream from https://guangyuwanglab2021.github.io/ymir-showcase/ — no local video files needed.

## Changing videos
In `index.html`, search for `VIDEO 1` … `VIDEO 4` and edit each `<video>` tag's `src` (video) and `poster` (cover image). Case 01 has two videos switched by tabs.

## Viewing locally
Open via a local server (not by double-clicking), e.g. in this folder run:
`python3 -m http.server` → open http://localhost:8000
