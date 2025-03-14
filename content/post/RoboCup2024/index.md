---
title: RoboCup 2024
summary: My team travels to Netherlands to compeat at ARM RoboCup2024
date: 2024-07-12
authors:
  - admin
tags:
  - Engineering
image:
  caption: 'Entering RoboCup 2024 in the Netherlands'
---

📸 More Photos in [Google Photos Album](https://photos.google.com/share/AF1QipPSmfFeSJJbMU2WLBbBXzbHhqlMcnstHh4q7ZX6bPWX3S9jctF7mmxMBtcpnR7IyA?key=TDhNSV9PeEtPWk1PczRoM2hGb2lEMmJsUks1YmxR)

During the 2024 Summer Semester, I worked with Dr. Juan Rojas to develop robotic manipulation tasks for the Autonomous Robot Manipulation (ARM) Challenge, organized by RoboCup in collaboration with MathWorks and Universal Robots. This project helped me develop crucial skills in ROS, MATLAB, version control, and point cloud processing.  

Our approach divided the workspace into progressively challenging sections:  

```matlab
% Initialize robot connection and configuration
[masterhostIP,UR5eROBOT,initialRobotJConfig,r,optns] = StartRobotWorld("IP-ADDRESS", "UR5e");

% Gray Zone (Easiest)
staticPickAndPlace(optns); 

% Yellow Zone (Medium Difficulty)
PickandPlaceARMChallenge('Zone3', optns);

% Red Zone (Hard)
PickandPlaceARMChallenge('Zone4', optns);

% Blue Zone (Most Challenging)
PickandPlaceARMChallenge('Zone5', optns);
```

{{< youtube zXMk0hsVzh0 >}}

The most memorable achievement was developing our point cloud processing system. We successfully captured accurate 3D environment data, created reliable pick-and-place routines, and enabled the robot to reach target objects consistently. This system allowed our robot to complete its tasks within the environment, showcasing the effectiveness of our basic approach.

Though I couldn't attend in person, my team had a remarkable performance at the Netherlands finals. We placed 3rd overall with a score of 760 out of 780 points, just 20 points behind the 2nd place team. During the competition, we overcame critical hardware and connection issues during setup, ensuring our robot was operational. 

![Photo of Entrance](RoboCup2024-Image2.jpg)


Through this competition, I learned that ROS configuration requires meticulous attention to detail to ensure seamless robot operations. MATLAB's robotics toolbox significantly accelerated our development process by providing robust tools for simulation and control. Implementing version control was crucial in preventing catastrophic errors, allowing us to manage changes effectively and collaborate efficiently. Moreover, real-world testing exposed limitations in our simulations, highlighting the importance of bridging the gap between theoretical models and practical applications.

