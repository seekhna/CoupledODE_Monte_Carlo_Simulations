# CoupledODE_Monte_Carlo_Simulations

Problem statement given at http://cds.iisc.ac.in/wp-content/uploads/CDS_DS_MHRD-STARS_Jul-2020_PA.pdf.

File 1: CoupledODE_Known_Initial_Condition.ipynb solves the Coupled Differential Equation with Initial Conditions as X[0]=Y[0]=Z[0]=1. 
Six time steps (stepsize) are used to demonstrate the effect of step size on the solutions. 

File 2: CoupledODE_Monte_Carlo_Simulation.ipynb solves the Coupled Differential Equation by sampling 10000 random Initial Conditions for 
each X,Y and Z at 4 stepsizes.Results plotted at the end demonstrate the impact of stepsize on solution of differential equation for 10,000 initial conditions.  

References:

https://juanitorduz.github.io/multivariate_normal/

http://cs229.stanford.edu/section/gaussians.pdf

https://towardsdatascience.com/monte-carlo-simulations-with-python-part-1-f5627b7d60b0

https://en.wikipedia.org/wiki/Runge%E2%80%93Kutta_methods

https://stackoverflow.com/questions/54951362/seaborn-jointplot-with-defined-axes-limits

Stackoverflow
