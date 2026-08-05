# Using Data Science Tools to Explore Rate Matching in a Nickel-Catalyzed Cross-Electrophile Coupling of Alkyl and Aryl Halides (Cl, Br) with a Tridentate Monoanionic Ligand

This repository contains notebooks used in this work, including:
- Correction factors to predict aryl and alkyl chloride descriptor libraries
- Random forest regression models to predict relative rate constants for aryl and alkyl halides
- Visualizations of correlations between rate and yield

The attached Excel sheets include input features for modeling, construction of UMAP, 
calculated descriptor libraries, and correction factor information.

DFT optimized xyz coordinates are available in xyz_coordinates.

## Installation

Two environment files are provided:
- `CF_alkyl_rf.yml` — for correction factor calculations, random forest alkyl 
  rate modeling
- `aryl_rf_env.yml` — for random forest aryl rate modeling
- `rate_yield_analysis.yml` — for rate/yield analysis

  To create and activate an environment:
```bash
conda env create -f CF_alkyl_rf.yml
conda activate CF_alkyl_rf
```
## Contents
| Folder | Description |
|--------|-------------|
| `RF_alkyl_rates/` | Random forest model for alkyl halide rate prediction |
| `RF_aryl_rates/` | Random forest model for aryl halide rate prediction |
| `correction_factor/` | Descriptor library correction factors |
| `rate_yield_analysis/` | Rate-yield correlation analysis and interactive plots which show structures |
| `xyz_coordinates/` | .xyz files for DFT optimized structures |

| Excel File | Description |
|--------|-------------|
| `molecular_descriptors.xlsx` | Calculated / predicted descriptors for aryl and alkyl virtual libraries |
| `correction_factor_info_aryl_alkyl.xlsx` | Correction factor training sets and informations |
| `modeling_input_features.xlsx` | Input features used to construct models |
| `umap.xlsx` | UMAP coordinates and features used to make UMAPs |

| File | Description |
|--------|-------------|
| `crude_1HNMR_NMRYields.pdf` | Crude 1H NMR spectra for NMR yield data |
| `interactive_plot.html` | html file for interactive plots of UMAP/predicted rates, rate-yield bubble plot, and classification models |


