# PS4 Fightstick Touchpad Breakout



## Disclaimer

These files and instructions are provided as-is, and without warranty. Your results may vary, and by using these files and instructions, you assume the risks associated with that activity.



## Board Renders

!\[Front and Back](https://github.com/CapnHawke/Arcade-Addons/blob/main/PS4%20Fightstick%20Touchpad%20Breakout/Assets/PCB%20Quote%20Preview.png)



!\[3d Assembled view](https://github.com/CapnHawke/Arcade-Addons/blob/main/PS4%20Fightstick%20Touchpad%20Breakout/Assets/3d%20Render.png)



## Purpose

The purpose of this board is to convert the ribbon connectors on touchpads in PS4 era fightstick controllers into a pitch spacing that is a little easier to work with. Using the files provided, you can make a PCB through JLCPCB that breaks out a 7 pin ribbon cable into either JST PH 2.0 pitch spacing, or 2.54mm pitch spacing for standard pin headers.  



Although this product was originally made for a HORI RAP 4 Kai, it has been confirmed to work with the RAP 4 Kai as well as a handful of other controllers. Notable controllers include a Victrix Pro FS with a touchpad, and a Madcatz TE2+. Based on initial testing, I am optimistic that there will be compatibility with other PS4 era fightstick controllers that have touchpads.



The purpose of this board is simply to break out existing connections. Accordingly, there is no predefined net and no pin connection guide. Whatever goes in is what comes out, and in the preserved pin order. 



If you are making modifications to your controller, you are encouraged to work with a multimeter and to follow precautions. So far, in all applications where this board has seen use, pin 5 has corresponded to the TPAD Button and pin 1 has corresponded to GND. 



For production and PCB Assembly, it should be okay to just go with JLCPCB defaults. You can leave off whichever connectors you don't want to use, if you opt for PCB Assembly.



Production files including the Gerber, BOM, and Pick and Place (AKA the CPL) are located in the appropriately marked folder in this repo.



## OSHW Statement

This board was created in EasyEDA Standard. It has been exported in its native format, and the .json file hosted in this repository (in the folder labeled "design files") is made available for viewing, and free modification. 



My objective in publishing this design is to make it free and open for all to use and modify as they see fit, with no restrictions, either commercially or otherwise. It is intended to comply completely with the conditions for use of the OSHW logo as of the date that these files went live.



Although I would appreciate appropriate credit, feel free to do whatever you want with these files. Do no harm, be good to your neighbor, mod your stick, and support your locals.

