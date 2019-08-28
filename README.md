# PDEs


The finite differences method was used to solve two partial differential equations, the Poisson and the diffusion equation. The Poisson equation was used to model the potential and electric fields in and between the plates of a capacitor, whereas the diffusion equation was used to plot the temperature distribution along an iron rod placed in a furnace. Different boundary conditions were explored, as well as extending the diffusion model into two dimensions.

This program will be solving the Laplace equation, where ρ = 0 to find the potential V (x, y) in and around a parallel place capacitor. This will be done using an iterative technique, where either the Jacobi or Gauss-Seidel relaxation method can be used.
 

The second partial differential equation to be solved is the diffusion equation. This is an example of an initial value problem where u(x, y, to) is known for an initial time and all position grid nodes, and is then allowed to propagate in time. This can either be modeled using an explicit, Forward Euler scheme, or an implicit, Backward Euler scheme. 
