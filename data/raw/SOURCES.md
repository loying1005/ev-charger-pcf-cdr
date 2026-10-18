# Data Sources

Public data only. Record each source when you first use it.

| ID | Dataset | Publisher | URL | Version / Year | Accessed | License | Used in |
|---|---|---|---|---|---|---|---|
| S01 | PSR-0018 Electric Vehicle Charging Infrastructures | P.E.P. Association | https://register.pep-ecopassport.org/documents | ed1.3, 2025-04-08 | 2026-10-17 | Not redistributed; see publisher | 01 (functional unit, reference scenario), 02 (use phase) |
| S02 | PSR-0018 ANNEXE: in-use consumption calculator | P.E.P. Association | https://register.pep-ecopassport.org/documents | ed1.4, 2025-04-08 | 2026-10-17 | Not redistributed; see publisher | 02 (use phase) |
| S03 | Hager PEP HAGE-01517-V01.01-EN (XEV080) | Hager | https://assets.hager.com/step-content/P/HA_89901566/Document/std.lang.all/PEP_HAGE-01517-V01.01-EN.pdf | 2026-04 | 2026-10-17 | — | Screened; excluded from benchmark (passive wall socket, not a wallbox) |
| S04 | ChargePoint Home Flex (CPH50) datasheet | ChargePoint | https://docs.chargepoint.com/ref-docs-sec/content/pdfs/home/cph50/cph50-ds.pdf | 2026 (file modified 2026-10-08) | 2026-10-17 | — | 01 (attached cable, 23 ft; A02) |
| S05 | Tesla Universal Wall Connector datasheet | Tesla | https://energylibrary.tesla.com/docs/Public/Charging/WallConnector/What-to-Expect/uwc_datasheet.pdf | 2023 (file modified 2023-09-29) | 2026-10-17 | — | 01 (attached cable, 24 ft or 13.1 ft by part number; A02) |
| S06 | Wallbox Pulsar Plus North America datasheet (PUP2) | Wallbox | https://support.wallbox.com/wp-content/uploads/ht_kb/2025/10/Wallbox_Datasheet_PulsarPlus_NA_NACS_EN_b.pdf | 2025-10 | 2026-10-17 | — | 01 (attached cable, 25 ft; A02) |
| S07 | ENERGY STAR certified EVSE listing: Grizzl-E Classic GR1-14-24-PB | U.S. EPA ENERGY STAR | https://www.energystar.gov/productfinder/product/certified-evse-ac-output/details/2740428/export/pdf | Accessed version | 2026-10-17 | Public | 01 (attached cable, 24 ft, 8 AWG; A02) |
| S08 | PEP-PCR ed4: Product Category Rules for electrical, electronic and HVAC equipment | P.E.P. Association | https://register.pep-ecopassport.org/documents | ed4, 2021-09-06 | 2026-10-18 | © P.E.P. Association; not redistributed | 01 (cut-off criteria §2.3, Table 2) |

**Notes**
- S02 labels the 11 kW wallbox as single-phase, which conflicts with S01 (pp. 7–8: 11 kW is three-phase). S01 prevails.
- S01 (p. 14) references annex ed1.2; this project uses the newer ed1.4 (S02).
- S04–S07: cable details were read from each original document. Products with only retailer listings (no manufacturer or certification source) were not included.
