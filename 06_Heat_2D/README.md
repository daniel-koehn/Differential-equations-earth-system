# Differential Equations in Earth Sciences: 2D Heat Equation

In this module, we discuss a finite-difference based FTCS approach to solve the 2D heat equation

## Lecture 6: 2D Heat Equation

### [Lesson 1](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/06_Heat_2D/01_Heat_Equation_2D.ipynb): 2D Heat Equation
 
In this lesson, we graduate to two dimensions! A 2D heat-conduction problem is described, representing a computer microchip, and is solved with an explicit time integration scheme. 
The lesson covers boundary conditions in 2D and array-storage decisions.

### [Lesson 2](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/06_Heat_2D/02_Optimizing_Heat_Equation_2D.ipynb): Performance optimization of the 2D heat equation finite difference modelling code
 
During the last class, we developed a 2D heat equation FD code. However, if we investigate this "vanilla" Python implementation using a computationally more demanding test problem, 
the runtime performance is quite underwhelming. Therefore, the aim of this lesson is to optimize the performance of the 2D heat equation code with Just-In-Time (JIT) code compilation 
using the Numba package and NumPy array operations.

### [Lesson 3](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/06_Heat_2D/03_Heat_Equation_2D_analytical solution.ipynb): 2D Heat Equation: Comparison between analytical and numerical solution
 
In this module, we developed a finite difference modelling code to solve the 2D heat equation and optimized the runtime performance using Just-In-Time (JIT) compilation. What is still 
missing is a comparison between an analytical and the corresponding numerical solution. This will be the focus of this exercise.

### [Lesson 4](http://nbviewer.ipython.org/urls/github.com/daniel-koehn/Differential-equations-earth-system/tree/master/06_Heat_2D/04_Heat_Equation_2D_thermal_lithosphere.ipynb): 2D Heat Conduction Example: Thermal Structure of the Lithosphere

Time for an earth science related application of the 2D Heat equation. In this exercise you will investigate the thermal structure of the lithosphere subject to a thermal plume impinging 
at the bottom of the lithosphere.

## Copyright and License

(c) 2019 D. Koehn, based on (c) 2018 L.A. Barba, G.F. Forsyth [CFD Python](https://github.com/barbagroup/CFDPython#cfd-python), (c) 2014 L.A. Barba, I. Hawke, B. Knaepen [Practical Numerical Methods with Python](https://github.com/numerical-mooc/numerical-mooc#practical-numerical-methods-with-python).
All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). We are happy if you re-use the content in any way!
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)