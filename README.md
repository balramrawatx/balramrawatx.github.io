# Balram Rawat — Portfolio Website

A responsive dark-theme portfolio built with plain HTML, CSS, and JavaScript for GitHub Pages.

## Files

- `index.html` — website content
- `style.css` — design and responsive layout
- `script.js` — mobile menu and small interactions
- `assets/` — place your CV PDF and optional images here

## Before publishing

1. In `index.html`, replace `YOUR_EMAIL@example.com` with your public contact email.
2. Replace the LinkedIn placeholder `href="#"` with your profile URL, or remove that link.
3. Replace the sample previous-education card with your real degree details.
4. Update the project cards with real project descriptions and repository links.
5. Only list skills you can confidently discuss.

## Publish with GitHub Pages

1. Sign in to GitHub as `balramrawatx`.
2. Create a new **public** repository named exactly `balramrawatx.github.io`.
3. Upload the contents of this folder to the repository root. Upload the files and `assets` folder themselves, not the enclosing ZIP or parent folder.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then click **Save**.
7. Wait a few minutes, then visit https://balramrawatx.github.io/

If the repository already exists, check it before creating another one. Do not overwrite files you want to keep.

## Add your CV

Put your PDF in `assets/cv.pdf`. To add a download button, insert this link wherever you want it in `index.html`:

```html
<a class="button button-secondary" href="assets/cv.pdf" target="_blank" rel="noreferrer">
  View my CV ↗
</a>
```

## Updating the site

Edit a file in GitHub and commit the changes. GitHub Pages will rebuild the website automatically.
