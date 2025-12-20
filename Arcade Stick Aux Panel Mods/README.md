## Attribution

The following text must be included in any distribution of derivatives of this file. All Links must also be included.

Copyright 2024 [Hawkeye](https://github.com/CapnHawke)

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
 - list any changes you make here

## Summary

V3-SA Aux Panel mod is designed as a drop-in solution which can replace the existing panel V3-SA turbo slider panel. This aux panel mod is also compatible with the Hori VX-SA. One variation has six 12mm button holes which are large enough to accommodate 12mm buttons, such as Daiertek buttons available on Amazon.com. There is a window for a 128x64 I2C OLED screen. Other variations are provided with holes sized for MX keyboard switches.

I am also providing PCBs for those who wish to use the MX keyboard switch variety. Please note that there is a TESTED version of the board, which I have personally successfully installed in my own V3-SA and VX-SA controllers. I am also hosting an UNTESTED version of the PCB, which contains only one change from the tested model: It uses a copper fill for the ground instead of connecting ground to a trace. Electrically this should accomplish the same thing, but is perhaps less prone to damage and is more consistent with manufacturing standards. I have no plans to test the files with the ground plane unless the tested versions stop working for some reason.

The screen used for this mod was purchased here: [OLED link](https://www.aliexpress.us/item/2251832770994631.html). It is the "new" style, which has a smaller PCB than the "original" style. Screw holes might not align if a different screen is used.

The screws used to hold the original aux panel in place can be used to hold this replacement aux panel in place. Assembly is as follows: 
1. Remove entire aux panel and turbo slider PCB.
2. Install windowed panel which can be found in the STL/3mf stored in this repository.
3. Screw OLED screen into frame on inner panel using four M2 screws.
4. Place inner panel and OLED screen around the screw posts inside the controller.
5. Screw assembly into place using original aux panel screws.
6. Drop in and affix suitable buttons (either 12mm buttons or MX keyboard switches, depending on panel variation).
7. Wire screen and aux buttons to your encoder.
8. If you wish to use a Cherry MX style aux panel, designs for a printed circuit board have also been uploaded to this repository, which match the switch spacing of the aux panel and will allow for solder assembly. The hosted Gerber file will allow for easy production at JLCPCB, while the hosted .json file can be opened in Easyeda so that modifications to the design can be made. You can order the PCBs through JLCPCB. When I ordered it and tested it, I opted to *not* have any assembly done, and I hand-soldered headers in place. 

## Variations

12mm button Aux Panel: <br>
![HORI V3-SA/VX-SA 12mm button Aux Panel](https://github.com/CapnHawke/Arcade-Addons/blob/main/Arcade%20Stick%20Aux%20Panel%20Mods/Images/V3-SA%20aux%20panel.png)

Cherry MX Aux Panel (flat):<br>

![HORI V3-SA/VX-SA MX switch Aux Panel flat](https://github.com/CapnHawke/Arcade-Addons/blob/main/Arcade%20Stick%20Aux%20Panel%20Mods/Images/MX%20variations/Suggested%20print%20orientation%20flat.png)

Cherry MX Aux Panel (angled screen):<br>

![HORI V3-SA/VX-SA MX switch Aux Panel angled](https://github.com/CapnHawke/Arcade-Addons/blob/main/Arcade%20Stick%20Aux%20Panel%20Mods/Images/MX%20variations/suggested%20print%20orientation%20angled.png)

## Disclaimer
These files and instructions are provided as-is, and without warranty. Your results may vary, and by using these files and instructions, you assume the risks associated with that activity. 