# The Geometry of Narrative Overfitting

Replication code, spectral diagnostics, and simulation protocols for **"The Geometry of Narrative Overfitting: A Linear Algebra Demolition of Grand Theories in Soft Sciences."**

## Overview
This repository implements a linear algebraic audit of theoretical frameworks across political sociology, macroeconomics, and cognitive psychology. By analyzing residual Hessian conditioning ($\kappa(\mathcal{H})$), singular value spectra, and effective degrees of freedom ($\text{DoF}$), the scripts expose how excessive regularization and dimensional compression generate smooth mathematical artifacts out of noisy empirical data.

## Contents
* `narrative_overfitting_audit.ipynb`: Self-contained Python notebook reproducing:
  1. **Case Study 1 (Parliamentary Factionalism):** Synthetic roll-call SVD demonstrating the Guttman horseshoe compression artifact ($R^2 = 0.5580$).
  2. **Case Study 2 (Macroeconomic Expectations):** Heavy-tailed Markov shock simulation smoothed via Tikhonov regularization ($\alpha = 5000$), yielding $\kappa(\mathcal{H}) = 8.00 \times 10^4$ and $\text{DoF} = 7.32 / 150$.
  3. **Spectral Profiles:** Comparative eigenvalue decay plots for both systems.

## Archival DOI & License
* **Zenodo Archive:** 10.5281/zenodo.24137937
* **License:** MIT License
