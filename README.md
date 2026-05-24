# FinalSnap Public Site

This repository hosts the free GitHub Pages public site for the FinalSnap Chrome extension.

Recommended Chrome Web Store URLs after GitHub Pages is enabled:

- Homepage: `https://finalsnap.cc/`
- Brand search landing page: `https://finalsnap.cc/chrome-extension.html`
- Account entry: `https://finalsnap.cc/account.html`
- Support: `https://finalsnap.cc/support.html`
- Privacy policy: `https://finalsnap.cc/privacy.html`
- Chrome Web Store item: `https://chromewebstore.google.com/detail/fbplgmgpdnogfbifbcmcadhfnnbcifcd`
- Sitemap: `https://finalsnap.cc/sitemap.xml`
- Robots: `https://finalsnap.cc/robots.txt`

Chrome Web Store "Official URL" can remain `None` until the site is verified in Google Search Console.
The Homepage URL and Support URL can use the GitHub Pages URLs above immediately.

Mainland China sharing note:

- Do not send Chinese users only the raw Chrome Web Store URL. Chrome Web Store can be unavailable in mainland China even when the item URL itself is valid.
- Share the brand landing page first: `https://finalsnap.cc/chrome-extension.html`.
- Keep Chrome Web Store as the official primary install source, but the landing page should show a clear support fallback for users whose region cannot open the store.
- Do not publicly promise an alternate store, mirror, CRX, or zip install path until that path is actually prepared, tested, and supportable.

Brand-search SEO notes:

- The homepage, brand search landing page, support page, and privacy page should repeat `FinalSnap` consistently.
- The brand search landing page is intentionally narrow: answer searches such as `FinalSnap`, `FinalSnap Chrome extension`, `FinalSnap screenshot`, and `FinalSnap Chrome Web Store`.
- Keep structured data, canonical links, Open Graph, Twitter cards, `sitemap.xml`, and `robots.txt` aligned when URLs or major public copy change.
- Treat early Google indexing as a signal to strengthen brand ownership, not proof of stable demand.

Homepage hero animation:

- `assets/finalsnap-magic-cut-v7-site-nologo.mp4`
- `assets/finalsnap-magic-cut-v7-site-nologo-poster.png`

These are generated from `tools/render-finalsnap-magic-cut-promo-v7.py` and should stay aligned with the current short promo-video baseline in `marketing/promo-v7/`.
The homepage uses the no-logo variant because the site navigation already carries the FinalSnap brand mark; avoid double logo exposure in the first viewport.
The current hero animation mirrors the in-product Cut Middle effect: same-source band removal plus the real `.bandCutEffect` film-strip pull, closing lines, flash, and `Strip removed` badge.
Headline typography in generated promo assets should use the selected pixel-cut reference look: the high-contrast New York-style display serif from the `Remove the messy middle.` headline. Do not switch these promo/store hero assets to `Sora` / `Archivo` unless a future sans-serif variant is explicitly requested.

Standalone promo-video baseline:

- `assets/finalsnap-magic-cut-v7.mp4`
- `assets/finalsnap-magic-cut-v7-poster.png`

Locked approved promo-video snapshot:

- `assets/finalsnap-magic-cut-v7-scissors-locked-20260510.mp4`
- `assets/finalsnap-magic-cut-v7-scissors-locked-20260510-poster.png`

Keep these versioned files as the stable fallback for the May 10, 2026 scissors-consistent promo version.
