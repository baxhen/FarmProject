# Lands — Evaluated Properties

Farm property evaluations and enterprise analyses.

## Properties Evaluated

| # | Region | Spec | Property | Score | Recommendation | Date |
|---|--------|------|----------|-------|----------------|------|
| 1 | Miranda do Douro, PT | spec_1 | 5ha, 2 wells, unfinished building | 71/100 | BUY with conditions | 2026-07 |
| 2 | Miranda do Douro, PT | spec_2 | 0.6ha, flat, fenced, public water, fruit trees, building | 80/100 | BUY | 2026-07 |
| 3 | Perais, Vila Velha de Ródão, PT | spec_1 | 1ha, flat, oak grove (montado), fenced | 48/100 | PROBABLY NOT (homestead) / BUY at €7k (conservation asset) | 2026-07 |
| 4 | Miranda do Douro, PT | spec_3 | 1.43ha, stone walls, south slope, Espaço Agrícola, Sendim | 70/100 | BUY at €22k | 2026-07 |

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
