# Ordinary Differential Equations in Earth Sciences: 1D (Non)Linear Advection

In this module I introduce different finite-difference based approaches to solve the 1D (non)linear advection equation.

## Lecture 4: 1D (Non)Linear Advection

### [Lesson 1](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/04_Advection_1D/01_Advection_1D.ipynb): 1D (non)linear Advection
 
In the [last lecture](https://github.com/daniel-koehn/Differential-equations-earth-system/tree/master/03_Lorenz_equations#ordinary-differential-equations-in-earth-sciences-the-lorenz-equations), 
we looked into numerical integration methods for the solution of ordinary differential equations (ODEs), using a simplified thermal convection problem - the Lorenz equations. In this module, we 
will study the numerical solution of **partial differential equations (PDEs)**, where the unknown is a multi-variate function. The problem could depend on time, $t$, and one spatial dimension $x$ 
(or more), which means we need to build a discretization grid with each independent variable. We will start our discussion of numerical PDEs with 1-D linear and non-linear advection equations.

### [Lesson 2](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/04_Advection_1D/02_CFLCondition.ipynb): 1D Linear Advection Problem: Stability and CFL condition

This lesson deals with stability and the CFL condition of the finite-difference scheme to solve the 1D linear advection equation, including numerical experimentation and a graphical interpretation 
using the idea of domain of dependence of the numerical scheme.

### [Lesson 3](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/04_Advection_1D/03_Numerical_Diffusion.ipynb): 1D Linear Advection Problem: Numerical Diffusion

In this lesson we discuss another problem related to the numerical solution of the 1D advection equation, known as numerical diffusion. To mitigate this problem different FD schemes will be implemented 
and compared.

## Copyright and License

(c) 2019 D. Koehn, based on (c) 2014 L.A. Barba, G.F. Forsyth, C.D. Cooper [CFD Python](https://github.com/barbagroup/CFDPython). All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
