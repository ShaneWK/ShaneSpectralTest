# ShaneSpectralTest
A repository containing a general implementation of the spectral test for Linear Congruential Generators (LCGs), a batch evaluation framework for many generators, and a 3D visualization tool for lattice structures.

# Overview
This repository contains the core code for Deliverables 1–3 of my DSoR project.
It implements the spectral test for LCGs using geometry‑of‑numbers techniques, including:

lattice construction for s‑dimensional tuples

LLL reduction

shortest‑vector extraction

Tezuka‑normalized spectral score computation

The repository also includes an interactive 3D visualization tool for exploring lattice structures and illustrating geometric differences between good and bad generators.

# Contents
## Spectral Test Implementation

Construction of s‑dimensional LCG lattices

LLL reduction (NumPy/SymPy‑based)

Shortest‑vector extraction

Spectral score evaluation

Jupyter notebook demonstrating the full pipeline

## LCG Batch Evaluation
Database of 50+ LCG configurations

Automated spectral‑score computation

Comparative analysis across generators

## 3D Lattice Visualization
Interactive Plotly‑based visualization

Exploration of geometric structure in 3D

Demonstrations of good vs. bad LCG behavior

Useful for presentation screenshots and conceptual explanation

# How to Use This Repository
Run the included Jupyter notebooks to explore the components of the spectral test:

Spectral Test Notebook — compute spectral scores for sample LCG parameters

Batch Evaluation Notebook — evaluate many LCGs automatically

3D Visualization Notebook — interactively explore lattice geometry

Each notebook is self‑contained and can be executed in any standard Python/Jupyter environment.

License
MIT License
