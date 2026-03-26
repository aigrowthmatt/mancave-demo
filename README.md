# Mancave (demo)

Static HTML prototype. Open **[mancave2.html](mancave2.html)** for the latest build, or the site root (redirects there).

## GitHub Pages

After the first push:

1. On GitHub: **Settings** → **Pages** (left sidebar).
2. Under **Build and deployment** → **Source**, choose **Deploy from a branch**.
3. **Branch**: `main`, folder **`/ (root)`** → **Save**.
4. In a minute or two the demo will be at:

   **`https://<your-username>.github.io/<repo-name>/`**

   (Root URL loads `index.html`, which sends you to `mancave2.html`.)

## Local preview

Open `mancave2.html` in a browser, or run a quick server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/mancave2.html`.
