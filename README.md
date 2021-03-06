# Arduino Boards

This repository contains support for the following SparkFun Arduino-compatible development boards:
* [ProMicro 5V](https://www.sparkfun.com/products/11098)
* [ProMicro 3.3V](https://www.sparkfun.com/products/10999)
* [Fio v3](https://www.sparkfun.com/products/11520)
* [MakeyMakey](https://www.sparkfun.com/products/11511)
* [Digital Sandbox](https://www.sparkfun.com/products/12651)
* [Serial 7-Segment Display](https://www.sparkfun.com/products/11441)
* [ATmega128RFA1 Development Board](https://www.sparkfun.com/products/11197)

Each board will be added as an entry to the Arduino **Tools** > **Board** menu.

![Example image](example.png)

### Installation Instructions

To add this support to your Arduino IDE, simply copy the "sparkfun" folder, and all of its contents, into a "hardware" directory in one of two
places:
* The actual Arduino directory
	* Directory structure example: C:/Program Files (x86)/Arduino/hardware/sparkfun/avr
* Inside your Sketchbook directory
	* Directory structure example: C:/Users/userName/Arduino/hardware/sparkfun/avr

### Cleaning up the Boards Menu

Each entry in the boards list is defined in [boards.txt](https://github.com/sparkfun/Arduino_Boards/blob/master/sparkfun/avr/boards.txt). If you want to de-clutter the menu, you can comment out a board by inserting a `#` at the beginning of each line.

### Notes
	
* **Please note: This will only work under Arduino IDE versions 1.5 and up.**
* Information on compiling and programming the bootloaders can be found in the bootloaders directory.