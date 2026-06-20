# plentii-food — Project Brain

Per-repo brain, migrated from central claude-memory 2026-06-20. Canonical project memory now lives here.

## Current state
- Diet-agnostic "Rosetta Stone" food database. 15 dieting metrics as equal pillars; every food carries every metric simultaneously.
- Phase 1 BUILT + committed (`ba61871`, May 13 2026). 21 pages, 10,841 lines.
- Stack: Astro 5 + Tailwind 4, JSON-LD per page, Fraunces/Inter/JetBrains Mono fonts, forest/cream/amber palette.
- Repo: `sunnyp81/plentii-food`. Local: `C:\Users\sunny\repos\plentii-food\`.
- Status: awaiting CF Pages connect (build `npm run build`, output `dist`, NODE_VERSION=22) + domain (plentii.food) + GSC/Bing.
- Revenue: £0.
- NOTE: central registry later flagged a possible pivot to integrate plentii into shecookssheeats.com as a premium app feature — confirm direction before Phase 2.

## Cross-link contract
- plentii = data + decisions; shecookssheeats.com = recipes. NO `/recipes/` on plentii.

## Page inventory (Phase 1)
- 1 homepage (ROOT, 9 sections, banana multi-metric chip, 15-pillar grid, FAQ)
- 1 manifesto (/about/, ~4,000 words)
- 8 foundational guides — calories, syns, WW points, macros, TDEE, BMR, deficit, surplus/recomp
- 6 working JS calculators — TDEE (Mifflin-St Jeor), syns-to-cal, WW-to-cal, macros, BMI, alcohol units
- 5 E-E-A-T trust pages — editorial policy, methodology, team hub, 2 author profiles
- robots.txt, llms.txt, ai.txt, sitemap-index.xml auto-generated

## Key facts & warnings
- 🔴 YMYL critical hire: HCPC-registered Dietitian or AfN Nutritionist for clinical review (£100-200/mo). Without it, ranking ceiling ~30-40% of potential.
- Full architecture = 1,017 pages across 5 phases. Maps in `G:\My Drive\Claude Code Work\Topical_Maps\plentii-food_topical_map.md`; Phase 1 briefs in `plentii-food_phase1_briefs.md`; original HTML mockups in `plentii-mockups\`.
- Phase 2 = 15 metric hubs + 50 foods + 20 tools + 5 migration bridges; starts once Phase 1 is live + indexed.
- Dev server was on port 4322.

## History
- 2026-05-13 — Phase 1 built + committed `ba61871`. Awaiting GitHub push / CF Pages connect / domain / GSC + Bing.
