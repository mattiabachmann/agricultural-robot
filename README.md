# Agricultural Robot

**ETH Zurich | Innovation Project | 2025**

## Overview

Development of a small-scale Arduino-based agricultural robot designed to harvest miniature 3D-printed apples and plums, deposit collected objects, and plant onions.

## Robot Demonstration

Photos and videos demonstrating the robot's main functions:

- Harvesting apples and plums

 https://github.com/user-attachments/assets/ee5fcba4-0733-413f-b8f0-1259552bb9d7

- Depositing collected objects

 https://github.com/user-attachments/assets/a861c03e-6746-419a-9272-71887f97d969

- Planting onions

 https://github.com/user-attachments/assets/6dd59d98-ee77-444e-a621-41b08baf0afe

- Autonomous drivetrain control

 https://github.com/user-attachments/assets/541a7f26-2d62-47aa-957c-bb61672bf7a9

## My Contributions

- Implemented and tuned the PID drivetrain controller using Arduino.
- Co-developed the depositing mechanism.
- Contributed to the rack-and-pinion mechanism for harvesting
- Responsible for the team's 3D printing and component fabrication.


## Technical Implementation

### Line Following & PID Control

The robot used a five-channel IR reflectance sensor array (QTR-MD-05RC) for line detection. A PID controller
processed the line-position error and adjusted the motor commands to follow the desired path.

### Mechanical Systems

The harvesting mechanism used a motor-driven rack-and-pinion system with a magnet to pick up the objects containing ferromagnetic inserts. By rotating the mechanism, the robot could directly sort and deposit the harvested objects into two separate containers, eliminating the need for an additional sorting mechanism. Servomotors and DC motors provided actuation, while a Hall-effect sensor was used for further position detection of the rack. 

## Technologies

- **Control & Programming:** Arduino, PID Control
- **Actuators & Electronics:** DC Motors, Servomotors, 5-channel IR reflectance sensor array, Hall-effect sensors for rack position detection
- **Mechanical Design:** Autodesk Fusion 360
- **Manufacturing:** FDM 3D Printing, Rapid Prototyping

## Project Context

Developed as a team project during the Innovation Project course at ETH Zurich.
