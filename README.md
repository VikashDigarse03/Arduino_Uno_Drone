# Arduino Based Drone 🚁

This project is a quadcopter drone built using **Arduino Uno as the flight controller**. It demonstrates basic drone flight control, sensor integration, and stabilization using low-cost hardware.

## Features
- Arduino Uno based flight controller
- MPU6050 IMU for orientation and stabilization
- Brushless motors controlled using ESCs
- Manual control using a 6-channel transmitter and receiver
- Basic PID based stabilization

## Hardware Used
- Arduino Uno  
- MPU6050 IMU sensor  
- 4 × 1000KV BLDC motors  
- 4 × 30A ESC  
- 8 inch or 10 inch propellers  
- 6-channel transmitter and receiver  
- 3S LiPo battery  
- 450mm drone frame  

## Working
The MPU6050 measures the drone's orientation and motion. The Arduino processes this data and uses PID control to stabilize the drone by adjusting motor speeds through ESCs. The drone can be controlled manually using a transmitter.

## Applications
- Learning drone flight control
- Embedded systems projects
- Robotics experimentation

## License
This project is open-source and free to use for learning and educational purposes.
