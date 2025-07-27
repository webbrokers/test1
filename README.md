# Simple Demo Site

This repository contains a small two-page demo website inspired by [MillionPesos.com](https://millionpesos.com/). The site includes:

- `index.html` – a home page that links to the About page
- `about.html` – a short description of the project
- `styles.css` – basic styling used by both pages

## Publishing with GitHub Pages

To publish this site on GitHub Pages:

1. Create a new repository on GitHub and push this code to the `main` branch.
2. In your repository settings, enable **GitHub Pages** and choose `GitHub Actions` as the source.
3. The included workflow in `.github/workflows/github-pages.yml` will automatically deploy the site on every push to `main`.
4. After the workflow completes, your site will be available at `https://<your-username>.github.io/<repository>`.

Once configured, any changes pushed to `main` will update the published site automatically.
