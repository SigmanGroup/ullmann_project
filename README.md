# Ullmann Project

Welcome to the Ullmann Project repository, a comprehensive resource for the research and data related to our project. This repository includes Cartesian coordinates of optimized geometries, an Excel file featuring both experimental and computed data, and the Jupyter notebooks utilized throughout the project.

For in-depth information, please consult our associated manuscript on [ChemRxiv](https://chemrxiv.org/engage/chemrxiv/article-details/6532eb5cc3693ca993c1ce40).

## Contents

- **computed_data.xlsx:** Excel file containing experimental yields and computed properties. Structural properties were computed at the wB97X-D/def2-TZVP level using Gaussian16.
- **"optimized_coordinates" folder:** This folder contains .txt files with the optimized xyz coordinates for all aryl-bromides, primary amines, and ligands employed in the project. These geometries were optimized at the wB97X-D/def2-SVP level using Gaussian16.
- **"clustering" folder:** This folder contains the Jupyter notebooks utilized for clustering the primary amines and aryl-bromides. Code was adapted from the [Doyle Lab](https://pubs.acs.org/doi/10.1021/jacs.1c12203).
- **"workflow" folder:** This folder contains two Jupyter notebooks utilized during this project:
  1. ***ligand_threshold.ipynb:*** Notebook utilized for the active learning selection of ligands. Code was adapted from the joint publication between the [Doyle & Sigman Labs](https://www.science.org/doi/10.1126/science.abj4213).
  2. ***workflow_ullmann.ipynb:*** Comprehensive notebook for training and validating the decision tree model, as well as developing the uncertainty maps and ligand suggestion tool.

## Additional resources

The substrate libraries were created utilizing the python scripts in the commercial search [GitHub Repository](https://github.com/SigmanGroup/Commercial_Search), developed by Dr. David Vogt.
