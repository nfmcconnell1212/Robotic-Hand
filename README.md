# Robotic-Hand
Side project to create a robotic hand

## Background
I began this personal project to further my experience in robotics and to explore my interest in robotic prosthetics. The 3-D printed hand was designed in SolidWorks using similar dimension to my own hand for accurate proportions. Utilizing an Arduino Nano on the user's glove and an Arduino Uno on the 3-D printed hand, the robotic hand will mimic the users motions. Two bluetooth modules perform the communication between the Arduinos allowing the user to be at a distance while still operating the hand. The forearm houses the 5 mini servo motors that contract and retract the fingers and thumb. Further development of this project could involve creating a more intricate hand design for a more realistic design with better accuracy and mobility.

## Hand Design
The hand was modeled off of the dimensions of my own hand to create proper proportions and an accurate design. The finger joints are revolute joints held together with pins to allow the finger to contract and retract. Each finger has two lines connected at the tip to the servo tensioners which control the movement of the fingers. The most challenging part of this process is the troubleshooting that occurs when discovering constraints in movement due to interferences in the design. The palm is connected to the forearm by a bracket. Within the forearm, the servo motors are mounted to brackets and spaced accordingly to be space-efficient. There are two string brackets for organization and to minimize contact.

![image](https://github.com/nfmcconnell1212/Robotic-Hand/assets/128636283/78f2f845-ca69-49a8-b626-d8a402684129)
![image](https://github.com/nfmcconnell1212/Robotic-Hand/assets/128636283/c78a097d-61a2-4165-a050-6a1404e5668b)

## Current Stage
Currently, I have the hand-assembled and am working on debugging and troubleshooting the motors and flex sensors. The next step is to begin putting the user glove together and attaching the flex sensors to each hand. Once that is done I will determine the resistance of each finger closed and open to properly assign values to the mapping of the servos. This will give more accuracy on each finger.

![117733647-cacc3480-b1a6-11eb-865d-ec73822f799f](https://github.com/nfmcconnell1212/Robotic-Hand/assets/128636283/c43dbaa3-46d2-4029-81f4-8f8c253dc6b6)
![117733694-d9b2e700-b1a6-11eb-9f6e-a69f86bb72c9](https://github.com/nfmcconnell1212/Robotic-Hand/assets/128636283/6a7e3add-52b2-4ed1-8ffd-cb3adf49b513)

## Next Steps
The future steps of this project involve creating a cleaner wiring design for the glove, implementing batteries for the Arduino and subsystems so they can run independently, and cleaning up the 3-D hand print for a smoother design.
