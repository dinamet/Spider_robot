# Spider Robot - Arduino Robotics Project

## Project Description:

This project is a four-legged Spider Robot, each leg equipped with three SG90 servo motors (12 in total).
The robot’s body is custom-designed and 3D-printed, and movement is controlled through Bluetooth using the HC-05 module.
By sending commands from a smartphone or computer, the robot can walk, move its legs, and perform basic motion sequences.

This project demonstrates skills in robotics, servo control, embedded programming, wireless communication, and mechanical design.

## Project Purpose and Outcomes:

The main goal of this project was to design and build a fully functional walking robot using Arduino.
### Key outcomes:

- Successful control of 12 servos via PCA9685

- Stable 3D-printed mechanical frame

- Wireless Bluetooth control using HC-05

- Ability to walk forward, backward, and perform basic movements

- Understanding of servo kinematics and robot balance

- Clean modular Arduino code used in real hardware

## Components Used:

- Arduino Uno + USB cable
  
- 7.4V external power supply (2 batteries in series)

- XL4015 DC-DC adjustable voltage step-down module with digital display

- PCA9685 – 16-channel servo driver

- SG90 servo motors – 12 pcs

- HC-05 Bluetooth module

- 3D-printed custom frame

- Jumper wires

# Project Setup

## 1. Wiring

- Connect all 12 SG90 servos to the PCA9685 driver

- Power servos with the 7.4V battery → XL4015 → PCA9685 V+

- Arduino powers the logic side of PCA9685 (VCC + GND)

### HC-05:

- TX → Arduino RX

- RX → Arduino TX

- VCC → 5V

- GND → GND

Make sure all grounds (Arduino, PCA9685, power module) are connected together.

# Instructions for Running the Project
## 2. Software Setup

### 1) Install the required libraries:

- Adafruit_PWMServoDriver

- Servo (if used)

### 2) Upload the Arduino code from this repository

### 3) Turn on the external power supply

### 4) Connect to HC-05 using a Bluetooth terminal app (Android/Windows)

- Default password: 1234

### 5) Send movement commands (examples):

- "F" – walk forward

- "B" – walk backward

- "L" – rotate left

- "R" – rotate right

# How to Replicate This Project

### To fully recreate this robot:

1) Print the frame using the included STL files

2) Assemble 12 SG90 servos into the legs and body

3) Wire everything using the wiring diagram

4) Flash the Arduino code

5) Install the Bluetooth control app

6) Power the robot using two 3.7V Li-ion batteries (7.4V total)

7) Adjust voltage on the XL4015 to power the servos safely (typically 5–6V)

# Project Outcome Summary

### The Spider Robot successfully demonstrates:

- Full servo control using PCA9685

- Stable walking motion

- Bluetooth-based remote control

- A complete robotics workflow: design → print → wire → program → test

- Understanding of basic quadruped locomotion

- This project can be expanded with gait algorithms, sensors, or autonomous movement in the future.



# Our progress

Spider leg assembly

![image spider 1](https://github.com/user-attachments/assets/d3acd0db-35a2-41e2-9b97-c8a5c4930b0d)


Preparation for assembly

![image spider 2](https://github.com/user-attachments/assets/2710ccf6-e0f6-40ba-852b-422f935ce88c)


Spider body assembly

![image spider 3](https://github.com/user-attachments/assets/68f7bd75-05b1-4985-bfe0-e210ffdd56aa)


We have some problems with power supply 

![image spider 4](https://github.com/user-attachments/assets/f6a51cbd-bc95-486f-a553-ca844b44c01b)


We connect servo motor to Arduino and power supply using some convenient components 

![image spider 5](https://github.com/user-attachments/assets/5278d28c-e0d4-4e6a-9c5b-8eacfc5c88d5)


![image spider 6](https://github.com/user-attachments/assets/057a007b-f384-4a11-be63-738ac073bc4a)


Loading code of callibration to Arduino Uno and legs of spider takes initial position 

https://github.com/user-attachments/assets/a95fe72d-f8f6-45bc-99b3-0bcea506866f


Adding Bluetooth module to our project

![image spider 7](https://github.com/user-attachments/assets/44a5bf36-5af1-4507-985a-c6796e394008)


Images of Spider Robot with hardware 

![image spider 8](https://github.com/user-attachments/assets/4c45dca8-5c05-433a-bf70-eb7ad7fad1fc)

![image spider 9](https://github.com/user-attachments/assets/35262a11-71b8-4890-ac92-55cb0555bb76)

![image spider 10](https://github.com/user-attachments/assets/d71c31c2-0f4e-4d10-9fc4-73f1746318eb)
