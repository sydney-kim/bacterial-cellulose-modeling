# Bacterial Cellulose Mathematical Modeling

This repository contains the MATLAB scripts and workspaces used for mathematical modeling of bacterial cellulose synthesis. The modeling is based on the Monod Equation and mass-balance ODEs, and is described in detail Section 3 of the masters thesis "Media Recycling in Bacterial Cellulose Production" (Sydney Kim, Massachusetts Institute of Technology, May 2026). This work was done in MATLAB R2025b.

## Content overview

### `bacterial_cellulose_modeling_1of2.mlx`
This script fits the parameters of the equations to experimental data via parameter estimation (inverse modeling). It is set up to work with the provided workspace, but the concept can be extended to different datasets.

### `bacterial_cellulose_modeling_2of2.mlx`
This script takes the results (parameter values) from the first file, applies them to data with different inital conditions, and evaluates the goodness of fit. It is set up to work with the provided workspace but can be applied to different datasets as with the first script.

### `workspace_6well.mat`
This workspace contains the set of experimental data used in the aformentioned thesis for fitting and analyzing the model performance. It is provided as an example, but the parameters should be fit to experimental data specific to the culture system in use for best results.

## Contributions
This code was written by **Sydney Kim**, with support from the MIT Bioinstrumentation Lab.  
The work was carried out under the supervision of **Professor Ian Hunter**, who provided mentorship, lab space, and equipment.

---

Please feel free to use, adapt, or extend this work. Contributions and feedback are always welcome!
