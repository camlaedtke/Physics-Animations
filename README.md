# Physics-Simulations

Collection of numerical simulations of different physical phenomena. Some of the scripts are adapted from homework assignments or projects in PHYS/AST 4101: Computational Methods in the Physical Sciences

## Examples


#### Quantum tunneling

Time-evolution of the 1D Schrodinger equation, where a particle (gaussian wave packet) hits a potential barrier with an energy slightly higher than the particle energy. 

![](src/schrodinger_1D.gif)


#### Double slit interference

Time-evolution of 2D Schrodinger equation, where a 2D gaussian wave packet travels through a double slit. Simulated using alternating direction implicit method over a 1024x1024 grid. For all of the plots, the color represents the phase angle between the real and imaginary parts of the equation. 

Visualized in two-dimensions

![](src/schrodinger_2D_1536.gif)


Visualized in three-dimensions

![](src/schrodinger_3D_1024.gif)


#### ResNet function approximator applied to damped pendulum

Demonstrates the use of a one-step residual neural network for data-driven equation approximation. The method aims to be useful for recovering unknown governing equations based only on coarsely distributed observational data of trajectories. It is demonstrated on a dynamical system of a damped pendulum, with a dataset of trajectories generated by an accurate ODE solver. Animation shows the model's predictions on a sample data point at each epoch of training. 

![](src/resnet_training.gif)


#### Monte Carlo simulation of ising model

Monte Carlo algorithm is used to simulate the equilibrium distribution of the Ising model in two dimensions. 

![](src/ising_mc.gif)


#### Molecular dynamics simulation

Simulation of particles that interact using a Lennard-Jones potential.

![](src/molecular_sim.gif)


