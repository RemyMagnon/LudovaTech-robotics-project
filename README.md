# LudovaTech-robotics-project

This is the robotics project I worked on in high school as founder and captain of the robotics team. It consists of two autonomous robots designed to play soccer against another team of two robots.  

[Google Drive](https://drive.google.com/drive/folders/1gkIxhxm4YXJWOHLKBpufCNScrH6JFMv0): Detailed evolution of the project with images and videos.  
[LudovaTech YouTube channel](https://www.youtube.com/@LudovaTech): Video demonstrations of the robots in action.  


## **Details of the repository:**

- CAD-models: 3D models of the robots, with additional images included.  
- robot-code: Main C++ code of the robots on the Teensy 4.1 microcontroller.  
- camera-code: Image recognition Python code on the OpenMV camera.  
- LudovaTech design document: Detailed technical description of the robots and struggles encountered.  
- LudovaTech poster: Overview of the project and inner workings of the robots (graphic design courtesy of @D'Artagnant).  


## **What I worked on:**

**Electronics**
- PCB design: Worked on the schematic and routing of the main PCB and the power board on EasyEDA, and soldered components on the PCBs.
- Battery management: Handled LiPo battery safety measures during operation and charging, and harnessed the battery wires.
- Actuators and sensors: Tested and implemented the motors, solenoids, LIDARs, and cameras into the robots. Worked on data communication systems (digital, analog, PWM, UART).
- Assembly: Assembled the structural parts and PBCs into the robots.

**Programming**
- Main code: Tested the implementation of the main code into the robots in real-life, and coded part of the robots' movement system in C++.
- Camera code: Coded the ball and goal recognition algorithm in Python, and data communication between the camera and the Teensy microcontroller.
- Positioning system: Coded the positioning system of the robots in C++, by analyzing LIDAR data and extrapolating the position of the robots inside of the soccer field.

**Design and Manufacturing**
- CADing: 3D modeled the robots' structural parts on FreeCAD, and optimized the physical organization of parts to facilitate the manufacturing process.
- Manufacturing: 3D printed PLA and ABS parts using UPBOX and Creality K1, and laser cut acrylic parts using Trotec Speedy 100.


## **What I took from the project:**

When I started doing robotics by myself in middle school, I basically didn't know anything besides Python programming. Needless to say, I was completely clueless. But I slowly figured out things like electronics and manufacturing. I never really had access to advanced components, so I had to work with what I had. I did not become an "expert" in robotics, but I can confidently say that I have become really good at making basic components achieve insane things you didn't even think they could achieve. One of the teams I once played against during competition could not believe that robots as simple as mine could beat their really complex robots.

When I started leading my own team, I also learned what it was like to manage a relatively large scale project. I made sure to distribute tasks and funding properly to make the project advance forward as fast as I could. The "simplify as much as possible" mindset proved to be successful, as we saved a lot of time and money. I don't think we would have completed the project without it. I still made many organizational mistakes, but I just needed to communicate more about what I was doing (and sleep more because I get grumpy way faster when I lack sleep).

Today, even after my departure, the robotics team I built still lives. New members join every year, and learn how to build robots my actually doing it.

