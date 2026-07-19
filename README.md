# Merge PDFs

A single-file, browser-based PDF merger. No installs, no server, no build step — files never leave your device.

**Try it:** enable GitHub Pages on this repo (see below) and open the published URL.

## How it works

Everything lives in `index.html`. It loads [pdf-lib](https://pdf-lib.js.org) from a CDN and merges your PDFs entirely in the browser using JavaScript. Nothing is uploaded anywhere.

Features:

- Drag & drop or browse to add PDFs
- Reorder files by dragging, or with the ↑ / ↓ buttons
- Shows page counts and file sizes
- One click to merge and download `merged.pdf`

## Host it on GitHub Pages

1. Create a new repo and add `index.html` (and this README) to it.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute, your app is live at `https://<your-username>.github.io/<repo-name>/`.
5. For me: [https://nmaccabe.github.io/pdf-merge/](https://nmaccabe.github.io/pdf-merge/)

## Run it locally

Just open `index.html` in any browser. That's it.
