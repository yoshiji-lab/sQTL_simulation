# Analytic Power Curves for sQTL / GWAS

This repository contains a single Jupyter notebook (`power_curve_demo.ipynb`) that uses a closed-form formula to plot statistical power under a genome-wide significance threshold (e.g. Bonferroni or BH-equivalent). No external data or Monte-Carlo simulations are required.

---

## Files

- **power_curve_demo.ipynb**  
  - Defines the `analytic_power(n, maf, β, p_thr)` function
  - Plots **Power vs Effect Size** at fixed MAF  
  - Plots **Power vs MAF** at fixed effect size  
  - Compares results with publicly available GTEx sQTL discoveries  

- **README.md**  
  - This file

---

## Quick Start

1. Install dependencies:
   ```bash
   pip install numpy scipy matplotlib
