# FinalSnap Public Site

This repository hosts the free GitHub Pages public site for the FinalSnap Chrome extension.

Recommended Chrome Web Store URLs after GitHub Pages is enabled:

- Homepage: `https://finalsnap.cc/`
- Brand search landing page: `https://finalsnap.cc/chrome-extension.html`
- Pricing: `https://finalsnap.cc/pricing.html`
- Account entry: `https://finalsnap.cc/account.html`
- Support: `https://finalsnap.cc/support.html`
- Privacy policy: `https://finalsnap.cc/privacy.html`
- Chrome Web Store item: `https://chromewebstore.google.com/detail/fbplgmgpdnogfbifbcmcadhfnnbcifcd`
- Sitemap: `https://finalsnap.cc/sitemap.xml`
- Robots: `https://finalsnap.cc/robots.txt`

Chrome Web Store "Official URL" can remain `None` until the site is verified in Google Search Console.
The Homepage URL and Support URL should use the public `finalsnap.cc` URLs above after the official-domain deploy is healthy.

## Website Refresh Drafts

Current local website draft:

- Draft label: `website-real-plugin-demo-2026-05-24-a`
- Baseline branch: `codex/gcp-mvp-backend`
- Baseline commit: `f63701a`
- Baseline manifest version: `0.3.327`
- Scope: `policy-site/index.html`, shared `assets/site.css`, and the promoted real-plugin hero video assets generated from `real-plugin-demo-v1`
- Rule: every visible CTA must point to a real page, Chrome Web Store URL, account handoff, or support email. No placeholder buttons, fake checkout buttons, decorative CTA controls, or public price promises without Account/server evidence.
- Navigation rule: all public pages use the same predictable top nav, `Home / Pricing / Account / Add to Chrome`. Do not put `Demo`, `ROI`, `Support`, or `Privacy` in the global top nav; those stay as body CTAs or footer/utility links. Account stays in the top nav because it is the real plan/billing/trial/receipt entry, and top-nav Account should route to the real Account server rather than a visible trampoline.
- Style target: concise product-proof pages with one idea per section, real product assets, and Silicon Valley-style restraint. Public copy should support the stable promise `Remove the messy middle.`
- Planning source: `marketing/public-website-strategy-2026-05-24.md`

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

- `assets/finalsnap-real-plugin-demo-v1.mp4`
- `assets/finalsnap-real-plugin-demo-v1-poster.png`

These are recorded by `tools/record-finalsnap-real-plugin-demo-v1.js` and promoted into `policy-site/assets/` so the public homepage uses the same source ledger and audit as `marketing/real-plugin-demo-v1/`.
The homepage hero must solve long-screenshot legibility with a real-plugin, same-source camera path: global original screenshot -> local Cut Middle view -> Smart Erase payoff -> global processed screenshot.
Do not replace the hero with stitched independent visuals. The top content should stay fixed, the unwanted band should collapse, and the lower content should move upward inside the same coordinate system.
The homepage uses a site-specific no-logo composition because the site navigation already carries the FinalSnap brand mark; avoid double logo exposure in the first viewport.
The current real-page source is a NASA Science article crop with usage and no-endorsement guardrails recorded in `marketing/real-plugin-demo-v1/source-ledger.md` and `marketing/realpage-hero-v1/source-ledger.md`. The earlier `finalsnap-realpage-hero-12s.*` and `finalsnap-cinematic-cut-hero-12s.*` assets remain source-quality and motion-proof fallbacks, not the current homepage recording.

Standalone promo-video baseline:

- `assets/finalsnap-magic-cut-v7.mp4`
- `assets/finalsnap-magic-cut-v7-poster.png`

Locked approved promo-video snapshot:

- `assets/finalsnap-magic-cut-v7-scissors-locked-20260510.mp4`
- `assets/finalsnap-magic-cut-v7-scissors-locked-20260510-poster.png`

Keep these versioned files as the stable fallback for the May 10, 2026 scissors-consistent promo version.
