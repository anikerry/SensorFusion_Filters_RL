# Kalman Filter Implementation for Ball Trajectory Simulation

## Overview
This project implements a Kalman Filter to estimate the position and velocity of a ball based on noisy measurements of its position over time.

## Requirements
- Python 3.x
- NumPy
- Matplotlib

## Installation
Install the required packages using pip:
pip install numpy matplotlib

## Usage
1. Clone the repository.
2. Run the `kalman_filter.py` script.

## Code Explanation
- `KalmanFilter` class: Implements the Kalman Filter.
- `simulate_ball_trajectory` function: Simulates the true trajectory of the ball.
- `add_measurement_noise` function: Adds measurement noise to the trajectory.
- The main part of the script simulates the trajectory, adds noise, and runs the Kalman Filter.

## Visualization
The script generates a plot showing:
- True trajectory of the ball.
- Noisy measurements.
- Estimated trajectory using the Kalman Filter.


# Particle Filter Implementation for Two Balls Trajectory Simulation

## Overview
This project implements a Particle Filter to estimate the positions and velocities of two balls based on noisy measurements of their positions over time.

## Requirements
- Python 3.x
- NumPy
- Matplotlib

## Installation
Install the required packages using pip:
pip install numpy matplotlib


## Usage
1. Clone the repository.
2. Run the `particle_filter.py` script.

## Code Explanation
- `ParticleFilter` class: Implements the Particle Filter.
- `simulate_two_balls_trajectory` function: Simulates the true trajectories of two balls.
- `add_measurement_noise` function: Adds measurement noise to the trajectories.
- The main part of the script simulates the trajectories, adds noise, and runs the Particle Filter.

## Visualization
The script generates a plot showing:
- True trajectories of the balls.
- Noisy measurements.
- Estimated trajectories using the Particle Filter.
