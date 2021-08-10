Update 2021-08-10: I have also finally (hopefully) fixed the DS Lite style power switch board. 1.6mm PCB will be too thick. 0.8mm board might work but appears to be too tall. Flex PCB might be required. I will update this abysmal repo with better instructions once fully tested. 

Update 2021-07-24: I have finally (hopefully) fixed the footprint for the switch I used but I may have messed up the switch placement in the process. I have ordered test PCBs to verify. This is the switch the boards use: https://lcsc.com/product-detail/Multi-Directional-Switches_XKB-Connectivity-TM-2023_C318951.html

v2.1 is an incremental upgrade to v2.0 (the original version in this soft latching repository, v1.0 used a different design entirely and never made it to github) that moves the button off the board. The ground pad has moved to the bottom of the PCB and the button footprint has been reduced to a solder pad on the front of the board. I have also removed the power on behavior jumper from this revision to try and make it even smaller. When ordering this revision from oshpark, it should only be $0.90 so it's quite a bit cheaper than the previous revision. 

This new revision is not yet tested but since the schematic is otherwise unchanged, it should still work. I did rearrange some parts and I did redo all the track layouts. It's about as small as I can make it without making it increasingly difficult to assemble (though it is already still difficult with the component spacing). 

There are also two new board files. These are to replace the power switch itself on the GAME BOY ADVANCE ONLY. Other versions will come, probably, but these are purely for testing. I have no idea if either of these will fit and work and when everything is assembled and tested, I will add renders, BOM, assembly instructions, etc. As is, the boards need clean up but I am currently testing a few things so I tried playing it safe. 

See this video for install: https://www.youtube.com/watch?v=EvzQTYazzEA
