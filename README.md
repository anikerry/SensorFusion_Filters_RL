
# Reasoning and Decision Making under Uncertainty
# Portfolio 2 - Sensor Fusion

**Name:  Aniket Dattatraya Kulkarni**

**Matriculation Number: 5123739**

**Email ID: aniketdattatraya.kulkarni@study.thws.de**


# Portfolio Exam 2: Sensor Fusion – Kalman and Particle Filter

This repository contains the solutions for Task P2.1 and Task P2.2 of the Portfolio Exam 2 for the course "Reasoning and Decision Making under Uncertainty" at the Technical University of Applied Sciences Würzburg-Schweinfurt.

## Contents

- `Aniket_P2_1.ipynb`: Python script implementing the Kalman Filter for simulating a ball-throwing example.
- `Aniket_P2.2.ipynb`: Python script implementing the Particle Filter for simulating two balls flying simultaneously.
- `README.md`: This file.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- Scikit-learn

You can install the required libraries using pip:

```bash
pip install numpy matplotlib scikit-learn


Task P2.1: Kalman Filter
Description
The task is to implement a Kalman Filter for simulating the trajectory of a ball. The Kalman Filter estimates the position and velocity of the ball from observed erroneous positions over time.

Features
Simulation of the ball trajectory with parameters such as launch position, launch speed, and launch angle.
Parameterized observation uncertainty and variable time steps between observations.
Handle observations with dropouts.
Adjustable initial parameters and noise covariance matrices for the Kalman Filter.
Usage
Run the script to simulate the ball trajectory and visualize the results:



Task P2.2: Particle Filter
Description
The task is to implement a Particle Filter for simulating the trajectories of two balls flying simultaneously. The Particle Filter estimates the positions and velocity vectors of the balls from observed erroneous positions over time.

Features
Simulation of the trajectories of two balls with variable time steps and observation dropouts.
Parameterized initial states and noise parameters.
Handling of multiple balls and estimation of their positions and velocities.
Usage
Run the script to simulate the trajectories of two balls and visualize the results:

Visualization
Both scripts provide graphical visualizations of the simulated trajectories and the estimated positions using Matplotlib. The results include plots of the noisy measurements, the true trajectories, and the estimated trajectories.

Author
Aniket Kulkarni

License
This project is licensed under the MIT License - see the LICENSE file for details.