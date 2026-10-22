# image-compress-pdf

A pure front-end, locally-run tool to **batch compress images, pack them into a ZIP, and build a PDF** — all in a single `index.html`. No installation, no server required; just open it in a browser.

Chinese UI:

![Screenshot](docs/screenshot.png)

English UI:

![English UI](docs/screenshot-en.png)

## Features
- **Batch compression**: import JPG / PNG, adjust quality (0.1–0.95), re-compresses automatically on release.
- **ZIP packaging**: download all compressed images as one ZIP.
- **PDF building**: one-click merge with multiple layouts:
  - Fit centered (portrait A4, no distortion)
  - Smart auto orientation (landscape images use landscape A4)
  - Cover crop (no margin, may crop edges)
  - Original aspect ratio page (exact reproduction)
  - Multi-image grid (2×2)
- **Sorting**: drag cards manually / by name / by modified time — order affects both ZIP and PDF.
- **Bilingual UI**: switch between Chinese and English from the top-right corner.

## Usage
Open `index.html` in any modern browser. All processing happens locally; nothing is uploaded.

## Privacy
All image processing runs entirely in your browser. No images are ever uploaded to any server.

## Author
by [mp2012](https://github.com/mp2012) · Source
