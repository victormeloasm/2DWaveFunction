# Wave Function

## Overview

The Wave Function is a MATLAB simulation that models the propagation of waves in a 2D medium. It employs the Courant–Friedrichs–Lewy (CFL) method and Runge-Kutta 4th order scheme to accurately simulate the behavior of wave-like phenomena. The simulation can be used to visualize and study various wave patterns and their evolution over time.

## How It Works

The simulation is based on solving the wave equation, which describes how waves propagate through a medium. The wave equation is given by:

![Wave Function](simulation_video.gif)


where `u(x, y, t)` represents the wave function at position `(x, y)` and time `t`, `c` is the wave speed, and `d^2/dx^2` and `d^2/dy^2` are second derivatives with respect to `x` and `y`, respectively.

The simulation domain is a 2D square region of size `L x L`, discretized into a grid with `N x N` cells. The initial condition of the wave function `u` is specified based on the desired wave pattern.

## Simulation Parameters

The simulation can be customized by adjusting the following parameters:

- `CFL`: The Courant–Friedrichs–Lewy number, which determines the stability and accuracy of the simulation. Lower values provide better stability but may require more computation.
- `T`: The total simulation time. This parameter controls how long the simulation will run.
- `tplot`: The time interval at which the simulation plots the wave pattern.
- `N`: The number of grid cells in each dimension. Increasing this value results in higher resolution but requires more computation.
- `L`: The size of the simulation domain.
- `c`: The wave speed.
- `dx` and `dy`: The grid spacing in the `x` and `y` directions, respectively.
- `xc` and `yc`: The center coordinates of the circular wave source.
- `R`: The radius of the circular wave source.

## How to Use

1. Install MATLAB: Ensure that you have MATLAB installed on your system.

2. Clone the Repository: Clone or download the repository to your local machine.

3. Open MATLAB: Launch MATLAB and navigate to the directory containing the cloned files.

4. Run the Simulation: Open the `RungeKutta.m` script in MATLAB and execute it. The simulation will start running, and you will see the evolving wave patterns displayed in a 3D plot.

5. Video Output: The simulation will generate an MP4 video file named `simulation_video.mp4` in the same directory. This video will capture the entire simulation process and can be viewed later.

6. Customization: Feel free to modify the simulation parameters in the script to explore different wave patterns and behaviors.

## Acknowledgments

The Wave Function simulation is based on the Courant–Friedrichs–Lewy method and the Runge-Kutta 4th order scheme. The code was adapted and extended from existing examples and discussions in the scientific computing community.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for personal and commercial purposes. Please see the license file for more details.

## Contact

If you have any questions, suggestions, or issues related to the simulation or the code, feel free to contact us at [email address] or create an issue on the GitHub repository. We welcome any feedback and contributions to improve the simulation.


