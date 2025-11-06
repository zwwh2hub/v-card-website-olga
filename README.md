Digital Business Card
========================

This repository contains a website a digital business card. All content is plain markup so anyone can edit text, images, or links without a build step.

Project layout
--------------

```
index.html
.nojekyll
assets/
  css/
    styles.css
  img/
    portrait.jpg
```

- index.html - markup and the small script that powers theme, language, and share behaviour.
- assets/css/styles.css - typography, layout, and colour tokens for the card.
- assets/img/portrait.jpg - sample portrait image (replace with your own asset).
- .nojekyll - tells GitHub Pages to serve files exactly as provided.

Customising
-----------

1. Update copy, links, or translations directly in index.html.
2. Swap images by dropping new files into assets/img/ and updating the `<img>` tag.
3. Adjust colours or spacing in assets/css/styles.css. The design uses CSS variables to keep theming simple.

Deploying to GitHub Pages
-------------------------

1. Push the project to a GitHub repository.
2. Open Settings -> Pages.
3. Select "Deploy from a branch", choose the branch (for example main) and the root folder (/), then save.

After the first deploy, GitHub Pages will publish the site at `https://<username>.github.io/<repo>/`. Fork or branch the project to add extra sections while keeping the static hosting workflow.
