# Lands — Evaluated Properties

Farm property evaluations and enterprise analyses.

## Properties Evaluated

| # | Region | Spec | Property | Score | Recommendation | Date |
|---|--------|------|----------|-------|----------------|------|
| 1 | Miranda do Douro, PT | spec_1 | 5ha, 2 wells, unfinished building | 71/100 | BUY with conditions | 2026-07 |
| 2 | Miranda do Douro, PT | spec_2 | 0.6ha, flat, fenced, public water, fruit trees, building | 80/100 | BUY | 2026-07 |

## Structure

Each property follows:
```
lands/<region>/<spec_N>/
├── README.md              ← Property summary
├── property_profile.md    ← Standardized data
├── evaluation/            ← Property assessment
├── enterprises/           ← Enterprise analyses
├── integration/           ← Cross-enterprise plans
├── land_specific/         ← Location reference data
└── documents/             ← Raw documents (PDFs, PDM)
```

## Scoring Quick Reference

| Score | Recommendation |
|-------|---------------|
| 85-100 | STRONG BUY |
| 70-84 | BUY |
| 55-69 | MAYBE |
| 40-54 | PROBABLY NOT |
| 0-39 | REJECT |
