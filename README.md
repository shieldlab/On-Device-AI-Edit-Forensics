# Edits in the Wild — Project Page

Project page for **"Edits in the Wild: A Multilingual Benchmark for Localizing On-Device Generative Image Edits on Consumer Platforms"** (EMNLP 2026 Main Conference).

A static site with no build step: `index.html`, plus images in `static/img/` and the poster in `static/pdf/`.

## Deploy on GitHub Pages

1. Create a new public repository on GitHub, for example `edits-in-the-wild`.
2. Upload everything in this folder to the repository root, including the hidden `.nojekyll` file:
   ```bash
   git init
   git add .
   git commit -m "Project page"
   git branch -M main
   git remote add origin https://github.com/<your-username>/edits-in-the-wild.git
   git push -u origin main
   ```
3. On GitHub, open **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, then **main** and **/ (root)**, and click **Save**.
4. After a minute or two the page is live at `https://<your-username>.github.io/edits-in-the-wild/`.

## Before the camera-ready release

In `index.html`, find the buttons with `href="#"` and the `(soon)` label. Point each one at its real link and delete the label:

| Button  | What to link |
|---------|--------------|
| Paper   | ACL Anthology / PDF |
| arXiv   | arXiv abstract page |
| Code    | GitHub code repository |
| Dataset | Dataset hosting (e.g. Hugging Face) |
| Talk    | Recorded video |

When the page has its final URL, point the poster's QR code at it too.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
