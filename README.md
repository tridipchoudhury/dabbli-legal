# dabbli-legal

Public landing page, privacy, terms and support information for Dabbli.

The repository is the reviewed source for the public legal site. Production is
served as static, unauthenticated HTTPS pages through Cloudflare; GitHub Pages
is intentionally not used. The site contains no cookies, forms, analytics,
tracking pixels or third-party assets.

English and Dutch pages are maintained together:

- `index.html` / `index-nl.html`
- `privacy.html` / `privacy-nl.html`
- `terms.html` / `terms-nl.html`
- `support.html` / `support-nl.html`

Before publishing an update, confirm all local links resolve, both language
versions describe the same behavior, and the public URLs still match the app
and App Store Connect metadata.

## Local preview

From the repository root, run:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8080/`. Landing-page imagery is kept in
`assets/landing/`; its README records the asset roles and replacement notes.
