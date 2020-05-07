# ArduinoProjects

## Mini Security System

### Authenication System

The project simulates the home security system using arduino. It contains a keypad, LCD display, a RFID reader, a green LED, a potentiometer and a servo motor. 

To begin with, the user has to enter a 4 digit number password through keypad and the LCD will display "*" to indicate the number of digit that user has entered. Once a 4 digit number is entered. The system will check if the password entered corresponds to the user predefined one. If it is incorrect, the LCD displays an "ACCESS DENIED" message and prompts user to enter it again. Once the user has given a correct password, "Access granted" will be displayed and user can proceed to scan their RFID card using the RFID scanner. (RFID is not turned on until keypad authentication is done. If the user has used the right RFID card, the green LED will turn on and LCD display the corresponding message and the servo motor will turn on and rotate 180 ( To simulate to opening of a lock).  

### Sonar system 
