# LudovaTech-robotics-project

This is the robotics project I worked on in high school as captain of the robotics team. It consists of building two small autonomous robots designed to play soccer against another team of two robots.


## **Details of the project:**

[Video demonstration](https://youtu.be/_eiEAFdv0b4?si=FcbZjqLqs41bY-pg) of how the robot works.  
Additional videos available on the [LudovaTech YouTube channel](https://www.youtube.com/@LudovaTech). 

Details of the repository:
- robot-code: Main C++ code of the robot on the Teensy 4.1 microcontroller.  
- camera-code: Image recognition Python code on the OpenMV camera.
- LudovaTech poster: Overview of the project and inner workings of the robot (graphic design courtesy of @D'Artagnant).

[Google Drive](https://drive.google.com/drive/folders/1Y74dZfu8a425qoM3rjbtKIES4N7hrRu5): images taken during the development of the project.


## **What I worked on:**

**Electronics**
- PCB design: Worked on the schematic and routing of the main PCB and the power board on EasyEDA, and soldered components on the PCBs.
- Battery management: Handled LiPo battery safety measures during operation and charging, and harnessed the battery wires.
- Actuators and sensors: Tested and implemented the motors, solenoids, LIDARs, and cameras into the robots. Worked on data communication systems (digital, analog, PWM, UART).
- Assembly: Assembled the structural parts and PBCs into the robot.

**Programming**
- Main code: Tested the implementation of the main code into the robot in real-life, and coded part of the robot's movement system in C++.
- Camera code: Coded the ball and goal recognition algorithm in Python, and data communication between the camera and the Teensy microcontroller.
- Positioning system: Coded the positioning system of the robot in C++, by analyzing LIDAR data and extrapolating the position of the robot inside of the soccer field.

**Design and Manufacturing**
- CADing: 3D modeled the robot's structural parts on FreeCAD, and optimized the physical organization of parts to facilitate the manufacturing process.
- Manufacturing: 3D printed PLA and ABS parts using UPBOX and Creality K1, and laser cut acrylic parts using Trotec Speedy 100.
