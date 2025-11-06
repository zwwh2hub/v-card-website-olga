# Digital Business Card

Responsive single-page profile card for Dr. Olga Zeichel, built with plain HTML/CSS/JS.

## Project structure

```
.
├── assets
│   ├── css
│   │   └── styles.css
│   └── img
│       └── Olga_Zechiel.jpg
├── index.html
└── .nojekyll
```

- `index.html` – main page served by GitHub Pages.
- `assets/css/styles.css` – styling for the page.
- `assets/img/Olga_Zechiel.jpg` – profile portrait.
- `.nojekyll` – disables the default Jekyll pipeline so all assets load as-is.

## Hosting on GitHub Pages

1. Push this project to a GitHub repository (e.g. `username/username.github.io` or any repo).
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing this project (commonly `main`) and the root folder (`/`).
5. Save. GitHub Pages will publish the site to `https://<username>.github.io/` (or `/<repo>` for project sites) once the build finishes.

If you add or rename assets, ensure the paths in `index.html` stay relative so they resolve on GitHub Pages.
