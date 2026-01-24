# Code and data for this study

This repository contains the genome-scale metabolic model (GEM),
enzyme-constrained GEM (ecGEM), datasets, and scripts used to reproduce
the computational results reported in the manuscript.

---

## Contents

- `models/`  
  Curated GEM and ecGEM used in this study.

- `data/`  
  kcat assignment table and biomass composition data.

- `scripts/`  
  Scripts used to run simulations.

- `requirements.txt`  
  Conda environment specification.

---

## Environment

All simulations were performed using:
- Python 3.8
- COBRApy (tested with v0.21.0)
- Gurobi solver (default parameters)

A valid Gurobi license is required.
