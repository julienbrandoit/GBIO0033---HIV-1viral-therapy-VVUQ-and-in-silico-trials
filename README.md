# HIV Viral Therapy In Silico Study

This repository contains the code and analysis related to the in silico study of a viral therapy model for HIV-1, as presented in the report for the course **GBIO0033 - Advances in In Silico Medicine**.

## Overview

The study investigates a mathematical model describing the interaction between HIV-1, host cells, and a genetically modified therapeutic virus. Using ordinary differential equations (ODEs), the model simulates the effect of viral therapy in reducing HIV-1 load and restoring host cell populations. 

Key analyses include:
- **Reproduction of model dynamics**: Single and double infection scenarios.
- **Equilibrium and sensitivity analysis**: Exploration of parameter influence on treatment efficacy.
- **In silico clinical trials**: Simulation of virtual patient populations to assess treatment response variability.

## Contents

- `HIV.ipynb`: Jupyter Notebook containing all simulations and figure generation.
- `figures/`: Directory with visualizations of model results.

Details about the numerical dependences can be found in the report. 

## References

The study is based on the viral therapy model introduced in:
> *Revilla, T., & García-Ramos, G. (2003). Fighting a virus with a virus: a dynamic model for HIV-1 therapy. Mathematical Biosciences, 185(2), 191-203.*  
> [DOI: 10.1016/S0025-5564(03)00091-9](https://doi.org/10.1016/S0025-5564(03)00091-9)

For further details, please refer to the full [report](REPORT.pdf).
