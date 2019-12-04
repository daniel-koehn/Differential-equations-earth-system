# Differential Equations in Earth Sciences: 1D Diffusion

In this module, I introduce a finite-difference based approach to solve the 1D diffusion equation and apply the code to solve two problems related to earth sciences

## Lecture 5: 1D Diffusion

### [Lesson 1](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/05_Diffusion_1D/01_Diffusion_1D.ipynb): 1D Diffusion
 
In this lesson, we learn how to solve the 1D diffusion equation using the FTCS finite-difference scheme and animating the time evolution of the 1D diffusion equation solution.

### [Lesson 2](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/05_Diffusion_1D/02_Heat_Equation_1D_Explicit.ipynb): 1D Heat Conduction

This lesson develops a 1D heat-conduction problem and its solution by means of a forward-time/centered-space scheme. It discusses in detail Dirichlet and Neumann boundary 
conditions, looking at their implementation in code. At the end, it touches on boundary condition and time step limits with explicit schemes.

### [Lesson 3](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/05_Diffusion_1D/03_Heat_Equation_1D_periodic_heating.ipynb): 1D Heat Conduction Example I: Diurnal periodic heating of a half-space

In the last notebook we discussed different types of boundary conditions, like the Dirichlet condition (fixed values at the boundaries) or the Neumann condition (fixed gradient values at the boundaries). 
In this exercise we will apply a diurnal periodic heating as boundary condition to compute the temperature distribution in the near surface soil down to a depth of 1 m.

### [Lesson 4](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/05_Diffusion_1D/04_Heat_Equation_1D_cooling_halfspace.ipynb): 1D Heat Conduction Example II: Cooling of a half-space

In this exercise we will focus on another problem in geophysics, which can be described by the 1D heat conduction equation: the cooling of a half-space. By solving this problem, we can understand the 
generation and cooling of the oceanic lithosphere on earth.

## Copyright and License

(c) 2019 D. Koehn, based on (c) 2014 L.A. Barba, G.F. Forsyth, C.D. Cooper [CFD Python](https://github.com/barbagroup/CFDPython). All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
