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

Homepage hero replacement (2026-06-03):

- Draft label: `cinematic-flow-v284-sandbox`
- Product version: `0.3.380`
- Source: first-party CaseRoom visual evidence packet with source ledger in `marketing/source-ledgers/finalsnap-editorial-record-v21.md`
- Homepage assets: `assets/finalsnap-caseroom-workflow-v284.mp4`, `assets/finalsnap-caseroom-workflow-v284-poster.png`, and `assets/finalsnap-caseroom-workflow-v284-contact-sheet.jpg`
- Visual correction: no capture popup pollution, browser-maximized recording, visible four-border Crop, one-pass Cut Middle with only a small breath above the next card, Smart Erase restored, red before/after callouts inside viewport, and browserless logo finale.
- Review source: `marketing/cinematic-flow-v284-sandbox/storyboard.md`
- Account boundary: this homepage/video promotion must not change Account server, Account route, payment flow, or account handoff behavior.

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

Current homepage and function-clip assets:

- `assets/finalsnap-caseroom-workflow-v284.mp4`
- `assets/finalsnap-caseroom-workflow-v284-poster.png`
- `assets/finalsnap-caseroom-workflow-v284-contact-sheet.jpg`
- `assets/finalsnap-v284-clip-crop-edges.mp4`
- `assets/finalsnap-v284-clip-cut-middle-reconnect.mp4`
- `assets/finalsnap-v284-clip-smart-erase-noise.mp4`
- `assets/finalsnap-v284-clip-before-after-clean-record.mp4`

These are generated from `marketing/cinematic-flow-v284-sandbox/`, which uses the first-party CaseRoom test page and FinalSnap `manifest.json` version `0.3.380`. Keep the source page, storyboard, contact sheets, and visual-audit output together so future homepage updates can be traced back to the exact recording. The hero fullscreen target should be the video stage only, not the whole card, so fullscreen playback does not show the page caption or rounded-card corners.

Superseded public-site promo assets such as v19 government-site recordings, older real-page clips, and May 2026 magic-cut videos should not be referenced by the live website. If they must be kept for archive or store-history purposes, keep them outside the public website asset path and label them as superseded.
