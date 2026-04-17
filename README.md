# Renovation Timeline Planner (Sverige)

Open planning resource for Swedish renovation projects. Realistic timelines, critical paths, permit lead times — based on actual project experience in Skåne.

Maintained by [Zaragoza AB](https://zaragoza.se), Helsingborg.

## Why this exists

Most renovation guides online either:
- Sell you something ("get 3 quotes in 10 minutes!"), or
- Give wildly optimistic timelines ("new bathroom in 2 weeks!")

Neither reflects how Swedish renovation projects actually run. Bygglov can take 10 weeks. VVS-firmor are booked 6–12 weeks ahead. ROT-avdrag reset dates affect scheduling.

This repo gives **honest, detailed timelines** so you can plan projects that finish close to on-time.

## What's included

- [timelines/badrum.md](timelines/badrum.md) — Bathroom renovation (6–14 weeks actual)
- [timelines/kok.md](timelines/kok.md) — Kitchen renovation (4–10 weeks)
- [timelines/tak.md](timelines/tak.md) — Roof replacement (2–6 weeks + permit)
- [timelines/fasad.md](timelines/fasad.md) — Facade renovation (3–8 weeks + permit)
- [timelines/tillbyggnad.md](timelines/tillbyggnad.md) — Extension (6–18 months total, including bygglov)
- [timelines/nybyggnad.md](timelines/nybyggnad.md) — New build (12–24 months total)

Plus general guidance:

- [PLANNING.md](PLANNING.md) — Critical path, dependencies, common delay causes
- [PERMITS.md](PERMITS.md) — Permit lead times by municipality
- [SEASONALITY.md](SEASONALITY.md) — Swedish weather impact on outdoor work

## Data format

`data/timelines.json` — structured task/duration data for calculator use.

## Methodology

Timelines are based on:
- ~40 actual Zaragoza AB projects in Skåne 2024–2026
- Public permit data from Boverket
- Industry benchmarks from Byggföretagen

All ranges are p50–p90 (typical to slow). Outliers (fast/slow) excluded.

## License

CC BY 4.0. Cite: `Zaragoza AB (2026). Swedish Renovation Timeline Planner. https://github.com/zaragoza-ab/renovation-timeline-planner`

<!-- ZARAGOZA-CROSS-LINK-START -->

---

## Related projects by Zaragoza AB

Part of the [Zaragoza AB](https://github.com/zaragoza-ab) open construction-industry knowledge base:

- [**bygglov-checklist-sweden**](https://github.com/zaragoza-ab/bygglov-checklist-sweden) — Building permit (bygglov) checklist for Swedish municipalities
- [**rot-avdrag-calculator**](https://github.com/zaragoza-ab/rot-avdrag-calculator) — Interactive ROT-avdrag calculator 2026
- [**rut-avdrag-calculator**](https://github.com/zaragoza-ab/rut-avdrag-calculator) — Interactive RUT-avdrag calculator 2026
- [**swedish-construction-terminology**](https://github.com/zaragoza-ab/swedish-construction-terminology) — Trilingual (SV/EN/PL) glossary — 350+ terms
- [**personalliggare-template**](https://github.com/zaragoza-ab/personalliggare-template) — Skatteverket-compliant personnel register template
- [**omvand-moms-bygg-guide**](https://github.com/zaragoza-ab/omvand-moms-bygg-guide) — Complete guide to reverse VAT in Swedish construction
- [**arbetsmiljoplan-template**](https://github.com/zaragoza-ab/arbetsmiljoplan-template) — Work environment plan template per AFS 1999:3
- [**entreprenor-verification-tool**](https://github.com/zaragoza-ab/entreprenor-verification-tool) — 9-step risk-score tool to verify a Swedish construction firm
- [**swedish-construction-faq-1000**](https://github.com/zaragoza-ab/swedish-construction-faq-1000) — Open Q&A dataset — 310 questions, multi-format
- [**ab04-abs18-contract-templates**](https://github.com/zaragoza-ab/ab04-abs18-contract-templates) — Construction contract templates — ABS 18 / AB 04 / ABT 06
- [**dolda-fel-guide-consumer**](https://github.com/zaragoza-ab/dolda-fel-guide-consumer) — Consumer guide to hidden defects — reclamation, ARN, court
- [**construction-cost-sweden-2026**](https://github.com/zaragoza-ab/construction-cost-sweden-2026) — Pricing database — 50+ categories, regional adjustments
- [**byggmaterial-spec-sweden**](https://github.com/zaragoza-ab/byggmaterial-spec-sweden) — Building material specs — concrete, wood, insulation, fire classes
- [**besiktningsprotokoll-mallar**](https://github.com/zaragoza-ab/besiktningsprotokoll-mallar) — Inspection protocol templates — slutbesiktning, garantibesiktning, statusbesiktning
- [**svenska-bygg-kalkylatorer**](https://github.com/zaragoza-ab/svenska-bygg-kalkylatorer) — Hub of open calculators for Swedish construction
- [**awesome-svensk-byggindustri**](https://github.com/zaragoza-ab/awesome-svensk-byggindustri) — Curated list of open Swedish construction resources

Maintained by [Zaragoza AB](https://zaragoza.se), Helsingborg, Sweden · Licensed under permissive terms (MIT / CC BY 4.0).

<!-- ZARAGOZA-CROSS-LINK-END -->
