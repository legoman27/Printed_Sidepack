# Printed_SideSkirt
A fully printed mod intended for a Voron Trident to relocate the electronics to the side of the printer with as little deviation from the standard BOM as possible.

Heavily inspired by by `kyledavis417#2007`'s [Trident sidepack mod](https://github.com/3DPrintingMods/VoronTrident-Sidepack).

Huge thanks to the Voron design team for everything!

#

Current design assumes a total thickness of side panel + foam tape = 3mm.

This mod could also be mounted on the rear of a trident, but this prevents access to the A/B belts at the rear of the gantry as well as moving the power inlet to the side of the machine, which may or may not be preferable.

Uses a completely stock Voron Spec Trident frame. Verticals are all the same length for 250 / 300 / 350, so the front and rear pieces will be the same for all sizes. 
LDO frames are taller, and will require modification --TODO!.

Total width of the side skirts is 90mm. 
the side skirts have provisions for an M3 heat set insert, and should be able to accept most side panel clips.
270 degree hinges mount to the side of the printer and are not compatible. any hinges that mount to the front should work just fine.

Total height of the lower skirts is 36mm.
The alternate lower skirts are optional, and were only created because I wanted to reduce the total z height of the printer slightly to fit in my workbench.
For smaller builds, it may be beneficial to use the standard full size Lower Skirts for more space for electronics, or if you want to retain the standard mini12864 screen. 
extended ribbon cables should be used in this case.


I originally created this for a trident with a 215mm^2 build area, so there is a narrower fan mount available if anyone else builds one for some reason.
All other sidepack pieces in this case are the same as a 250mm^2 build.

<p align="center">
  <img src="Images/overview.png" width="800">
</p>


# Future Plans
- [ ] finish lower skirts and update for standard frames
- [ ] add other power inlet types
- [x] ~~add support for 300 & 350 frames~~
- [ ] add support for LDO frames
- [ ] add some sort of display capability in the side skirt, mabye a btt TFT43 if it is at all possible to rotate the display by 90 degrees.


[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/M4M2H52T7)

# EVERYTHNG BELOW THIS IS A WORK IN PROGRESS


# BOM Changes

+ 1x side panel of your size 250/300/350 - modified to allow for cable pass-through (OR PRINT the side panel)
+ 8x M5x10 BHCS
+ 8x M5 nut
+ 16x M3x8 SHCS
+ 12x M3x4x5 Heat set inserts


# Installation

FOAM TAPE IS REQUIRED BETWEEN THE SIDE PANEL AND THE FRAME. FRONT Z MOTOR WILL BIND ON THE PANEL WITHOUT CLEARANCE.

### SideSkirt mounted on the right side of the printer
- Z_rear parts & Cable chain mount are mirrored in X 
- Deck panel mounted upside down


### Lower Skirt corners
- For the front corners, install the captive M5 nut for the rubber feet before mounting to the frame. Inserting the nut after attaching to the frame is not possible due to clearance with the steppers.


### Corner Trim
- just stuck on with double sided tape


### DIN Rail mounts
- The din rails mount via M5x16 BHCS with captive nuts through the skirt

<p align="center">
  <img src="Images/din_outside.png" width="600">
</p>

<p align="center">
  <img src="Images/din_inside.png" width="600">
</p>
