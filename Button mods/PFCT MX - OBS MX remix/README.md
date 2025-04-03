![PFCT MX top](https://github.com/CapnHawke/Game-Controller-Parts/tree/main/Button%20mods/Images/PFCT%20MX%20top.png)
![PFCT MX bottom](https://github.com/CapnHawke/Game-Controller-Parts/tree/main/Button%20mods/Images/PFCT%20MX%20bottom.png)
![PFCT MX completed unit](https://github.com/CapnHawke/Game-Controller-Parts/tree/main/Button%20mods/Images/completed%20unit.png)

## PFCT MX 1.0
---


!!!WARNING!!!

These circuit boards were based on another open source design which can be viewed here, called [OSB MX.](https://github.com/OpenStickCommunity/Hardware/blob/main/3D%20Prints/OSBMX%20v2/Legacy%20-%20OSBMX%20v1/README.md) Those files were provided with a number of warnings and disclaimers, all of which also apply to this remix. To summarize, there may be production issues with the PCBs, there may be incompatibilities with certain MX switches, and these files are provided WITHOUT WARRANTY. User assumes all risk including potential damages, if applicable.

---

## Attribution

Due to the size of the individual boards it may be impossible to provide a proper link to the original repo.  As such, please use these extra guidelines:

- A link to the OSB MX repo if you are making a remix that is done on a panel where there is space to include the repo link
- Attribution to the original designers of the OSB MX (TheTrain and Rana Labs)
- A link to this repo on any sales pages for either original OSBMX switch plates or remixes
- If a remix is based on this design, a link to the PFCT MX repo and attribution to CapnHawke in addition to the other required links and attribution.

The following text must be included in any GitHub distributions of derivatives of this board. All links must also be included.

Based on the OSBMX by TheTrain and Rana Labs - https://ko-fi.com/ranalabs/

Copyright © 2023 [TheTrain](https://github.com/TheTrainGoes) and [Rana Labs](https://ko-fi.com/ranalabs/)

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
  - Redrawn the board outline. 
  - Added 2.0mm JST PH connector for signal and ground.
  - Added 2.54mm DuPont pin headers for signal and ground.

If any further changes are made from this remix:
  - list any changes you make here

---

Summary:

The PFCT Mx are based on the hot swap variant of OSBMX 24 / OSBMX 30 circuit boards hosted in the [OpenStick Community Hardware Repo](https://github.com/OpenStickCommunity/Hardware/blob/main/) which in turn are based on the buttons from the OFOF1 by RanaLabs (https://github.com/rana-sylvatica/OFOF1).

PFCT Mx was designed with four objectives in mind. First, the buttons are intended to have a very low profile beneath their mounting panel. 

Second, the buttons are intended to be usable with several kinds of affordable project wire, for example, breadboard jumper wires. Although many arcade buttons have typically used 2.8mm quick disconnect or Faston connectors, these buttons instead use wires that are more commonly available in general hobby electronics spaces. 

Third, the existence of a second ground connector on the button PCB allows several of them to be chained together, creating a highly expandable network of buttons all tied to a common ground. 

Fourth, the space for the connectors has been moved farther from the center pin to improve compatibility with different kinds of switches, by eliminating the need for switches with a cut-out (typically for LEDs).

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

Parts necessary for assembly of the main low profile board:

1 x PFCT MX board<br/>
1 x MX hot swap socket (https://www.aliexpress.com/item/4001051840976.html)<br/>
2 x M2 5mm Hex Hexagon Socket Cap Head Self Tapping Screws (https://www.aliexpress.com/item/10000350027047.html)<br/>
1 x OOSBMX 24 / OSBMX 30 housing<br/>
1 x OSBMX 24 / OSBMX 30 plunger<br/>
1 x OSBMX 24 / OSBMX 30 washer<br/>
1 x MX switch (https://www.aliexpress.com/item/1005004679651313.html)<br/>

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

How to order a button housing:

Button housings typically have been ordered though JLCPCB.  Due to the size of the buttons you can order a full sprue for a very small cost depending on the material you choose.  You will get the best quality out of PA12 nylon, but they are the most expensive.  Make washers out of a different material, to prevent the nylon from bonding together after it is tightened.

1 - Go to JLCPCB.com<br/>
2 - Click on `Instant Quote`<br/>
3 - Click on `3D Printing` <br/>
4 - Click on `Add 3D files` and choose the file named `OSBMX 24 - Single Sprue.stl` or `OSBMX 30 - Single Sprue.stl`<br/>
4 - Choose the following options for the board:<br/>
- 3D Technology = MJF (Nylon) (1)<br/>
- Material = PA12-HP Nylon (2)<br/>
- Color = Dyed Black<br/>
- Build Time = 72 hours<br/>
- Quantity = As needed<br/>
- Product Description = Anything you like<br/>
- 3D Remarks = "Please print facing flat down."<br/>

5 - Click on `SAVE TO CART`<br/>
6 - Go through checkout process, ensure to select economic shipping to keep costs low

(1) - These are best done in MJF (Nylon).  If you want to make cheaper buttons you can do them in SLA (Resin).  The sprues have been optimized for ordering in MJF (Nylon).  If you would like to order these in resin please check out some of the other files I have in here which have greater sized sprues.
(2) - PA12-HP Nylon is recommended due to finish and feel, although it is more expensive.  You can make these out of 9000R resin if you are looking to get a larger number for a lower cost, or want to experiment with doing dye jobs.
     
---

Other stuff:

Check out OSB MX V2 over on the Open Stick Community Hardware repository! Please note that these PCBs are untested with the V2 body variant. 

---

Revision History:

v1.0
- Original design

--- 

Planned Changes:

- Create variant board with three pin headers (one signal and two ground).
- Create variant board with integrated LED.
