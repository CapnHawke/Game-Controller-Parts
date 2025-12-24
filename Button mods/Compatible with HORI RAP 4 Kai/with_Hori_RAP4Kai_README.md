## Touchpad Breakout Board

!!!WARNING!!!

These circuit boards were based on another open source design which can be viewed here, called [OSB MX.](https://github.com/OpenStickCommunity/Hardware/blob/main/3D%20Prints/OSBMX%20v2/Legacy%20-%20OSBMX%20v1/README.md) Those files were provided with a number of warnings and disclaimers, all of which also apply to this remix. To summarize, there may be production issues with the PCBs, there may be incompatibilities with certain MX switches, and these files are provided WITHOUT WARRANTY. User assumes all risk including potential damages, if applicable.

!!!WARNING!!!

As of December 24, 2025, these boards are on order from JLCPCB and they have not been tested. No problems are anticipated, but order at your own risk!

---

## Attribution

Due to the size of the individual boards it may be impossible to provide a proper link to the original repo.  As such, please use these extra guidelines:

- A link to this repo on any sales pages for this product or remixes
- If a remix is based on this design, a link to the relevant repo and attribution to CapnHawke in addition to the other required links and attribution.

The following text must be included in any GitHub distributions of derivatives of this board. All links must also be included.

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
  - v1.0 initial design released

If any further changes are made from this remix:
  - list any changes you make here

---

Summary:

This board was made to allow users to make certain modifications to their HORI RAP 4 Kai controllers. The specific purpose of this board is to enable a user to insert the ribbon cable connected to the touchpad in their RAP 4 Kai into an appropriate connector, which is then broken out into a 2.54mm and 2.0mm pitch spacing row of through holes. 

The board design includes a bill of materials and component placement list which will allow users to add JST PH, and/or 1x7P DuPont pin headers for easy access to the broken out ribbon cable.

---

Provided Files: 

The files provided in this Repo include 

(a) a .json file native to EasyEda. Users who wish to examine, remix, or study the original files are encouraged to use EasyEda to ensure maximum program compatibility. 

(b) a Gerber file to allow for production of the PCBs.

(c) a Bill of Materials listing the connectors used on these PCBs and facilitate production.

(d) a Components Placement List (aka "pick and place") to allow placement of through-hole soldered parts on the PCBs.

--- 

Assembly:

Assembly is quite straight forward on this board.  

Components can be individually soldered, but users are encouraged to upload BOM and Pick and Place files when they place an order for board production. The only component that will require soldering one way or another, is the hot swap socket. 

---

How to order a board:

All of the boards so far have been ordered though JLCPCB.  Due to the size of the boards you can order quite a lot at very low cost.  

1 - Go to JLCPCB.com<br/>
2 - Click on `Instant Quote`<br/>
3 - Click on `Add Gerber file` and choose the file named `Gerber_OSB-MX-remixes_PCFT-Mx-1.0.zip`<br/>
4 - Choose the following options for the board:<br/>
- Base Material = FR-4<br/>
- Layers = 2<br/>
- Dimensions = (should auto-populate)<br/>
- PCB Qty = as desired (e.g. 125) <br/>
- Product Type = Industrial/Consumer electronics<br/>
- Different Design = 1<br/>
- Delivery Format = Single PCB<br/>
- PCB Thickness = 1.6<br/>
- PCB Color = (up to you)<br/>
- Silkscreen = (defaults to white for all except white boards which is black)<br/>
- Surface Finish = HASL(with lead)<br/>
- Outer Copper Weight = 1oz<br/>
- Gold Fingers = No<br/>
- Confirm Production file = No<br/>
- Flying Probe Test = Fully Test<br/>
-  Castellated Holes = No<br/>
- Remove Order Number = as desired<br/>
- No advanced options<br/>
5 - Click on `SAVE TO CART`<br/>
6 - Go through checkout process, ensure to select economic shipping to keep costs low

---

Revision History:

v1.0
- Original design


Planned Changes: