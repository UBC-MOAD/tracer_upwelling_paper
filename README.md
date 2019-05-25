# tracer_upwelling_paper - Under construction!

This repository contains MITgcm configurations and post processing scripts and notebooks to reproduce the results presented in the paper *The Impact of Locally Enhanced Vertical Diffusivity on the Cross-Shelf Transport of Tracers Induced by a Submarine Canyon* Ramos-Musalem, K. and S.E. Allen, 2019: J. Phys. Oceanogr., 49, 561–584, https://doi.org/10.1175/JPO-D-18-0174.1. It is divided into:

* **experiments** - Data files and modified MITgcm routines for each run.
* **postprocessing** - Notebooks and scripts used to calculate transports, upwelled tracer and water onto the shelf, extracting density and tracer profiles, etc.
* **figures** - Notebooks used to generate the figures presented in the paper.
* **input_files** - All binary files required to rerun the experiments (initial temperature, salinity, tracer concentration, vertical diffusivity, and bathymetry files) 

Some notebooks and scripts require modules from [canyon_tools](https://bitbucket.org/canyonsubc/canyontools/src/09f475f551444184dc76645b2a233de04b9a3bea?at=default).

