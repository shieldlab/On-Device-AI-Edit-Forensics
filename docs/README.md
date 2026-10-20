# Project page: Edits in the Wild (EMNLP 2026)

Static project page for the paper. No build step: `index.html` plus images in `static/img/` and the poster in `static/pdf/`.

This folder is served by GitHub Pages from `docs/` on the `main` branch:
https://shieldlab.github.io/On-Device-AI-Edit-Forensics/

## Pages

`index.html` is the project page and `dataset.html` is the dataset download page. In `dataset.html`, search for `DEMO DOWNLOAD` to point the demo button at the zip.

## Updating links

In `index.html`, search for `PAPER LINK` and `VIDEO LINK`. Replace the `href="#"` on the line below each with the real URL; for the Video button also remove `class="soon"`, `aria-disabled` and the `<em>soon</em>` tag.

## Local preview

```bash
cd docs && python3 -m http.server 8000   # open http://localhost:8000
```
