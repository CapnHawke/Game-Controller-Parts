# Arcade Joystick RGB LED board

## Attribution

The following text must be included in any distribution of derivatives of this file. All Links must also be included.

Copyright 2024, 2026 [Hawkeye](https://github.com/CapnHawke)

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

If you remix or modify this design, please include a change log and list any changes you make.



## Change Log

May 12, 2026

Two new versions of this board have been added. There is a version 1.1.4 and a version 1.1.8.



Changes in v 1.1.8:

* The silk screen has been updated to make identification of the different pins on each JST connection easier. Each of the pins is now labeled "GND", "DATAIN", "DATAOUT" or "5V".
* "Frame Perfect" logo has been removed and the text "mod your stick" has been added.
* Compared to v. 1.0, the traces and components are in the same places and have the same physical location and properties.
* This board has passed all design rule checks in EasyEda and should be ready for production. Because changes were made to the silk screen only, no change is anticipated in the function of this board compared to v 1.0, which is tested and works.



Changes in v 1.1.4:

* The silk screen has been updated to make identification of the different pins on each JST connection easier. Each of the pins is now labeled "GND", "DATAIN", "DATAOUT" or "5V".
* "Frame Perfect" logo has been removed and the text "mod your stick" has been added.
* The number of LEDs on the board have been reduced from eight to four. Compared to v. 1.0, the traces have been redrawn and the placement and orientation of the four remaining LEDs and attached capacitors has been changed.
* This board has passed all design rule checks in EasyEda and should be ready for production. However, it has not been tested by the designer. Your use of these files is subject to assumption of risks associated with the license and with the disclaimers posted in this repository.



May 13, 2026

Two new versions of this board have been added. There is a version 1.2.4 and a version 1.2.8.



Changes in v 1.2.8:

* The silk screen has been updated to add the Open Source Hardware logo.
* Compared to v. 1.1.8, the board outline has been redrawn and the three-pin JST connectors have been moved away from the rectangular footprint on the PCB. This will accomplish two things: First, it allows the LED board to sit flush on top of the lever mounting plate without the through-hole pins contacting the lever's mounting plate.  Second, it eliminates the need for a spacer or an air gap, thus reducing the overall height added and simultaneously preventing electrical shorts which could have previously been possible due to contact between the pins and the metal lever mounting plates. 
* This board has passed all design rule checks in EasyEda and should be ready for production. Small changes were made to the traces leading to each of the board connectors. Files are provided without warranty. If you choose to use them, you assume associated risks. 



Changes in v 1.2.4:

* The silk screen has been updated to add the Open Source Hardware logo.
* Compared to v. 1.1.4, the board outline has been redrawn and the three-pin JST connectors have been moved away from the rectangular footprint on the PCB. This will accomplish two things: First, it allows the LED board to sit flush on top of the lever mounting plate without the through-hole pins contacting the lever's mounting plate.  Second, it eliminates the need for a spacer or an air gap, thus reducing the overall height added and simultaneously preventing electrical shorts which could have previously been possible due to contact between the pins and the metal lever mounting plates.
* This board has passed all design rule checks in EasyEda and should be ready for production. Small changes were made to the traces leading to each of the board connectors. Files are provided without warranty. If you choose to use them, you assume associated risks.



## Summary

This RGB LED board was designed for use with the following:

* GP2040-CE gamepad firmware.
* Japanese style arcade levers such as Sanwa JLF, JLX, Seimitsu LS-40, Seimitsu LS-70x, etc.

Depending on the selected version, these LED boards host a set of either four or eight WS2812 addressable RGB LEDs, which can be assigned to light up at the same time that the up, down, left and right cardinal direction switches are pressed on your joystick.



Included is a CPL, a BOM, and a Gerber production file. If you want to make changes to the design, .json and .svg files have been exported from EasyEda. EasyEda is recommended to view and edit the .json file, to ensure that all data is retained in its native format.

