# Line-following-robot
This project is all about a line-follower-drop-mobile-robot. The working princibles of this line follower drop mobile robot are as the following; when the switch is on, the motor will start to move forward by default. Next, when the IR sensor sense a white line, the motor will turn on and off and that depends on the black line until the end of the track. After finishing the track, the ultrasonic sensor will start functioning and detecting the distance of two obstacles (two walls in our case). Lastly, after the robot reaches the point, the servo motor will turn on and drop the object. The designed mobile robot is a three wheeled Robot with differential steering. The Robot has one servo motor, two Ultrasonic Sensors and two IR sensors. The main controller of the robot is implemented in a PIC microcontroller. The Algorithms runs on the PIC microcontroller are based on the information received by the IR sensors and Ultrasonic Ranger. The type of the microcontoller used is PIC16F877A and the IDE is Microcode Studio. 
