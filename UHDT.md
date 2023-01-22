---
layout: project
type: project
image: img/UHDT.png
title: "University of Hawaii Drone Technologies"
date: 2022
published: true
labels:
  - Robotics
  - Drone
  - Image Processing
  - Software
  - Python
  - UAV
summary: "My team and I are building an autonomous quadcopter that will attend AUVSI SUAS competition. The drone will mimic payload delivery. The drone will fly waypoint to waypoint and then search and area. In the search area, a object detection classification localizaton (ODCL) script will run. Once target are detected the location will be sent to automous python script and the drone will deliver the 5 payloads to each target accordingly."
---
<img width="300px"  src="../img/UHDT_Drone.png"> <img width="300px"  src="../img/Logo.jpg"> <img width="300px"  src="../img/SITL.png">

I am the lead to for the unmanned aerial vehicle (UAV) software subsystem. My subsystem and I work to make sure that the UAV has autonomously functionality. My team and I are building an autonomous quadcopter that will attend AUVSI SUAS competition. The drone will mimic payload delivery. The drone will fly waypoint to waypoint and then search and area. In the search area, a object detection classification localizaton (ODCL) script will run. Once the targets are detected the location will be sent to automous python script and the drone will deliver the 5 payloads to each target accordingly.

## **Autonomous Python Script**
What i contributed to the team was help creating the autonomously Python script. Inside the python script, there is the waypoint navigation, search area waypoint navigation and air delivery . Once the mission completes waypoint navigation it will then search the area, the script will then activate the ODCL script. After the ODCL script has identified the targets location, it will upload the gps coordinates to the air delivery portion of the code and then the drone will fly to the location and drop of the five payloads to its destinaions. After completing the program we ran software in the loop simulations to make sure the script worked properly and did not get out of bounds or miss a waypoint. 

## **Drone Avoidance**
Currently i am creating drone avoidance script so the drone can avoid other UAV in the air.
