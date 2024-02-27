# Robotic-Hand
Side project to create a robotic hand

## Background
I began this personal project to further my experience in robotics and to explore my interest in robotic prosthetics. The 3-D printed hand was designed in SolidWorks using similar dimension to my own hand for accurate proportions. Utilizing an Arduino Nano on the user's glove and an Arduino Uno on the 3-D printed hand, the robotic hand will mimic the users motions. Two bluetooth modules perform the communication between the Arduinos allowing the user to be at a distance while still operating the hand. The forearm houses the 5 mini servo motors that contract and retract the fingers and thumb. Further development of this project could involve creating a more intricate hand design for a more realistic design with better accuracy and mobility.

## Hand Design
The hand was modeled off of the dimensions of my own hand to create proper proportions and an accurate design. The finger joints are revolute joints held together with pins to allow the finger to contract and retract. Each finger has two lines connected at the tip to the servo tensioners which control the movement of the fingers. The most challenging part of this process is the troubleshooting that occurs when discovering constraints in movement due to interferences in the design. The palm is connected to the forearm by a bracket. Within the forearm, the servo motors are mounted to brackets and spaced accordingly to be space-efficient. There are two string brackets for organization and to minimize contact.

![image](https://github.com/nfmcconnell1212/Robotic-Hand/assets/128636283/78f2f845-ca69-49a8-b626-d8a402684129)
