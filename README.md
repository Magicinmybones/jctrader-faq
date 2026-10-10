# JCTRADER FAQ

Static FAQ prototype deployed to Cloudflare Pages. The site has no build step or runtime dependencies.

## Files

- `public/index.html` — page markup, styles, and interaction code
- `public/assets/` — local WOFF2 font files used by the page

## Deploy

From this folder, run:

```sh
npx wrangler pages deploy public --project-name jctrader-faq --branch main
```

The Cloudflare Pages project uses Direct Upload. Pushing to GitHub stores the source but does not trigger deployment; run the command above after changes.
