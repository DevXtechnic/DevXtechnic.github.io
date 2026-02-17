# Bikram Personal Website

Playful dark-themed personal website for **Bikram Gole**.

## Stack

- HTML
- CSS
- JavaScript
- GitHub API (to show latest repos)

## Pages

- `index.html` - Home + live GitHub repos
- `about.html` - Personal story and profile
- `contact.html` - Email and GitHub links

## Run locally

Open `index.html` directly, or run a local server:

```bash
cd bikram-site
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a GitHub repo (recommended name: `DevXtechnic.github.io` for user site).
2. Upload all files from this folder to the repo root.
3. On GitHub, go to `Settings -> Pages`.
4. Under `Build and deployment`, set:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` and `/ (root)`
5. Save and wait 1-2 minutes.
6. Visit your site URL shown in Pages settings.

If repo name is `DevXtechnic.github.io`, URL will be:
`https://devxtechnic.github.io/`

If repo name is something else (example `bikram-site`), URL will be:
`https://devxtechnic.github.io/bikram-site/`
