# Drawing Plotter
 ## Problem Statement
 Assembling the 2D plotter which can run with G codes and drawing provided by user with appropriate functioning 
 
 ## Ideation and Planning
 As this project includes 3D printing parts and PCB, the space occupied by it is comparatively smaller but it affects the cost.  
 ###Arranging all the parts: The parts were mentioned are following:
 1.	6mm aluminium pipes (more in step 2),
2.	3m of GT2 belt,
3.	3D printed parts,
4.	screws and nuts (3x M2 12mm, 14x M3 20mm, 6x M4 12mm)
5.	3 stepper motors (28BYJ-48, 5V DC) with drivers (ULN2003),
6.	Micro servo (Tower Pro 9g),
7.	16x2 LCD with I2C converter,
8.	SD card reader,
9.	DC 5,5x2,1mm plug and socket,
10.	5V 2A DC charger,
11.	PCB parts (more in step 4),
12.	wires, goldpins, heat-shrink tubing.
13.	ATMega328P (with Arduino bootloader)
14.	28 pin sockets for AT Mega,
15.	3x 10kΩ resistors (SMD version)
16.	Capacitors: 3x 100nF, 2x 22pF, 1x 10nF
17.	button
18.	16MHz crystal
19.	10uH coil
20.	Gold pins


### The assembling the parts will be following sequence:
1)	Frame
2)	Attaching pulleys and 3D printed parts to frame
3)	Mounting of belt
4)	Electrical connection of motors, motor drivers to PCB and with Arduino
5)	Attaching accessories like display
6)	Uploading the program 
7)	Calibrating


## Pipeline
### Entire project can be divided into three segments:
1)	3D printing
2)	Mechanical assembly
3)	PCB printing
4)	Electrical connections
5)	Uploading G codes and other codes


In order to make base of the printer structural components like pipes and other parts can be purchased or cut very easily. After assembling them with proper screwing (or Welding also may work). The pipes for linearly moving the servos should be straight and accurately cut. The 3D printing can be done with readily made Fusion 360 design and then cured. 
First X axis motor wires are long enough - motor will be close to microcontroller. Second X axis motor will be placed on the other side of plotter, it's cables should be 53cm long. Y axis motor will be moving across all X axis so his cables should be longer than it - 60cm will do the work. Servo will move across all X axis and all Y axis, so it's cables should be longer than these two together - 90cm will be good.

### By arranging all the wiring in one PCB can save the space like anything.
![image](https://user-images.githubusercontent.com/88575247/174485344-39f9c0b5-b5e3-4f1d-82a7-49001d48a541.png)
![image](https://user-images.githubusercontent.com/88575247/174485349-cb78d1d7-7471-4924-a27c-c35491f5670a.png)
Making electrical connections with all the servo motors, connecting a display, power adopts, SMPS, motor drivers, card reader ports etc.
The G code library is available at open source, but before this we have to test and modify according to our requirement. After uploading it is followed by calibration.

## Prototyping phase
The project itself is a prototype and as it involves majority of the parts are 3D printed. After 3D printing, the frame should be fabricated. PCB making is to be followed by assembling. After assembling, all the process similar mentioned above needed to be fooled.
