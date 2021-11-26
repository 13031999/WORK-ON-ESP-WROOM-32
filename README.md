# WORK ON ESP-WROOM-32
ESP-WROOM-32 is the chip used in ESP-32.
This file includes Eagle CAD schematic circuit design along with the PCB design and the Arduino IDE program file.
In order to make your own ESP-32 board follow these steps:
 1) Connect the chip with various electronics on GPB in order to program it.
 2) Follow the Eagle CAD file to understand the connections.
 3) After the connections are done, use the attached Arduino file (opens in Arduino IDE software) to code the chip.
 4) After pressing 'upload' button in Arduino IDE, follow these steps while the code is uploading:
     A) Press 'Reset' button and 'Flash' button together.
     B)Release the 'Reset' button first and then release the 'Flash' button.
     The code will start getting uploaded on the chip.
Consequently the LED will start blinking.
  
