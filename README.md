# Av-Automation-V1
This project is an Arduino powered RFID sensor door lock. This projects uses two led's, some jumper wires, one Arduino Uno, RFID card, RFID tag, RFID sensor, one Servo motors and two resistors. This projects uses the RFID sensors to read the RFID card, the card number which is provided in the code, using that it allows the servo motor to rotate which opens the lock. If someone uses a RFID card or tag which does not have authorized access to the sensor, it will make the red led blink two times.  If they use the correct RFID card, which has the authorized access. The blue Led blinks 2 times and then the servo motors rotate.

For building this project this is all hardware components used -:
1) RFID Sensor          2) Servo Motor        3) Two Led's       4)Two 1k resistor  
5) 1 breadboard        6) Arduino Uno        7) Some jumper wires
We used some libraries, which were downloaded inside the IDE, and some of them were included in a zip file. All the Arduino code was written in C programming language 
