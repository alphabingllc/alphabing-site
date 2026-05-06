# Alphabing Static Website

This is a clean GitHub Pages-ready rebuild of the downloaded Alphabing Google Sites export. It uses plain HTML, CSS, and JavaScript only.

## Project Structure

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
├── privacy/
│   └── index.html
├── TesseraCubePrivacy/
│   └── index.html
├── facepicto-privacy/
│   └── index.html
├── digipinfind-privacy/
│   └── index.html
├── assets/
│   ├── logo.png
│   ├── app-malayalam.png
│   ├── app-english.png
│   ├── app-spanish.png
│   ├── app-punjabi.png
│   ├── app-tamil.png
│   ├── app-hindi.png
│   ├── app-facepicto.png
│   ├── app-digipin-find.jpg
│   ├── learning-preview.png
│   ├── tesseracube.png
│   ├── eyebrain-pro.png
│   ├── icon-instagram.png
│   ├── icon-facebook.png
│   ├── icon-email.png
│   └── icon-x.png
└── alphabing-website/
    ├── Alphabing.html
    └── Alphabing_files/
```

## Run Locally

Option 1: open `index.html` directly in your browser.

Option 2: run a local server from this folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

The privacy pages use folder-based routing and are available locally at:

```text
http://localhost:8000/privacy/
http://localhost:8000/TesseraCubePrivacy/
http://localhost:8000/facepicto-privacy/
http://localhost:8000/digipinfind-privacy/
```

## Deploy To GitHub Pages

1. Create a GitHub repository.
2. Push these files to the repository.
3. In GitHub, go to `Settings` -> `Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Set `Branch` to `main`.
6. Set `Folder` to `/root`.
7. Save the settings and wait for GitHub Pages to publish the site.

## Notes

The original downloaded Google Sites export remains in `alphabing-website/`. The clean static website lives at the project root.

The original export referenced a Spanish app icon file that was not included in `Alphabing_files/`, so `assets/app-spanish.png` is a simple local replacement that can be swapped later.
