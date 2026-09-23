# PINNs-2D-geometry
Python/Colab code for generating 2D solid geometries for PINN simulations.

## Overview
This project provides a flexible framework for creating 2D geometries with customizable dimensions, grid resolution, and coordinate scales.
The generated geometries are intended to serve as computational domains for different simulastion approaches, including:

- Physics-Informed Neural Networks (PINNs)
- Finite Element Merhod (FEM)
- Computational Fluid Dynamics (CFD)
- Other numerical and computational engineering simulations

The main purpose of this repository is to provide a simple and adaptable starting point for preparing computational geometries before applying the corresponding numerical or physics-based simulation methods.

---

## Features
### 1. Customizable Geometry Dimensions
The geometry dimensions can be modified according to the requirements of the simulation.
Examples include:
- Nanometer (nm)
- Micrometer (μm)
- Other user-defined scales

### 2. Adjustable Grid Resolution
The number of grid points can be modified depending on the required spatial resolution. Nx=100, Ny=50 or a finer grid Nx=500, Ny=250, higher grid resolution can be used when a more detailed representation of the computational domain is required.

### 3. Flexible Computaional Domain
The current development focuses on 2D computational domains, with future development including more complex geometries.

---

## Technologies
The project is primarily developed using:

- Python
- Google Colab
- NumPy
- Matplotlib

Additional libraries may be added depending on future simulation requirements.

## Motivation
This project was developed as part of my interest in computational modeling, numerical simulation, heat transfer, and Phsics-Informed Neural Networks (PINNs). 
The goal is to developed a reusable geometry-generation framework that can be adapted to different physical scales, geometries, and simulation methods. 
The same computational domain can potentially be prepared for different numerical approaches, allowing geometry generation to become a reusable part of the simulation workflow.

## Author
M. Adila Amarta, Materials and Mettalurgical Engineering

Areas of interest:

- Physics-Informed Neural Networks (PINNs)
- Computational Modeling
- Heat Transfer
- Finite Element Analysis (FEA)
- Computational Fluid Dynamics (CFD)
- Thermal Analysis
- Materials Engineering
- Numerical Simulation
