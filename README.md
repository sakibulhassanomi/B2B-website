# SM Technology — landing page

Static site (HTML + CSS + vanilla JS). No build step.

## Deploy on Vercel
1. Push this folder to GitHub (or run `npx vercel` inside it).
2. In Vercel: **Add New → Project → import repo**. Framework preset: **Other**. Leave build command and output directory empty.
3. Deploy.

## Preview locally
`python3 -m http.server 3000` then open http://localhost:3000

## Things to replace
- **Client logos**: `index.html`, section `#clients` — swap each `.logo.slot` for `<div class="logo"><img src="/assets/clients/name.svg" alt="Name"></div>`.
- **Contact form** opens the visitor's email app (mailto). To receive submissions directly, point it at Formspree/Resend/etc.
- Add `og:image` and your final domain to the `<head>` for social previews.
