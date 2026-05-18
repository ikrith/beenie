# Project Beenie!

A long-term project focused on the development of a modular quadcopter flight-control system from scratch.

This project began rather spontaneously — with an STM32 board lying around, an old quadcopter built on a SpeedyBee F405 flight controller, another Pixhawk-based setup, and a random evening thought of trying to build something meaningful with them instead of letting the hardware sit unused.

What started as curiosity about hover stabilization and flight logic gradually evolved into a larger goal: understanding how modern quadcopters achieve stable and autonomous flight, from the lowest embedded-control layers to higher-level autonomous behavior.

The project begins with foundational control-system development, including hover stabilization and altitude hold, and will gradually expand toward:

- Attitude stabilization
- Sensor fusion
- State estimation
- Autonomous flight modes
- Embedded STM32-based firmware
- Real-world flight testing

## Objectives

- Understand the fundamentals of quadcopter flight dynamics and control systems
- Develop and test stabilization algorithms incrementally
- Explore embedded systems programming using STM32-based hardware
- Learn sensor interfacing, filtering, and state estimation techniques
- Build a modular and extensible flight-control architecture
- Document the engineering and learning process throughout development
- Progressively move from simulation and testing toward real-world autonomous flight

The primary goal is not just to build a working drone, but to figure out and implement (hopefully) a complete flight-control pipeline, from low-level embedded systems and control loops to higher-level autonomous behaviors. 
