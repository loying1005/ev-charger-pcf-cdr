# EV Charger Product Carbon Footprint & CDR Neutralization Plan

A product carbon footprint (PCF) of a typical Level 2 AC electric vehicle charger (wallbox), followed by a carbon dioxide removal (CDR) portfolio designed to neutralize its residual emissions.

> **Disclaimer:** This is an independent learning project built entirely on public data. It does not use, represent, or estimate any company's proprietary or confidential data.

## Research Question

What is the cradle-to-grave carbon footprint of a typical Level 2 AC wallbox, where are its emission hotspots, and is the result consistent with published PEP ecopassport declarations for similar products? Based on its residual emissions, what CDR portfolio would credibly neutralize them?

## Method

| Step | Notebook | Standard / Framework | Output |
|---|---|---|---|
| 1. Goal & scope | `01_scope_boundary` | ISO 14067 framework, applied through PEP ecopassport PCR ed4 and PSR-0018 | Functional unit, system boundary, cut-off rules, data quality requirements |
| 2. Inventory & calculation | `02_inventory_calc` | PCR ed4 and PSR-0018; EPA eGRID | Bill of materials × emission factors; use-phase electricity (California vs. Texas); DQR data quality scores |
| 3. Validation | `03_validation` | DQR (PCR ed4) → pedigree; Monte Carlo | Mass balance check, pedigree-based uncertainty range, benchmark against public PEP ecopassports |
| 4. CDR portfolio | `04_cdr_portfolio` | — | Removal portfolio scored on additionality, permanence, reversal risk, MRV, cost, and ex-ante vs. ex-post issuance |

## Repository Structure

```
ev-charger-pcf-cdr/
├── README.md
├── requirements.txt
├── notebooks/          # Analysis notebooks, run in order
├── data/
│   ├── raw/            # Public source data (see SOURCES.md)
│   └── processed/      # Cleaned and derived tables
└── docs/
    ├── learning_map.md       # Concepts covered in each step
    └── assumptions_log.md    # Every assumption, with rationale and source
```

## Roadmap & Status

| Notebook | Status |
|---|---|
| `01_scope_boundary` | ✅ Complete |
| `02_inventory_calc` | ⬜ Not started |
| `03_validation` | ⬜ Not started |
| `04_cdr_portfolio` | ⬜ Not started |

## Reproducibility

```bash
pip install -r requirements.txt
jupyter notebook
```

Data sources are listed in [`data/raw/SOURCES.md`](data/raw/SOURCES.md). Assumptions are listed in [`docs/assumptions_log.md`](docs/assumptions_log.md).
