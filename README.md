# Programmer for EPROM 27 series (16-512) based on Arduino

*You can download the stable version on the "Releases" tab. It guarantees a working version of the source code, compiled by the GUI for Windows and a sketch for arduino.*

Compatible Chips List (not all chips are tested):

 * 27C16 (connects from 3 to 26 leg DIP28 socket)
 * 27C32 (connects from 3 to 26 leg DIP28 socket)
 * 27C64
 * 27C128
 * 27C256
 * 27C512

Before write, check programming voltage in datasheet

## Schematic

Based on the project: https://github.com/bouletmarc/BMBurner

![Schematic](https://github.com/walhi/arduino_eprom27_programmer/blob/master/imgs/sch.png)

PCB Built in KiCAD 7 using through hole components to preserve retro style

## Software

Software for PC written by Qt6.

Functions:

 * Read chip
 * Write chip
 * Verify and check for write (no bits to be set to 1)
 * Programming voltage control (for AVR in TQFP case)

![GUI on Windows 10](https://github.com/walhi/arduino_eprom27_programmer/blob/master/imgs/win.png)

Required Windows 7 or later.

![GUI on Ubuntu Mate](https://github.com/walhi/arduino_eprom27_programmer/blob/master/imgs/ubuntu_mate.png)

## Changelog
### Rev 1.0
Migration of circuit from Eagle

### Rev 1.1
Add support for ID reading and EEPROM Erase
