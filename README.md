# RK4 Numerical Solver for Stiff Chemical Kinetics ODEs

## Overview
A Python-based numerical solver using the 4th-order Runge-Kutta (RK4) method 
to integrate systems of ordinary differential equations governing chemical 
kinetics. Applied to the Westbrook-Dryer reduced mechanism for methane 
combustion, with a modular structure allowing custom ODE systems to be 
defined and solved using the same RK4 engine.

*Note: This repository is only a preview of some results developed under the custom RK4 numerical solver written with Python language*

## Method
- 4th-order Runge-Kutta (RK4) integration scheme.
- Applied and solved the Westbrook-Dryer reduced mechanism for Methane combustion while accounting for the two-stage behavior of the Westbrook & Dryer reduced mechanism (CO Dropping while CO2 raising).
- Modular design supporting custom ODE system definitions to be solved with the main RK4 solver.

## Results

<p align="center">
  <img src="images/Solved_Westbrook_Dryer_Methane_Combustion_reduced_mechanism.png.png" alt="Solved Westbrook & Dryer Methane Combustion reduced mechanism" width="600">
</p>


<p align="center">
  <img src="images/Custom_chemical_reaction_ODE_mechanism_solved_used_the_RK4_solver.png.png" alt="Custom chemical reaction ODE mechanism solved using the RK4 solver" width="600">
</p>

## Skills
Python · Numerical Methods · Stiff Chemical Kinetics · Combustion Modeling · Scientific Computing
