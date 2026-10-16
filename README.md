# EV Charger Product Carbon Footprint & CDR Neutralization Plan

A product carbon footprint (PCF) of an AC Level 2 electric vehicle charger, followed by a carbon dioxide removal (CDR) portfolio designed to neutralize its residual emissions.

> **Disclaimer:** This is an independent learning project built entirely on public data. It does not use, represent, or estimate any company's proprietary or confidential data.

## Research Question

<!-- TODO (you): Write 1–2 sentences. What decision should this analysis support, and for whom? -->

## Method

| Step | Notebook | Standard / Framework | Output |
|---|---|---|---|
| 1. Goal & scope | `01_scope_boundary` | ISO 14067, ISO 14040/14044 | Functional unit, system boundary, cut-off rules, data quality requirements |
| 2. Inventory & calculation | `02_inventory_calc` | ISO 14067; EPA eGRID | Bill of materials × emission factors; use-phase electricity (California vs. Texas) |
| 3. Validation | `03_validation` | Pedigree matrix; Monte Carlo | Mass balance check, data quality scores, uncertainty range, benchmark against public PEP ecopassports |
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
| `01_scope_boundary` | ⬜ Not started |
| `02_inventory_calc` | ⬜ Not started |
| `03_validation` | ⬜ Not started |
| `04_cdr_portfolio` | ⬜ Not started |

## Reproducibility

```bash
pip install -r requirements.txt
jupyter notebook
```

Data sources are listed in [`data/raw/SOURCES.md`](data/raw/SOURCES.md). Assumptions are listed in [`docs/assumptions_log.md`](docs/assumptions_log.md).
