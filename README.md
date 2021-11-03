# AMS548

Task 1

a) Translate one of the proteins along the vector connecting center of masses of those proteins.

b) Write a function which calculates coulombic electrostatic energy between two proteins.

c) Write a function which calculates array of gradients (forces) of the electrostatic energy from one protein to another protein.

d) Check that gradient calculation using analytical formula agrees with numerical way of derivative calculation.

e) Tabulate the values of electrostatic energy while moving one of the protein along center of mass.

f) Plot the values of energy as function of distance.

Task 2

a) Calculate PI using Monte Carlo (by integrating area of the circle)

b) Use metropolis monte carlo to perfrom the search with the following energy function
 E= (-0.5x^2-0.5x-0.3)*exp(-|x|)+0.01x^2
 
 ![gif](https://user-images.githubusercontent.com/90792980/140000484-7856c7a0-8150-45bd-9b0e-bbe3081b5479.gif)

  
c) Write Metropolis Monte Carlo search for two proteins. Energy function is in the complex_energy function. The moves should be rotational and translational.
