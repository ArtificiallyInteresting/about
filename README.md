# about

The source of https://resume.artificiallyinteresting.com: one static page of plain HTML and CSS, with no build step and no JavaScript.

- `index.html`: the page
- `404.html`: the not-found page
- `_headers`: response headers for Cloudflare Pages
- `fonts/`: Space Grotesk (headings), self-hosted, under the SIL Open Font License (`fonts/OFL.txt`)

The scroll effects use CSS scroll-driven animations; browsers without them get a static page, and everything stops moving for visitors who ask for reduced motion.

Hosted on Cloudflare Pages. Build command: none. Output directory: `/`.
Every push to `main` deploys.
