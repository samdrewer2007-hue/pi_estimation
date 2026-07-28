# Monte Carlo pi estimation

## Overview 

This project finds an estimation for pi through a geometric method. In this project I aimed to introduce myself to Monte Carlo simulations, vectorisation using NumPy, and Matplotlib plotting. This simulation demonstrates my learning of the techniques outlined above.

## Theory

To find an estimation for pi the simulation generates N points in a 2x2 square, by randomly picking x and y values between -1 and 1. We can then transcribe a circle of radius 1 centred at the origin onto this plot. As the area of this circle is given  pi*r^2, and the area of the square is 4*r, we find that the proportion of points in the circle provides an estimation for pi/4.

![Simulation diagram and convergence plot](pi_estimation.png)

## Skills Demonstrated

Through this project, I was able to demonstrate a more advanced proficiency with NumPy arrays that my previous level. I also learnt the basics of Boolean masking 