Tommy_Pinball_System
====================

A Pinball System based off the Parallax Propeller. Aimed at hobby use.

The Tommy Pinball System is a Parallax Propeller based platform to drive custom pinball machines. It is designed to cover all use cases and be rugged enough to survive prototyping the machine. It features fully optocoupled inputs for the switches and all I/O that comes off the board is ESD protected. 

It is built on a 4-Layer PCB for optimum power and noise immunity. High power solenoid voltage is isolated on the board. 

Lights are done by 8-bit PWM to allow dimming and replicate the ramping of incandescent lights. RGB LEDs for general illumination is supported. Connectors are all locking to ensure reliable connectivity. 

Tommy Pinball System Specifications
CPU:        Parallax Propeller P8X32A-Q44 clocked at 96MHz.
 
I/O:        64 Optocoupled switch inputs.
            32 Mosfets for solenoid control.
            8 Servo Connectors. 
            72 8-bit PWM LEDs. Using WS2803 chips.
            Up to 64  8-bit PWM RGB LEDs for General Illumination. Using WS2801 chips.
            4 12-bit Analog to Digital Channels.
            Standard LED DMD connector. 

Power:      Molex connector for PC PSU.
            Separate connector for Solenoid and Servo Power.

Storage:    Micro SD card slot.
            2 Mbit of SPI SRAM.
            1 Mbit of I2C EEPROM.

Additional: PCB Size is 7"x5" - 4 Layer 
            3 7-Segment numerical LED digits for debugging. 
            USB Serial built in.
            2-channel audio.
            Selectable voltage for LEDs and Servos. 
            All I/O data lines brought out for expandability. 
            Hardware watchdog that will disable solenoid power on event of CPU failure. 

More information can be found on the Tommy project page.

http://longhornengineer.com/pinball/tommy-pinball-system/

Created by:
Parker Dillmann
The Longhorn Engineer

http://longhornengineer.com/

Diclaimer and licensing information can be found below.
http://longhornengineer.com/diy/disclaimer/
