# Programmer for EPROM 27 series (16-512) based on Arduino

Forked from https://github.com/walhi/arduino_eprom27_programmer

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

PCB Built in KiCAD 7 using through hole components to preserve retro style

## Software

Software for PC written by Qt6.

Functions:

 * Read chip
 * Write chip
 * Verify and check for write (no bits to be set to 1)
 * Programming voltage control (for AVR in TQFP case)

![GUI on Linux](https://github.com/walhi/arduino_eprom27_programmer/blob/master/imgs/ubuntu_mate.png)

## Changelog
### Rev 1.0
Migration of circuit from Eagle

### Rev 1.1
Add support for ID reading and EEPROM Erase
