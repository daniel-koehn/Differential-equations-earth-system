# Differential Equations in Earth Sciences: 2D Thermal Convection in the Earth Mantle

In modules 4-7 of this lecture, we decomposed the general equations for the conservation of mass, 
momentum and energy into different sub-problems:

- (non)-linear advection
- linear diffusion
- Boundary value problems (Poisson equations)

For each problem, we discussed different approaches to compute numerical solutions using the finite-difference 
approach. In the following modules we will assemble the individual problems to more complex differential equations 
related to earth science. We begin with 2D thermal convection in the earth mantle, which includes all problems 
mentioned above.

## Lecture 8: 2D Thermal Convection in the Earth Mantle

### [Lesson 1](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/08_Convection_2D/01_2D_Mantle_Convection_intro.ipynb): 2D Thermal Convection in the Earth Mantle: Introduction
 
We start with a short review of the differential equations governing 2D time-dependent thermal mantle convection and 
discuss the general approach to solve the problem using a finite-difference based approach.

### [Lesson 2](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/08_Convection_2D/02_2D_Linear_Advection.ipynb): 2D Linear Advection Equation
 
In order to solve the 2D thermal mantle convection in the next class, we first have to deal with the 2D advection problem. 
To mitigate the effect of numerical diffusion, we solve the problem by implementing a 2D Marker-in-Cell code based on our 1D implementation from 
[this notebook](https://nbviewer.jupyter.org/github/daniel-koehn/Differential-equations-earth-system/blob/master/04_Advection_1D/03_Numerical_Diffusion.ipynb).

### [Lesson 3](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/08_Convection_2D/03_2D_Linear_Advection_Diffusion.ipynb): 2D Linear Advection-Diffusion Equation

After solving the 2D linear advection problem in the last notebook, we have to add the diffusion equation to the problem. The resulting 2D advection-diffusion 
equation can be solved by separating the diffusion from the advection problem using operator splitting and applying the Marker-in-Cell method to the advection 
problem, while the diffusion problem is solved by finite-differences.

### [Lesson 4](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/08_Convection_2D/04_2D_Thermal_Mantle_Convection.ipynb): 2D Time-Dependent Thermal Mantle Convection Modelling

Finally, we can assemble our 2D time-dependent thermal convection code and compute the evolution of the temperature field for different initial conditions.

## Copyright and License

(c) 2019 D. Koehn, based on (c) 2018 L.A. Barba, G.F. Forsyth [CFD Python](https://github.com/barbagroup/CFDPython#cfd-python), (c) 2014 L.A. Barba, I. Hawke, B. Knaepen [Practical Numerical Methods with Python](https://github.com/numerical-mooc/numerical-mooc#practical-numerical-methods-with-python).
All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
