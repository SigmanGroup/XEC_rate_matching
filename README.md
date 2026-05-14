# Using Data Science Tools to Explore Rate Matching in a Nickel-Catalyzed Cross-Electrophile Coupling of Alkyl and Aryl Halides (Cl, Br) with a Tridentate Monoanionic Ligand

This repository contains notebooks that were used in this work, including correction factors to predict aryl and alkyl chloride descriptor library, predict relative rate constants for aryl and alkyl halides with random forest regression, and visualize correlations between rate and yields. The attached excel sheets include input features for modeling and cnostruction of UMAP, calculated descriptor library, and information of correction factors. 

## Installation

.yml files for correction factor, alkyl rate random forest model, aryl rate random forest model, and correlation of rate and yields are attached. 

## Usage

1. Correction factor:
2. alkyl rate random forest model:
3. aryl rate random forest model:
4. visualize rate and yield correlation:
   
## Other changes to be made

I received this warning. This should be fixed with a corrected env file

/opt/miniconda3/envs/modeling/lib/python3.12/site-packages/tqdm/auto.py:21: TqdmWarning: IProgress not found. Please update jupyter and ipywidgets. See https://ipywidgets.readthedocs.io/en/stable/user_install.html
  from .autonotebook import tqdm as notebook_tqdm

It looks like your grid search doesn't search a lot of parameters, but that's okay if you're happy with the model. I
would recommend switching to grid search CV instead since you're only exploring a few combinations of hyperparameters.

In the "markdown" sections of your jupyter notebook, add a bit more detail about what is going on in each cell.





