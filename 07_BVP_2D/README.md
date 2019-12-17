# Differential Equations in Earth Sciences: 2D Boundary Value Problems

This course module is dedicated to the solution of elliptic PDEs, like the Laplace and Poisson equations.
These equations have no time dependence and the solutions can be found by iterative schemes, where an 
initial guess is relaxed to the steady-state solution.

## Lecture 7: 2D Boundary Value Problems

* [Lesson 1](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/07_BVP_2D/01_2D_Laplace_Equation.ipynb) 
introduces the five-point discrete Laplace operator and the Jacobi method. We solve a 2D Laplace problem
with both Dirichlet and Neumann boundary conditions. Via a spatial grid-convergence analysis, we find that the Neumann
boundary conditions needs a second-order difference approximation to get second-order spatial convergence throughout.

* [Lesson 2](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/07_BVP_2D/02_2D_Poisson_Equation.ipynb) 
is dedicated to the Poisson equation: we see the effect of having internal sources with an elliptic equation.
We also learn about algebraic convergence of iterative methods and protest at how slow the Jacobi method is.

* In [lesson 3](https://nbviewer.jupyter.org/github/daniel-koehn/Differential-equations-earth-system/blob/master/07_BVP_2D/03_Iterative_Solvers.ipynb) 
we improve on the Jacobi method: we look at Gauss-Seidel and successive over-relaxation (SOR) schemes.

* [Lesson 4](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/07_BVP_2D/04_Conjugate_Gradient.ipynb) 
focuses on the conjugate gradient (CG) method, perhaps the most popular iterative method.

* [Lesson 5](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/07_BVP_2D/05_BVP_2D_Thermal_Mantle_Convection.ipynb) 
discusses a more complex problem consisting of mutliple coupled Poisson equations: stationary solutions of the 2D thermal mantle convection problem.

## Copyright and License

(c) 2019 D. Koehn, based on (c) 2018 L.A. Barba, G.F. Forsyth [CFD Python](https://github.com/barbagroup/CFDPython#cfd-python), (c) 2014 L.A. Barba, I. Hawke, B. Knaepen [Practical Numerical Methods with Python](https://github.com/numerical-mooc/numerical-mooc#practical-numerical-methods-with-python). All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
