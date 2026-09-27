# Business Process Automation — Website

Static site, no build step. Deploy on **GitHub Pages**:

1. Create a repo (e.g. `yourname.github.io` or any repo name).
2. Copy all files in this folder to the repo root (keep `.nojekyll`).
3. Push to `main`.
4. Repo → **Settings → Pages** → Source: `Deploy from a branch` → Branch: `main` / `/(root)`.
5. Site goes live at `https://yourusername.github.io/reponame/`.

## GoatCounter analytics
Every page has this snippet before `</body>`:

```html
<script data-goatcounter="https://MYCODE.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>
```

1. Create a free account at https://www.goatcounter.com
2. Replace `MYCODE` in **every HTML file** with your GoatCounter site code.
3. Visits will show up in your GoatCounter dashboard (no cookie banner needed — it's cookieless/GDPR-friendly).

## Contact form
`contact.html` posts to Formspree (`https://formspree.io/f/yourFormID`) — sign up free at
https://formspree.io and swap in your own form ID, or replace with your own backend.

## Files
- `index.html` — homepage
- `services.html` — full service catalogue (8 categories + tutoring)
- `packages.html` — fixed-scope packages
- `shop.html` — digital products
- `about.html`, `contact.html`
- `style.css` — shared Win95-retro stylesheet used by every page
