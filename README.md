# Plasma Surrogate Modelling using Fourier Neural Operators

This orgnasiation/folder contains several repositories with the code and experiments for the paper ["Plasma Surrogate Modelling using Fourier Neural Operators"](https://iopscience.iop.org/article/10.1088/1741-4326/ad313a) by Vignesh Gopakumar et al., published in Nuclear Fusion, 2024.

## Overview

The paper demonstrates the use of Fourier Neural Operators (FNO) as surrogate models for predicting plasma evolution in both simulation and experimental domains. Key highlights include:

- A modified version of the FNO capable of handling multiple variables that govern a family of PDEs, allowing for learning and encoding the mutual dependence of variables.
- Demonstration of the FNO's utility in surrogate modelling the evolution of plasma across a range of reduced magnetohydrodynamic (MHD) cases with increasing complexity.
- Application of FNOs to predict plasma evolution on real-world experimental data observed by cameras positioned within the MAST Tokamak.
- Extensive analysis of the FNO's features, including ablation studies evaluating the impact of various hyperparameters and training regimes.
- Comparison of the performance of individual FNOs with the multi-variable FNO.

The FNO offers a viable alternative for surrogate modelling, as it is quick to train and infer, requires fewer data points, and can perform zero-shot super-resolution while achieving high-fidelity solutions.

## Folder  Structure

- `FNO_Isothermal_Blob`: Contains the code and experiments for the FNO in modelling the evolution of an isothermal blob under reduced MHD. 
- `FNO_Single_Blob`: Contains the code and experiments for the FNO in modelling the evolution of a single blob under reduced MHD. 
- `FNO_Multi_Blobs`: Contains the code and experiments for the FNO in modelling the evolution of multiple blobs under electrostatic conditions given by reduced MHD. 
- `results/`: Contains the code and experiments for the FNO in modelling the plasma evolution within the MAST Tokamak as captured by the fast visible camera diagnostic.


Please refer to the paper for more details on the methodology, results, and conclusions.
