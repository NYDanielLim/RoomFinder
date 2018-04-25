# RoomFinder








-------For Me---------------
1. To run server "python3 manage.py runserver"
2. leave window open
3.open another and go to right directory with piezo.py and script
4. type "sh script.sh"

-----NOTES-------
The Raspberry Pi computer does not have a way to read analog inputs. It's a digital-only computer

Piezoelectricity (also called the piezoelectric effect) is the appearance of an electrical potential 
(a voltage, in other words) across the sides of a crystal when you subject it to mechanical stress (by squeezing it).
change in stress and strain
senses contact force

With resistor in parallel we create a voltage divider with the 
internal resistance of the piezo device
A voltage divider is a simple circuit which turns a large voltage into a smaller one
A resistor in parallel gives the current somewhere else to go besides the RPi.

piezo has high source impedance so a high value resistor in parallel will reduce the voltage

burden resistor
takes burden of the surge

Minimum input impedance of 1 M ohm. recommended 10 mega ohm

SPI uses 4 separate connections to communicate with the target device. 
These connections are the serial clock (CLK), Master Input Slave Output (MISO), Master Output Slave Input (MOSI) and Chip Select (CS).

The 8-channel part means that it can accept up to 8 different analog voltages, however it can only convert one voltage at any one time. 

 The range of analog voltages is represented as a 10-bit number on the output. 
If the ADC is measuring voltages from 0-3.3V, each step in the output value represents a change of .003 volts. 

