This is a sample C program that communicates with a slave device through a serial port. The program reads analog input registers from the slave device and displays the values.

Requirements
Serial library (serial.h)
CRC16 library (crc16.h)
projeto_1.h header file
C compiler
Installation
Download the required libraries and header file and place them in the same directory as the main.c file.
Compile the main.c file using a C compiler.
Usage
Connect the slave device to the serial port of your computer.
Run the compiled executable.
Choose an option from the menu:
Option 1 reads analog input registers from a specified port.
Option 2 reads all analog input registers.
Option 3 sends a frame with the wrong slave address.
Option 4 sends a frame with an invalid function code.
Option 5 sends a frame with an invalid register address.
Option 6 sends a frame with an invalid CRC.
Option 7 calculates the response time of the slave device.
Option 0 exits the program.
If Option 1 or Option 2 is selected, the program will prompt for the port number and the number of ports to read.
The program will display the values of the registers.
Credits
This program was written byVitor Paese De Carli for Project 1 for Project 1 of the Industrial Busbars course.
