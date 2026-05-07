# growingrootsproject.github.io

Static site for the **Growing Roots Project** (HTML, CSS, and JavaScript), intended for **GitHub Pages**.

## Local preview

Open `index.html` in a browser, or from this directory run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Enable GitHub Pages

1. Push this repository to GitHub.
2. In the repo on GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose your default branch (usually `main`) and folder **`/` (root)**.
5. Save. After a minute or two, the site should be available at `https://growingrootsproject.github.io/` (replace with your org/username if different).

## Custom domain (optional)

Add your domain in **Settings → Pages** under **Custom domain**, configure DNS per GitHub’s documentation, and add a `CNAME` file at the repository root containing the hostname.

## Files

- `images/growing-tree.png` — footer background illustration (copied from `growing tree.png`)

Single-page anchors: `#about`, `#mission`, `#programs`, `#farm-roots`, `#impact`, `#get-involved`, `#contact`, `#donate`.

- `index.html` — main page
- `css/styles.css` — styles
- `js/main.js` — navigation toggle and footer year
- `.nojekyll` — disables Jekyll processing on GitHub Pages
- `404.html` — simple not-found page

Replace placeholder contact email, EIN/Tax ID, and the donate button when ready.
