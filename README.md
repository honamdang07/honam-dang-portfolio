# Honam Dang Portfolio

## Run locally

Open `index.html` directly in a browser, or run `python3 -m http.server 8000` inside this folder and visit `http://localhost:8000`.

## Edit the site

- Content lives in `index.html`. Search for `[Add` to find project and biography placeholders.
- Replace images in `assets/` while preserving their filenames, or update the matching `src` / `data-full` paths in `index.html`.
- Colors and responsive styling are in `styles.css` under `:root`.

## Publish

### GitHub Pages

Create a GitHub repository, upload this folder's contents, then open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save. GitHub will give you a public URL.

### Vercel

Push this folder to GitHub, import that repository into Vercel, select **Other** as the framework preset, and deploy. No build command is required for this static site.
