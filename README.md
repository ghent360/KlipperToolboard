# Huvud 3D Printer toolhead board
This is a simplified version of the KilipperBoard started by bondus(https://github.com/bondus/KlipperToolboard). The goal is to make the board as cheap as possible. Removed the CAN interface, since I believe USB is more practical.
# Original author words
A very small 3D printer board for use on a direct drive toolhead. It is designed to be used with Klipper firmware. Klipper has the awesome feature to be able to use multiple MCUs connected to the host over a (relatively) high latency connection.

![Image of Board](doc/050_small.jpg)

Features: 
* One TMC2209 stepper driver for the extruder
* Two MOSFETs for fans
* One big MOSFET for the hotend heater
* Thermistor input
* Support for an endstop (or filament runout sensnor)
* STM32F103 72Mhz 32bit ARM MCU
* USB, for flashing firmware

Main power is 12-24V. 24V is preferred to keep the currents low

All done in KiCad and open source. 

If you are interesting in helping out, testing or eventually using this board feel free to contact me at ghent360@iqury.us.

### Documentation

* [Pinout and hook up](doc/pinout.md)
* [Klipper configuration](doc/klipper.md)
* [Prototype versions of the board](doc/versions.md)



