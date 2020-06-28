# Automatic Doggy Door Opener

This is a project to create an automatic Doggy Door Opener. The software runs on an ESP32 and is designed to be integrated with home automation systems. The hardware consists of a pneumatic cylinder for opening the door, a solenoid valve for controlling the cylinder, 2 PIR sensors for pet detection, and drawer slides for smooth operation. The hardware will be detailed more below.

This system is designed to prevent my cat from leaving the house while allowing my dog to come and go freely. Several approaches were considered for presence detection, but since there is a large size disparity between my dog and my cat, I think a PIR sensor will work adequately for the task. If this is not the case, I will try swapping out the PIR sensor for a rfid tag. 