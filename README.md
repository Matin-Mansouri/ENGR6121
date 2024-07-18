# Robust PID Consensus-Based Formation Control of Nonholonomic Mobile Robots

This repository contains the MATLAB code, simulation results video, and final report for the project titled \"Robust PID Consensus-Based Formation Control of Nonholonomic Mobile Robots Affected by Disturbances.\" This project was conducted as part of the Master of Engineering program at Concordia University by Matin Mansouri and Sourena Morteza Ghasemi.

## Project Overview

In this study, we introduce a unique controller designed to universally address the challenges of achieving position and orientation consensus in formations of multiple nonholonomic vehicles, represented as differential drive robots experiencing external disturbances. This controller utilizes a straightforward Proportional Integral Derivative (PID) configuration. To comply with the Brockett stabilization theorem for nonholonomic systems, we have integrated a time-varying persistency of excitation term within the angular velocity dynamics. Our approach marks the inaugural solution to the robust formation issue employing a smooth, time-varying controller. Simulation results are presented to substantiate the theoretical aspects of our approach.

## Getting Started

### Prerequisites

- MATLAB R2021a or later

### Running the Code

1. Clone the repository:

   \`\`\`bash
   git clone https://github.com/Matin-Mansouri/ENGR6121.git
   cd ENGR6121
   \`\`\`

2. Navigate to the \`code\` directory and open the \`formation_control.m\` file in MATLAB.

3. Run the \`formation_control.m\` script to perform the simulation. The script will generate plots showing the trajectories of the mobile robots, the consensus of Cartesian positions, and the behavior of input signals.

### Viewing the Results

- The \`results\` directory contains a video (\`simulation_video.mp4\`) demonstrating the final results of the simulation, including the trajectories and formation of the robots.

### Report

- The \`report\` directory contains the final project report (\`FINAL_REPORT.pdf\`). This report provides a detailed explanation of the problem formulation, controller design, simulation setup, results, and conclusions.

## Authors

- **Matin Mansouri** - [matin.mansouri23@gmail.com](mailto:matin.mansouri23@gmail.com)
- **Sourena Morteza Ghasemi** - [sourenaghasemi1997@gmail.com](mailto:sourenaghasemi1997@gmail.com)

## Acknowledgments

This project builds upon the pioneering work by Romero et al. and incorporates concepts from various studies in the field of nonholonomic mobile robots and robust control.

## References

1. Romero, J. G., Nuño, E., & Aldana, C. I. (2023). Robust PID consensus-based formation control of nonholonomic mobile robots affected by disturbances. International Journal of Control, 96(3), 791–799.
2. J Emmanuel Nuño, Antonio Loría, Tonatiuh Hernández, Mohamed Maghenem, Elena Panteley, Distributed consensus-formation of force-controlled nonholonomic robots with time-varying delays, Automatica, Volume 120, 2020, 109114.
3. Brockett, R. W. (1983). Asymptotic stability and feedback stabilization. In R. W. Brockett, R. S. Millman, & H. J. Sussmann (Eds.), Differential geometric control theory. Birkhauser.
4. Tzafestas, S. G. (2013). Introduction to mobile robot control. Elsevier.
5. Shojaei, K., Shahri, A. M., Tarakameh, A., & Tabibian, B. (2011). Adaptive trajectory tracking control of a differential drive wheeled mobile robot. Robotica, 29(3), 391–402.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
" > README.md
