# Exploring-Omics-and-Methods-to-Improve-Wheat-Prediction-Across-Locations-Years-and-New-Genotypes
data of the paper submitted to G3 
# Masked Wheat Phenotypic and Genomic Data (2024–2025)

Supplementary data for **[Exploring Omics and Methods to Improve Wheat Prediction Across Locations, Years, and New Genotypes]**.

## Overview
This dataset contains phenotypic and genomic data for **[N] winter wheat lines** grown in
**11 environments** (location × year) in Kansas and Nebraska during the 2024 and 2025 seasons.
Line names are masked as `geno1`, `geno2`, and so on. Both files use the same masked IDs,
so they can be joined directly.

## Files
| File | Object | Description |
|---|---|---|
| `pheno_4traits.rds` | `pheno_out` | Phenotypic records (long format) |
| `geno_features.rds` | `x_df` | Genomic features per line |

## Phenotypic data (`pheno_out`)
| Column | Description | Unit |
|---|---|---|
| `GE` | Masked line ID | – |
| `Location` | Environment (location + year) | – |
| `Year` | Season | – |
| `YIELD_kg_ha` | Grain yield | kg ha⁻¹ |
| `HDDAT_Day` | Days to heading | day of year |
| `PLTHT_cm` | Plant height (manual) | cm |
| `PLTHT_RS_cm` | Plant height (remote sensing) | cm |

**Environments:** Buhler, Garden City, Imperial and Wamego (2024 and 2025); Hutchinson,
Manhattan and Russell (2025 only).
