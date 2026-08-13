# Zilong (Leon) Huang — Academic Homepage

Personal academic homepage for Zilong Huang, built with the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) Jekyll template and published as a GitHub Pages project site.

## Public URL

`https://slash1028.github.io/LeonHuang/`

## Content maintenance

- Main page content: `_pages/about.md`
- Name, bio, contact links, site URL: `_config.yml`
- Top navigation: `_data/navigation.yml`
- Custom visual styling: `assets/css/main.scss`
- Monogram placeholder: `images/leon-monogram.svg`

The Google Scholar field is intentionally commented out until a confirmed public profile URL is supplied. The newest ACM Multimedia workshop paper links to its confirmed DOI.

## Deploy with GitHub Pages

1. Open the repository on GitHub and go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.
4. Wait for the Pages build to finish. The site will appear at the URL above.

The project-site path is configured through `baseurl: "/LeonHuang"`; keep this value synchronized with the repository name if the repository is ever renamed.

## Local preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve --baseurl /LeonHuang
```

Preview at `http://127.0.0.1:4000/LeonHuang/`.

## Attribution

This site retains the upstream MIT license and acknowledges AcadHomepage and Minimal Mistakes.
