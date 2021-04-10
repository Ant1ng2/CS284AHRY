# Title: Smoke Simulation

## Summary: 
In this project, we seek to implement a 2D smoke simulation with different shaders. The implementation should be interactive, which means users can combine different settings to achieve different results. 

## Team Members: 
Anthony Ling, Han Qi, Ruinan Xu, Yuhan Yang

## Problem Description:
We are going to work on the fluid (smoke) simulation. We need to consider what factors affect the look of the smoke using the Navier Stokes equations. The factors we are going to consider involve temperature and concentration of smoke particles. We’re trying to simulate the smoke with different parameters of temperatures, velocities. Besides the normal smoke simulation, one idea we want to implement is dynamic object interaction with the smoke (i.e. a rotating pinwheel in space). 

## Goals and deliverables:
We are trying to create a smoke simulation, with the result being a user interface that contains the results of our work. We want to have a smoke simulation interacting with external objects placed onto the surface, like circular or complex objects (star shape). 

The user interface will be done using OpenGL and be accessible as an executable. This would require finding (or creating) a user interface to be interacted with, then using the Navier-Stokes equations to simulate smoke flow.

We may want to add different shaders as well as adjust the quantities of certain features (Density, Velocity, Temperature, Pressure, Vorticity, Buoyancy, Advection) to make our smoke simulation realistic.

## Schedule:
- Week 1: We will learn about OpenGL and start building the framework of the interactive fluid simulator. 
- Week 2: We will create the basic shader for the simulator to implement the Navier-Stokes equation.
- Week 3: We will add more features to the simulator, such as boundary control and dynamic object interaction. We will also decorate the user interface.
- Week 4: Test the simulator and debug.

## Resources:
GPU Gem: https://cg.informatik.uni-freiburg.de/intern/seminar/gridFluids_GPU_Gems.pdf

A tutorial about fluid simulation : http://users.encs.concordia.ca/~grogono/Graphics/fluid-tutorials.pdf

A detailed implementation using WebGL: https://gamedevelopment.tutsplus.com/tutorials/how-to-write-a-smoke-shader--cms-25587

### Past Smoke simulators:
https://shariewang.github.io/cs184-smoke/docs/

https://github.com/PavelDoGreat/WebGL-Fluid-Simulation

https://rachelbhadra.github.io/smoke_simulator/index.html
