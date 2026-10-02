# SPHERE marketing site

Single-page product marketing site for **SPHERE** (Statistical Programming Hub for Execution and Reporting Environment).

Layout rhythm inspired by ReceptWise (soft paper sections, pill CTAs, generous spacing, clear stacked sections). Brand locked to navy `#0A3D6F` + paper aesthetic — not ReceptWise teal.

## Structure (one long scroll)

1. Sticky nav (anchor links only)
2. **Navy hero** — pill eyebrow, headline, lead, pill CTAs, **exactly one** product screenshot (Study home) in browser chrome + float chips; wave into paper below
3. Who it’s for — persona cards
4. Commercial imagery mosaic — workplace / analytics stock photos (not product UI)
5. Why teams adopt — problem → outcome cards
6. Split visual — biometrics workplace photo + ops copy
7. Capabilities — text modules (Study home, Mock Shells, Tracker, Runs, Files, Packages/Define, Copilot, Admin) — no extra UI shots
8. Split visual — abstract analytics graphic + tracker clarity copy
9. Study delivery — abstract workflow diagram + delivery cards
10. Compliance & audit
11. How it works — 5 steps
12. Product principles
13. Navy CTA band → Request demo
14. Footer (© SPHERE)

**Product UI policy:** only `assets/shot-study-home.png` appears on the page. Tracker / mock-shells / row detail screenshots are intentionally not shipped.

**Commercial imagery:** royalty-free Unsplash photos + a tasteful SVG analytics composite under `assets/img-*`. No personal or company founder names on the page.

## Preview

```bash
cd /workspace/sphere-marketing-site
python3 -m http.server 8765
# http://127.0.0.1:8765/
```

## Assets

- Brand lockups/marks from `/workspace/sphere-brand/pack/`
- Single UI shot: Study home
- Marketing imagery: `img-laptop-work.jpg`, `img-analytics-charts.jpg`, `img-office-meeting.jpg`, `img-biometrics-pro.jpg`, `img-analytics-graphic.svg`

## Proof

- `screenshots/home-desktop.png`
- `screenshots/home-mobile.png`

## Live

https://atulitllc.github.io/sphere-marketing-site/
