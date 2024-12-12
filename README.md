# Simulation Inputs and Parameters for PDMS Benchmark

This repository contains the simulation inputs and parameter files used in the study **"Force-Field Benchmark for Polydimethylsiloxane: Density, Heat Capacities, Isothermal Compressibility, Viscosity and Thermal Conductivity"**. These files are used for running simulations based on the methods and parameters described in the paper.

## Contents

- `input/`: This directory contains the simulation input files (e.g., generation, equilibration, production).
- `param/`: This folder contains the necessary force fields parameter files used in the simulation.
- `README.md`: Usage instructions.

### Simulation Input Files

The input files are required to run the simulations and are organized in the `input/` directory. These include:
- Equilibrium simulation
- Non Equilibrium Molecular Dynamics simulation for thermal conductivity calculation
- Viscosity calculation

### Parameter Files
Force field models include:
- Huang's all-atom model for PDMS
- UA for PDMS
- OPLS-AA
- COMPASS
- Dreiding 

To run the simulation, you may need to reference or modify the parameters in this folder. The specific parameters used in the study are detailed in the paper, and you should ensure that these values are applied to your simulation environment for consistency.

## How to Run the Simulation

`lmp -i system.in`
