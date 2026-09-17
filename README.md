# self-balancing-bot

## Objective
Design and build a two-wheeled self-balancing robot to learn embedded control and robotics.

## Hardware
- Arduino UNO
- MPU6050 IMU
- L298N motor driver
- GA12-N20 500 RPM motors
- 6 Ni-MH Rechargeable cells connected in series, each of 1.2V adding to 7.2V

## Mechanical Design
13-part modular chassis designed in SolidWorks and manufactured using PLA 3D printing.
*The CAD files for the complete assembly has been uploaded in the very same repo, under the name "CAD Files". For the assembly of the chassis, I used M3 bolts of different sizes, and Hex nuts, to accommodate for easier assembly. 

## Control
- MPU6050 for orientation sensing
- PID controller for balance
- Motor speed/direction controlled through L298N Motor Driver

## Current Status
The robot can recover from approximately 15° of initial tilt. Current work focuses on reducing oscillation through controller tuning.
