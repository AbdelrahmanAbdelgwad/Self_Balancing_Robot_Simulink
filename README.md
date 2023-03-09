# Self_Balancing_Robot_Simulink

## Description

This project is a simulation of a self-balancing robot using PID control implemented in Simulink. The idea is based on the inverted pendulum concept, where the robot must maintain its balance by continuously adjusting the RPM of its wheels. The simulation uses a feedback loop that measures the robot's angle and adjusts the motor speed to keep the robot upright.

## Prerequisites

To run this simulation, you will need:

- MATLAB installed on your computer
- Simulink and Simscape toolboxes installed in MATLAB

## Setup

1. Download and install MATLAB on your computer.
2. Open MATLAB and navigate to the folder containing the "Self_Balancing_Robot_Simulink.slx" file.
3. Open the "Self_Balancing_Robot_Simulink.slx" file in Simulink.
4. Press "Ctrl + T" to run the simulation.

## Usage

The simulation will run automatically when you press "Ctrl + T". You can adjust the parameters of the PID controller and observe their effect on the robot's behavior. The scope will display graphs of the robot's angle and motor speed over time.

## Future Work

Currently, this simulation assumes that the robot's motors behave synchronously, which may not always be the case in real-world scenarios. In future versions of this project, the motors' asynchronous behavior could be modeled more accurately, or a more sophisticated control algorithm could be implemented to account for this. Additionally, the simulation could be improved by modeling the robot's wheels more accurately, such as using non-prismatic joints to account for the rolling motion of the wheels. Finally, the simulation could be expanded to include other features such as sensor noise or environmental disturbances to make it more realistic.


## Acknowledgements

This project was inspired by the concept of the inverted pendulum and the use of PID control in robotics. Special thanks to the developers of MATLAB, Simulink, and Simscape for providing the tools to create this simulation.

