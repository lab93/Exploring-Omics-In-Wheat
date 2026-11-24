# Exploring-Omics-and-Methods-to-Improve-Wheat-Prediction-Across-Locations-Years-and-New-Genotypes

# Masked Wheat Phenotypic and Genomic Data (2024–2025)

Supplementary data for **[Exploring Omics and Methods to Improve Wheat Prediction Across Locations, Years, and New Genotypes]**.

## Files
| File | Dimensions | Description |
|---|---|---|
| `pheno.rds` | 4,374 rows × 7 columns | Phenotypic records (long format) |
| `geno.rds` | 399 rows × 400 columns | Genomic features per line |

## Phenotypic data (`pheno.rds`)
| Column | Description | Unit |
|---|---|---|
| `GE` | Masked line ID | – |
| `Location` | Environment (location + year) | – |
| `Year` | Season | – |
| `Yield_kg_ha` | Grain yield | kg ha⁻¹ |
| `Plant_height_cm` | Plant height (manual) | cm |
| `Plant_height_RS_cm` | Plant height (remote sensing) | cm |
| `Days_to_heading` | Days to heading | day of year |

**Environments:** Buhler, Garden City, Imperial and Wamego (2024 and 2025); Hutchinson,
Manhattan and Russell (2025 only).
