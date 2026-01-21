# Condensin Kymograph Analysis

This repository contains the Jupyter notebooks used to analyze LUMICKS C-Trap
kymograph data for the study of condensin diffusion and force–distance behavior.

The analysis includes:
- Automated kymograph tracking
- Extraction of diffusion trajectories
- Force–distance curve analysis
- Quantitative plotting used in the associated publication

---

## Repository structure
```text
condensin-kymograph-analysis/
├── notebooks/
│ ├── 00_condensin_kymotracking_diffusion.ipynb
│ └── 01_condensin_FD_curves.ipynb
├── requirements.txt
├── LICENSE
└── README.md
```
---

## Notebooks overview

### `00_condensin_kymotracking_diffusion.ipynb`
- Loads LUMICKS kymograph data
- Performs kymograph tracking
- Extracts condensin trajectories
- Computes diffusion-related quantities
- Export data

### `01_condensin_FD_curves.ipynb`
- Loads force–distance data
- Extracts quantitative force–distance parameters
- Export data

The notebooks are intended to be run **in order**.

---

## Requirements

- Python ≥ 3.9
- Jupyter Notebook 
- Core scientific packages:
  - numpy
  - scipy
  - matplotlib
  - pandas
- LUMICKS analysis package:
  - lumicks.pylake

Detailed instruction on how to install Anaconda and Pylake package is available here: https://lumicks-pylake.readthedocs.io/en/latest/install.html#installation-instructions

For questions, contact alessandro.borsellini@outlook.it or joanna.andrecka@fht.org
