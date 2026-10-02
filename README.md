# SPHERE marketing site

Single-page product marketing site for **SPHERE** (Statistical Programming Hub for Execution and Reporting Environment).

Layout rhythm inspired by ReceptWise (soft paper sections, pill CTAs, generous spacing, clear stacked sections). Brand locked to navy `#0A3D6F` + paper aesthetic — not ReceptWise teal.

## Structure (one long scroll)

1. Sticky nav (anchor links only)
2. Hero — pill eyebrow, headline, lead, pill CTAs, **exactly one** product screenshot (Study home) in browser chrome + float chips
3. Who it’s for — persona cards
4. Why teams adopt — problem → outcome cards
5. Capabilities — text modules (Study home, Mock Shells, Tracker, Runs, Files, Packages/Define, Copilot, Admin) — no extra UI shots
6. Study delivery — abstract workflow diagram + delivery cards
7. Compliance & audit
8. How it works — 5 steps
9. Product principles
10. Navy CTA band → Request demo
11. Footer (tiny © Atulit)

**Product UI policy:** only `assets/shot-study-home.png` appears on the page. Tracker / mock-shells / row detail screenshots are intentionally not shipped (copy-risk).

## Preview

```bash
cd /workspace/sphere-marketing-site
python3 -m http.server 8765
# http://127.0.0.1:8765/
```

## Assets

- Brand lockups/marks from `/workspace/sphere-brand/pack/`
- Single UI shot: Study home

## Proof

- `screenshots/home-desktop.png`
- `screenshots/home-mobile.png`
