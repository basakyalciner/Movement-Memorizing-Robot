# Autonomous Robot with PIC Microcontroller: Learning and Replicating 5-Axis Motion


![WhatsApp Image 2023-03-02 at 21 33 34 (2)](https://user-images.githubusercontent.com/56589435/222661237-54ea5c8c-406a-4d55-ba38-0de4b1aa3cff.jpeg)

Introduction
In this project, we developed an autonomous robot capable of learning and replicating 5-axis motion. The robot was programmed using the CCS (Custom Computer Services) C compiler, and it demonstrates the ability to record and reproduce complex movements with precision. This GitHub write-up provides an overview of the project, its design, implementation, and usage.

Motivation
The primary motivation behind this project was to create an intelligent and adaptable robot capable of memorizing human-controlled movements and later executing them autonomously. The robot's ability to learn and replicate intricate motions opens up possibilities for a wide range of applications, including automation, industrial tasks, and interactive entertainment.

Hardware Components
PIC Microcontroller: We used a PIC microcontroller as the brain of the robot to handle sensor inputs, control the motors, and perform motion calculations.

5-Axis Robot Arm: The robot arm consists of five motorized joints, each allowing independent movement.

Sensors: Various sensors, such as potentiometers and encoders, were integrated into the robot arm to provide feedback on joint positions during motion.

Display Unit: A display unit (LCD or OLED) was added to visualize the robot's learning progress and playback status.

Software Implementation
1. Motion Learning Module
The robot can be set to the learning mode, where it records the motions performed by a human operator. During this phase, the sensor data from each joint is collected and stored in memory, creating a motion profile.

2. Motion Replication Module
Once the motion learning is complete, the robot can switch to the replication mode. In this mode, it utilizes the stored motion profile to recreate the exact sequence of movements autonomously.

3. Motion Playback Control
The robot offers options to adjust playback speed, direction, and looping settings. This flexibility allows for precise and customized motion replication.

Usage
Clone the repository and install the required dependencies.
Connect the robot arm and sensors to the PIC microcontroller following the pin configurations.
Upload the CCS C code to the PIC microcontroller using a programmer.
Power up the robot and start the learning mode by using the appropriate command or button.
Perform the desired motion with the robot arm while the sensors record the joint positions.
Stop the learning mode and switch to the replication mode.
The robot arm will now replicate the learned motion autonomously.
Utilize playback controls to adjust the robot's motion as desired.
Conclusion
Our autonomous robot with PIC microcontroller has demonstrated an impressive capability to learn and replicate 5-axis motion accurately. This project showcases the potential of integrating advanced programming with robotics to achieve intelligent and adaptive automation solutions.


