### 2D Helmholtz Equation in Waveguides Using FDM and Analytical Solutions

This project demonstrates the numerical solution of the 2D Helmholtz equation for various waveguide geometries—rectangular, trapezoidal, circular, and elliptical—using the Finite Difference Method (FDM). For rectangular waveguides, the analytical solution is also provided for comparison and validation.



###### \## Overview

The Helmholtz equation describes how physical fields (e.g., electromagnetic waves) propagate in space. Solving it for different geometries is fundamental in waveguide and photonics research.



In this repository:



->FDM is used to solve the equation numerically for various cross-sectional shapes.



->Analytical results are included for rectangular waveguides for benchmarking the numerical solutions.



->Ready-to-use Jupyter notebooks are provided for each geometry.



Mathematical Formulation



The 2D Helmholtz equation is given by:



∇² u(x, y) + k² u(x, y) = 0



Where:



u(x,y) is the field (e.g., electric or magnetic).



k is the wavenumber (eigenvalue to be found).



Boundary Conditions:

Dirichlet boundary conditions (u = 0 on boundaries) are applied, corresponding to the perfectly conducting waveguide walls.



Rectangular Waveguide Analytical Solution

For a rectangular waveguide of width a and height b:



u\_mn(x, y) = sin(mπx / a) × sin(nπy / b)



k\_mn² = (mπ / a)² + (nπ / b)²

&nbsp;

where 

m,n are mode indices.



###### \## Results \& Visualization

->Each notebook visualizes the computed eigenmodes and compares FDM results with analytical solutions (for rectangular).



->Modes are plotted with clear color maps (typically using jet, where red is 1 and blue is -1).



->Field distributions and eigenvalues for each geometry are displayed.

