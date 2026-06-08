# Productbuilder Site

Static marketing and documentation starter site for Productbuilder.

## Local preview

Open `index.html` in a browser, or run a tiny static server:

```sh
python3 -m http.server 8080
```

Then visit:

```text
http://localhost:8080
```

## GitHub Pages

This starter is plain HTML/CSS, so GitHub Pages can publish it directly. The workflow at `.github/workflows/pages.yml` publishes the repository root as a Pages artifact.

Recommended repository settings:

- Settings -> Pages -> Source: GitHub Actions.
- Push to `main`.
- The workflow publishes the repository root.

Expected public URL:

```text
https://mcsim0001.github.io/productbuilder-site/
```

If a custom domain is added later, update `robots.txt` and `sitemap.xml`.

## Next links to connect

- GitHub Release asset for the primary download button
- Mac App Store
- mono donation page
- Donatello support page
- Support email
