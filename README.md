# SAVER — Surface Autonomous Vehicle for Emergency Rescue

## Overview
As NASA advances the Artemis program and prepares for deeper human space exploration through missions like Orion, astronaut safety during ocean landings remains a critical challenge. The Surface Autonomous Vehicle for Emergency Rescue (SAVER) is an autonomous marine system designed to locate astronauts after contingency landings and deliver emergency survival support. The goal of SAVER is to reduce response time, improve rescue precision, and support mission success through intelligent navigation and real-time environmental awareness.

## Problem
In the event of a launch abort or off-target ocean landing, astronauts may require rapid location and emergency support before traditional rescue teams arrive. Ocean environments introduce visibility challenges, navigation hazards, and delays in locating astronauts. SAVER addresses this gap by autonomously detecting beacons, identifying visual targets, and navigating safely toward astronauts.

## Solution
SAVER is an autonomous surface vehicle capable of:
- Detecting emergency beacon signals
- Navigating toward astronauts autonomously
- Avoiding obstacles using onboard sensors
- Delivering emergency survival resources
- Allowing teleoperation when human intervention is required

The system integrates signal processing, computer vision, and sensor-based navigation to function in dynamic marine environments.

## Key Features
- **Autonomous Navigation:** Maneuvers toward targets using sensor fusion and onboard processing
- **Beacon Detection:** Software-defined radio (SDR) processes 121.65 MHz Tri-Band Beacon signals
- **Computer Vision:** TensorFlow-enabled camera detects and identifies visual rescue targets
- **Obstacle Avoidance:** Ultrasonic sensors assist in safe navigation
- **Teleoperation Mode:** Allows manual control when necessary

## System Components
- Software-Defined Radio (SDR) for beacon signal detection and processing
- TensorFlow-enabled vision system for target recognition
- Ultrasonic sensors for object detection and avoidance
- Autonomous navigation and control software
- Remote teleoperation interface

## Technologies Used
- Python
- TensorFlow
- Software-Defined Radio (SDR)
- Computer Vision
- Sensor Fusion
- Autonomous Navigation Systems

## Impact
SAVER aims to improve astronaut safety and mission resilience by providing a rapid-response autonomous rescue platform capable of operating in uncertain and high-risk ocean environments. By combining AI-driven perception with robust navigation, SAVER contributes to safer human space exploration and contingency planning.

## My Role
- Led software development and system integration
- Implemented AI and computer vision components
- Contributed to autonomous navigation logic
- Collaborated across multidisciplinary engineering teams
- Developed technical plans and coordinated implementation

## Proposal Contents
- Project proposal and technical documentation
- System architecture overview
- Development notes and design considerations
- Supporting research materials

## Acknowledgments
Developed as part of a NASA-led competition focused on advancing autonomous systems for space mission safety and emergency response.
