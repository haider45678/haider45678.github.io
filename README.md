# Haider Raza — Personal Portfolio

A responsive, premium-light static portfolio built with plain HTML, CSS and JavaScript. It is hosted on GitHub Pages and requires no backend, build tools or paid hosting.

**Live site:** <https://haider45678.github.io>

## Project structure

```
index.html              Home page (hero, about, focus areas, apps, contact)
apps/index.html         Apps & projects page
privacy-policy/         Privacy policy page
terms/                  Terms of use page
assets/style.css        All styling, including mobile breakpoints
assets/script.js        Mobile menu and footer year
assets/favicon.svg      Site icon
```

## Contact details

- Email: `haider.awan350@gmail.com`
- GitHub: <https://github.com/haider45678>
- LinkedIn: <https://www.linkedin.com/in/haider45678/>

If any of these change, update the contact section of `index.html` and the contact lines in `privacy-policy/index.html` and `terms/index.html`.

The `<head>` of `index.html` also contains the Google Search Console verification tag. Keep it there, or replace the token if the site is re-verified.

Also review the privacy policy and terms. The privacy policy here describes this portfolio website only; **each Android app should have its own accurate privacy policy** describing its actual data collection, SDKs, permissions, ads and analytics.

## Deploying updates

The repository is already published with GitHub Pages (branch `main`, folder `/ (root)`). Commit and push, and the site rebuilds automatically:

```
git add -A
git commit -m "Describe the change"
git push
```

The deployment status is visible under **Settings → Pages** or in the repository's **Actions** tab.

## Adding an Android app later

Replace the placeholder card in the "Products in progress" section of `index.html` and the placeholder block in `apps/index.html` with the app name, short description and its Google Play listing URL. If you want icons or screenshots, extend the layout in those two files and add the images under `assets/`. Add a separate app privacy policy page if its practices differ from this website.

## Optional custom domain

You can connect a domain later in **Settings → Pages → Custom domain**. Follow GitHub's current DNS instructions for your domain registrar and enable HTTPS after DNS verification.

## Local preview

Open `index.html` in a browser. No package installation is required.
