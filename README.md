# Black-hole-simulation
Interstellar black-hole!(Gargantua) in C++ :)

## Physics & Mathematics

- **Schwarzschild radius:** r_s = (2GM/c^2)
- **Runge-Kutta4** to numerically estimate the trajectory of each light ray
- **Gravitational lensing:** Light bends due to curved spacetime near a massive object.
- **Numerical integration:** Simulating light-ray trajectories using numerical methods.
- **GPU computing:** GLSL compute shaders for simulation calculations.

## Tech Stack

- C++ 
- OpenGL and GLSL
- GLFW, GLEW, GLM
- Git and GitHub

## Project Files

- `GargantuaH.cpp` — Main simulation
- `geodesic.comp` — Compute shader
- `grid.vert` / `grid.frag` — Grid rendering shaders

## Build and working

-The project is currently developed on Windows. Build requirements and instructions will be added as the build process is finalized.

-For the 3D sim:GargantuaH.cpp and geodesic.comp work together to run the simuation faster using GPU, essentially it sends over a UBO(Uniform Buffer Object) and geodesic.comp to run heavy calculations.


## Future Work(IN PROGRESS)

- Improve gravitational lensing
- Accretion disk visualization
- Refine spacetime grid rendering
- Optimize GPU performance

## Acknowledgements

Inspired by and developed while studying [kavan010/black_hole] ,https://github.com/kavan010/black_hole.

*Credit goes to the original author for the reference project.
