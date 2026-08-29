# iBODY — static site (staging)

Built website files for i-body.ca, served via GitHub Pages for review.

- **Do not edit files here by hand** — this repo holds build output only.
  The source lives in the private `ibody-clinic` repo under `website/`;
  rebuild there and push the new `dist/` here.
- The staging build is `noindex` with a `Disallow: /` robots.txt on purpose,
  so it never competes with the live site in search engines.
