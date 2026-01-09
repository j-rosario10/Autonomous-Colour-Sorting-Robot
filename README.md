# Autonomous Color-Sorting Robot

## Overview
Autonomous mobile robot that detects, picks up, transports, and sorts objects by color using onboard sensors and embedded control logic. The system operates without human input after a sound-triggered start.

---

## Objective
Design a fully autonomous robot capable of identifying object color, navigating to predefined locations, and accurately placing objects into designated bins.

---

## Hardware
- EV3 controller
- DC drive motors with encoders
- Motor-driven arm and claw
- Color, ultrasonic, gyro, and sound sensors

---

## Software & Tools
- RobotC (C-based embedded programming)
- Encoder- and gyro-based navigation
- File-based coordinate input for navigation targets

---

## Key Features
- Autonomous color detection and classification
- Coordinate-based navigation with encoder and gyro feedback
- Obstacle-aware approach using ultrasonic sensing
- Modular pickup and drop-off control logic
- Sound-activated system start for safety

---

## System Flow
1. Wait for sound trigger  
2. Navigate to pickup location  
3. Detect and pick up object  
4. Return to home position  
5. Identify object color  
6. Transport to correct bin  
7. Drop off object and shut down

---

## Results
Successfully sorted objects by color with consistent performance under varying lighting and positioning conditions.

---

## Future Improvements
- Vision-based color detection
- Improved navigation accuracy
- Faster pickup and sorting cycles
