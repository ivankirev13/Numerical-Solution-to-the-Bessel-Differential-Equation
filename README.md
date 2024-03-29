# Numerical Solution to the Bessel Differential Equation

This is a numerical solution to a Sturm-Liouville-type ordinary differential equation using methods from numerical analysis. The file finite_differences_ODE.ipynb is a jupyter notebook with the solution, and the description of procedure is written inside the notebook in markdown cells.

The goal is to solve the linear second order ordinary differential equation, known as the Bessel Differential Equation

x^2 y" + x y' + (x^2 - nu^2) y = 0; 

y(0) = 0, 
y(20) = 1, 
x in [0,20] 

for nu = 1,2,3,4,5,6,7.

This is a boundary value problem and the method used is finite differences.
