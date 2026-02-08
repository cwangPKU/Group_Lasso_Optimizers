# Optimizers for solving Group Lasso Problem

This project focuses on solving the **Group Lasso optimization problem** using various optimization algorithms.  
All implementations are developed using **MATLAB**.

To establish benchmarks and enable comparison, we first solve the problem using professional optimization solvers. Specifically, the following approaches are applied:

## Solver-Based Methods

1. Solving the problem via the **MOSEK** solver using the **CVX** toolbox in MATLAB  
2. Solving the problem via the **Gurobi** solver using the **CVX** toolbox in MATLAB  
3. Directly solving the problem using the **MOSEK** solver  
4. Directly solving the problem using the **Gurobi** solver  

## Algorithmic Methods

Afterwards, we design and implement custom solvers based on classical optimization algorithms, including:

1. **Subgradient Descent** for the original problem  
2. **Proximal Gradient Method** for the original problem  
3. **Fast Proximal Gradient Method (FISTA)** for the original problem  
4. **Augmented Lagrangian Method (ALM)** for the dual problem  
5. **Alternating Direction Method of Multipliers (ADMM)** for the dual problem  
6. **Augmented Lagrangian Method** for a linearized version of the original problem  

## Notes

The experimental report and complete source code are provided in the accompanying files.  
Feedback, comments, and suggestions are very welcome.

Thank you for reading!
