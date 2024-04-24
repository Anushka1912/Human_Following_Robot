# Human_Following_Robot

This project controls a robot using an Arduino board and various sensors and actuators. It includes functionality to move the robot forward, backward, turn left, and turn right based on sensor inputs.


## Introduction

The Arduino Robot Controller utilizes servo motors and DC motors to control the movement of a robot. It incorporates ultrasonic sensors to detect obstacles and adjust the robot's movement accordingly. The robot can move forward, backward, turn left, and turn right based on the sensor readings.


### Components

- Arduino board
- Servo motor
- DC motors
- Ultrasonic sensor
- Motor driver (e.g., AFMotor library)

### Circuit

1. Connect the servo motor to pin 10 on the Arduino board.
2. Connect the ultrasonic sensor's trigger pin to pin A2 and echo pin to pin A0 on the Arduino board.
3. Connect the right sensor input to pin A5 and the left sensor input to pin A4 on the Arduino board.
4. Connect the DC motors to the motor driver, and connect the motor driver to the Arduino board.

### Installation

1. Clone or download the repository.
2. Open the Arduino IDE.
3. Open the `Human_following2.ino` file.
4. Upload the code to your Arduino board.

## Usage

1. Power on the Arduino board.
2. The robot will start moving according to the sensor inputs.
3. Use the ultrasonic sensor to detect obstacles and adjust the robot's movement.
4. Monitor the serial monitor for debug messages.


