# Shih-Ping Lin Personal Website

This is a bilingual static personal website built from the Chinese and English resumes.

## Files

- `index.html` - page structure and content hooks
- `styles.css` - responsive visual design
- `script.js` - Chinese and English language switching
- `assets/` - visual asset and downloadable resumes

## Preview Locally

Run a static server in this folder:

```bash
python3 -m http.server 5173
```

Then open:

```text
http://localhost:5173
```

## Deploy To GitHub Pages

1. Create a new GitHub repository, for example `personal-website`.
2. Upload all files in this folder to the repository root.
3. Commit and push to the `main` branch.
4. In GitHub, open `Settings` -> `Pages`.
5. Set `Build and deployment` to `Deploy from a branch`.
6. Select branch `main` and folder `/root`, then save.
7. Your site will be published at `https://<your-github-username>.github.io/personal-website/`.

For a user site URL like `https://ShihPingLin.github.io/`, name the repository `ShihPingLin.github.io` and deploy from the repository root.
