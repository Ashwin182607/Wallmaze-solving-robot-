# Robot Maze Solver

## Overview
This project involves a line-following robot designed to navigate a maze using ultrasonic sensors and simple maze-solving algorithms.

## Components
- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- DC Motors (2x)
- AA Battery Pack (4x 1.5V cells)
- Motor Driver (L298N)

## Setup
1. Connect the motors to the L298N motor driver.
2. Wire the ultrasonic sensor to the Arduino.
3. Attach the AA battery pack to power the motors and Arduino.
4. Upload the code (`src/maze-robot.ino`) to the Arduino.

## How It Works
The robot uses an ultrasonic sensor to detect line and objects. It follows a basic rule: move forward if there's space, or turn right if it's too close to a wall.

## License
MIT License
