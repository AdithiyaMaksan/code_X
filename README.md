# NFT / Static Website Template

A static HTML template for NFT/portfolio/marketing sites containing multiple prebuilt pages, assets, and JavaScript for interactions. This repository is a ready-made front-end site you can preview locally, customize, and deploy to GitHub Pages or any static hosting service.

---

## Project Overview

- **Purpose:** Static website template focused on NFT and creative portfolios with ready-made pages, styles, and client-side scripts.
- **Stack:** Plain HTML, CSS, and JavaScript (no build step required).
- **Status:** Complete static files present in the repository; ready for customization and deployment.

---

## Features

- Multiple page templates: home pages, about, blog, portfolio, product pages, contact pages, sign-in/up flows (static mockups).
- Organized asset folders: `assets/` and `assets2/` containing CSS, fonts, images, and JS vendor libraries.
- Lightweight client-side interactions using `main.js`, `owl.carousel`, `fancybox`, and other vendor scripts.
- Mobile menu support and responsive CSS built with vendor styles and custom CSS.

---

## Repository Structure (high-level)

- `index.html`, `about.html`, `contact.html`, and many specialized HTML pages (NFT-specific variants are marked with `(nft)` in filename).
- `assets/` — CSS, fonts, `img/`, and JS files that power the theme.
- `assets2/` — an alternate asset set (styles, fonts, images and JS vendor folders).
- `js/` — custom scripts (`main.js`, `ajax-form.js`, etc.).

Example:

```
d:\project 1\
├─ index.html
├─ about.html
├─ contact.html
├─ assets\
│  ├─ css\
│  ├─ fonts\
│  ├─ img\
│  └─ js\
└─ assets2\
   ├─ css\
   └─ js\
```

---

## How to Preview Locally

No build tools are required. The simplest option is to open `index.html` in your browser. For a correct local environment (so AJAX and some features work), serve the folder through a static HTTP server.

Using Python 3 (recommended):

```powershell
Set-Location -Path "D:\project 1"
py -3 -m http.server 8000
# Then open http://localhost:8000 in your browser
```

Or using PowerShell's built-in `Start-Process` to open the file directly:

```powershell
Start-Process "D:\project 1\index.html"
```

---

## How to Deploy to GitHub Pages

1. Initialize a git repo (if not already):

```powershell
Set-Location -Path "D:\project 1"
git init
git add .
git commit -m "Initial commit: static site"
```

2. Create a GitHub repository and add it as `origin` (replace `USERNAME` and `REPO`):

```powershell
git remote add origin https://github.com/USERNAME/REPO.git
git branch -M main
git push -u origin main
```

3. In the GitHub repository settings, enable **Pages** and select the `main` branch and `/ (root)` as the publish source. The site will be available at `https://USERNAME.github.io/REPO`.

---

## Customization Guide

- Edit HTML files directly for content and structure.
- Modify CSS in `assets/css/style.css` or `assets2/css/style.css` to change the look.
- Replace images in `assets/img/` or `assets2/images/` to update visuals.
- Vendor JS libraries live in `assets/js/vendor/` — update only if needed.

Best practice: create a feature branch (git) for larger changes and test locally before merging.

---

## Common Commands

- Serve locally (Python):

```powershell
py -3 -m http.server 8000
```

- Initialize & push to GitHub:

```powershell
git init
git add .
git commit -m "Initial commit"
git remote add origin <repo-url>
git branch -M main
git push -u origin main
```

---

## Notes & Troubleshooting

- If images or CSS are missing, ensure relative paths are correct and that files exist under `assets/` or `assets2/`.
- If browser caching shows old styles, clear cache or use hard-refresh (Ctrl+F5).
- For contact or AJAX demo features, server-based handling is not included — those are front-end demos; replace with real server endpoints when implementing.

---

## Credits

- Template and assets (various open-source vendors) are included in `assets/js/vendor` and `assets2/js/vendor`.

---

