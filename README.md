# Using Data Science Tools to Explore Rate Matching in a Nickel-Catalyzed Cross-Electrophile Coupling of Alkyl and Aryl Halides (Cl, Br) with a Tridentate Monoanionic Ligand

This repository contains notebooks used in this work, including:
- Correction factors to predict aryl and alkyl chloride descriptor libraries
- Random forest regression models to predict relative rate constants for aryl and alkyl halides
- Visualizations of correlations between rate and yield

The attached Excel sheets include input features for modeling, construction of UMAP, 
calculated descriptor libraries, and correction factor information.

## Installation

Two environment files are provided:
- `CF_alkyl_ratematch.yml` — for correction factor calculations, random forest alkyl 
  rate modeling, and rate/yield analysis
- `aryl_rf_env.yml` — for random forest aryl rate modeling

  To create and activate an environment:
```bash
conda env create -f CF_alkyl_ratematch.yml
conda activate CF_alkyl_ratematch
```
## Contents
| Folder | Description |
|--------|-------------|
| `RF_alkyl_rates/` | Random forest model for alkyl halide rate prediction |
| `RF_aryl_rates/` | Random forest model for aryl halide rate prediction |
| `correction_factor/` | Descriptor library correction factors |
| `rate_yield_analysis/` | Rate-yield correlation analysis and interactive plots which show structures |






