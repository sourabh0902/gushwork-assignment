# Gushwork Assignment

Product landing page for Meera Industries Limited, showcasing HDPE pipes and piping solutions. Built with vanilla HTML, CSS, and JavaScript — no build tools or dependencies required.

---

## Project Structure

```
Gushwork/
├── index.html      # Main page markup
├── styles.css      # All styling and responsive design
├── script.js       # Interactivity (modals, carousels, zoom, scroll effects)
└── assets/         # Images, SVGs, and icons
```

---

## Running the App

This is a static site with no build step.

### Option 1 — Open directly in a browser

Double-click `index.html`, or drag it into any browser window.

> Note: Some browser security restrictions may affect local file behavior (e.g., font loading). Use a local server if anything looks off.

### Option 2 — Local server (recommended)

Pick any of the following depending on what's installed on your machine:

**Python 3**
```bash
python -m http.server 8000
```

**Node.js**
```bash
npx http-server
```

**PHP**
```bash
php -S localhost:8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

---

## Making Changes

| What you want to change | File to edit |
|---|---|
| Page content / structure | `index.html` |
| Styles, layout, colors | `styles.css` |
| Interactive behavior | `script.js` |
| Images or icons | `assets/` |

No compilation or restart needed — just save the file and refresh the browser.

---

## Deployment

Copy all files to any static web host or CDN:

```
index.html
styles.css
script.js
assets/
```

No server-side runtime or build pipeline required.
