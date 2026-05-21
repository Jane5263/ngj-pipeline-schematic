# NGJ Perturbation Atlas — v2.4 Engine Pipeline Schematic

A single-page interactive visualization of the v2.4 engine pipeline.

**Live:** https://jane5263.github.io/ngj-pipeline-schematic/

## What's in it

- Six stages of the pipeline (foundation → references → gene wiring → simulation → scoring → validation → orchestration)
- A glossary of every named metric (tissue concordance, menstrual alignment, NPA, WES/NES, IRS, fibrosis composite, organ tox AUC, collapse drivers)
- The validation gate — four real-world benchmarks each engine release must pass
- The three v2.4 deltas over v2.3 (expression scaling, 24 tox mechanisms, fibrosis calibration)

Every diagram node, stage title, script name, and metric card is hoverable (desktop) or tappable (mobile) for a deeper description.

## Updating

Replace `index.html` with a fresh export from `outputs/v24_pipeline_schematic.html` in the upstream `perturbation-atlas` repo.

---
© NextGen Jane · v2.4 · 2026-04-15
