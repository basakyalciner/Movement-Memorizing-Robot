# Autonomous Robot with PIC Microcontroller: Learning and Replicating 5-Axis Motion


![WhatsApp Image 2023-03-02 at 21 33 34 (2)](https://user-images.githubusercontent.com/56589435/222661237-54ea5c8c-406a-4d55-ba38-0de4b1aa3cff.jpeg)

# Autonomous Robot with PIC Microcontroller: Learning and Replicating 5-Axis Motion

![Robot Image](robot_image.jpg)

## Introduction

This project features an autonomous robot that has the remarkable ability to learn and replicate 5-axis motion. Programmed using the CCS (Custom Computer Services) C compiler, this robot showcases advanced capabilities in memorizing intricate movements and reproducing them with precision. This GitHub repository provides an overview of the project, detailing its design, implementation, and practical usage.

## Motivation

The primary motivation behind this project was to create a highly intelligent and adaptable robot that could record human-controlled motions and later execute them autonomously. By developing a system capable of learning and replicating complex movements, the robot opens up a world of possibilities, ranging from industrial automation to interactive entertainment.

## Hardware Components

1. PIC Microcontroller: Serving as the brain of the robot, the PIC microcontroller is responsible for processing sensor inputs, motor control, and motion calculations.

2. 5-Axis Robot Arm: The robot arm consists of five motorized joints, each offering independent movement capabilities.

3. Sensors: Various sensors, including potentiometers and encoders, are integrated into the robot arm to provide feedback on joint positions during motion.

4. Display Unit: The robot features a display unit, such as an LCD or OLED, allowing real-time visualization of the learning progress and playback status.

## Software Implementation

### Motion Learning Module
The robot can be set into learning mode, during which it records motions performed by a human operator. The sensors gather data from each joint, which is then stored in memory, creating a comprehensive motion profile.

### Motion Replication Module
After successfully completing the learning phase, the robot switches to replication mode. In this mode, it utilizes the stored motion profile to autonomously replicate the exact sequence of movements.

### Motion Playback Control
The robot provides a range of options to control the playback, including adjusting speed, direction, and looping settings. This flexibility enables precise and customized motion replication.

## Usage

1. Clone the repository and install the required dependencies.
2. Connect the robot arm and sensors to the PIC microcontroller following the provided pin configurations.
3. Upload the CCS C code to the PIC microcontroller using a programmer.
4. Power up the robot and initiate the learning mode via the appropriate command or button.
5. Perform the desired motion with the robot arm while the sensors record the joint positions.
6. Stop the learning mode and switch to the replication mode.
7. The robot arm will now autonomously replicate the learned motion.
8. Utilize the playback controls to fine-tune the robot's motion as needed.

## Conclusion

The autonomous robot with a PIC microcontroller showcases an impressive capability to learn and replicate 5-axis motion with exceptional precision. This project demonstrates the potential of combining advanced programming with robotics to achieve intelligent and adaptable automation solutions.



