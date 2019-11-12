# Ordinary Differential Equations in Earth Sciences: The Lorenz equations

In this module I introduce the finite-difference method to solve ordinary differential equations.

## Lecture 3: Simplified Convection Problem: The Lorenz Equations

### [Lesson 1](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/03_Lorenz_equations/01_LorenzEquations_intro.ipynb): Simplified Convection Problem: The Lorenz Equations

The Lorenz Equations are a 3-D dynamical system that is a simplified model of Rayleigh-Benard thermal convection. They are derived and described in detail in Edward Lorenz' 1963 paper 
Deterministic Nonperiodic Flow in the Journal of Atmospheric Science. The key idea is that the Lorenz Equations result from a severely truncated spectral approximation to the 2-D equations 
for incompressible thermal convection in stream-function/vorticity form. These equations govern the flow of a buouyant incompressible fluid with a temperature dependent density in a layer 
of depth h, that is heated from below and cooled from the top. 

### [Lesson 2](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/03_Lorenz_equations/02_Stationary_solutions_of_DE.ipynb): Stationary Solutions of Time-Dependent Problems

Often, we do not want to compute the whole time evolution of a dynamical problem, but are only interested in stationary solutions, where the system reached an equilibrium state. These stationary solutions are 
estimated by setting all time derivatives in the differential equation to zero. As examples, we will compute the stationary solutions for streamlines from [Exercise: How to sail without wind](https://nbviewer.jupyter.org/github/daniel-koehn/Differential-equations-earth-system/blob/master/02_finite_difference_intro/3_fd_ODE_example_sailing_wo_wind.ipynb) and the Lorenz equations.

### [Lesson 3](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/03_Lorenz_equations/03_LorenzEquations_fdsolve.ipynb): Exploring the Lorenz Equations

We will program some simple python routines for the numerical integration and visualization of the Lorenz Equations and investigate the dynamic of the solutions using the temporal evolution and the phase space 
trajectories.

### [Lesson 4](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/03_Lorenz_equations/04_LorenzEquations_fdsolve_movie.ipynb): Lorenz Equations - The Movie

After all the equations, math, physics, simplifications, programming and visualizations, it is time to finish this lecture with some relaxing movies, showing the time evolution of the 2D temperature and velocity 
vector fields. 

## Copyright and License

(c) 2019 D. Koehn. All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
