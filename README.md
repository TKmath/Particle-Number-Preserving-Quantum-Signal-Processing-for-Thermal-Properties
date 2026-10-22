# Particle-Number-Preserving-Quantum-Signal-Processing-for-Thermal-Properties

[![arXiv](https://img.shields.io/badge/arXiv-2610.09373-b31b1b.svg)](https://arxiv.org/abs/2610.09373)

This repository contains the code and data to reproduce the results presented in our manuscript. 

## Repository Contents

*   `main.ipynb` - Main Jupyter notebook used to run generate spectral data.
*   `gamma_estimates.ipynb` - Jupyter notebook used to calculate and process gamma estimates.
*   `Data/` - Directory containing spectral data.
*   `Figures/` - Directory containing the figures in the manuscript.

## Usage

To reproduce the results and figures from the paper, run the notebooks in the following order:

1.  Run `main.ipynb` to generate the data based on stochastic Lanczos method (saved to the `Data/` folder).
2.  Run `gamma_estimates.ipynb` to estimate the quantity of interest, gamma_1,2. Before running the code, please unzip files in Data folder and place the resulting folders in the same directory as 'gamma_estimates.ipynb'. 


## Citation

If you find this code useful in your research, please consider citing:

```bibtex
@article{ko2026particle,
  title={Particle-Number-Preserving Quantum Signal Processing for Thermal Properties: Canonical-Ensemble Estimation and Grand-Canonical Reconstruction},
  author={Ko, Taehee and Lim, Sungbin and Choi, Sangkook},
  journal={arXiv preprint arXiv:2610.09373},
  year={2026}
}
