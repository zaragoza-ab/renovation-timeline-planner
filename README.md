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
