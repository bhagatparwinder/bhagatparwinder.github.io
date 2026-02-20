Source for a minimal personal site: a single-page static site built with HTML and CSS. The page includes a short intro, contact details, and instructions for running the site locally.

## Running locally

From the project root, start a local server so you can open the site in your browser (e.g. `http://localhost:8000`).

**Option 1 — Python (no install if you have Python):**
```bash
# Python 3
python3 -m http.server 8000

# or Python 2
python -m SimpleHTTPServer 8000
```

**Option 2 — Node (if you have Node/npm):**
```bash
npx serve
# or: npx http-server -p 8000
```

**Option 3 — PHP:**
```bash
php -S localhost:8000
```

Then open **http://localhost:8000** (or the port shown) in your browser.
