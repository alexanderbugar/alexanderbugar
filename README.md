# Hey, I'm Alex

I'm a computer engineering student at USF. Most of what I work on ends up somewhere around embedded systems, simulation, GPU computing, and numerical methods.

I started programming through game development and eventually got pulled into hardware, embedded systems, and simulation. Lately I've been getting more interested in the parts where those areas start overlapping.

## What I'm working on

- **[N-body simulator](https://github.com/alexanderbugar/n-body-sim)**  
  An old gravity simulator I originally made in high school that I'm now rebuilding in C++ and CUDA. I'm using the direct O(N²) solver to learn more about numerical accuracy, GPU profiling, and eventually Barnes-Hut. The CUDA work is also my introduction to GPU programming before I start using it more heavily for vision and spatial processing.

- **[Flight controller](https://github.com/alexanderbugar/flight-controller)**  
  My STM32H7 flight controller. This is where I've been working with IMUs, barometers, sensor fusion, real-time loops, and the lower-level side of actually controlling a vehicle.

- **[Physics simulator](https://github.com/alexanderbugar/physics-simulator)**  
  A C++ rigid-body and drone physics simulator that I plan to use for testing flight-control behavior without needing to finalize the actual drone frame.

- **[HIL bridge](https://github.com/alexanderbugar/bridge)**  
  A real-time pipeline connecting the simulation to physical embedded hardware over UDP and UART.

## Where it's going

I've wanted my final personal project to combine all of this into one system: a fully autonomous drone built around my own flight controller and software.

The plan is to use a Jetson Nano alongside the flight controller, with 3D LiDAR and visual-inertial odometry for localization, mapping, and navigation without relying entirely on GPS.

The projects above are basically the pieces leading up to that. The flight controller covers the real-time hardware and control side, the physics simulator and HIL bridge let me test the system before putting it in the air, and the CUDA work is my introduction to the GPU side before getting into the vision pipeline, spatial processing, and identifying where the drone is and what is around it.

## What I'm interested in

- simulation and numerical methods
- GPU computing / HPC
- embedded systems
- real-time systems
- robotics and autonomy
- emergent systems

## Tools I use a lot

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/alexander-bugar-0569a0226/) · [X](https://x.com/CascadeNP)
