# v0.2 bringup notes

## Build specifics:
 - Fly Gemini v3 Soc/MCU Mainboard
 - Fly SH(i)T36v2 CANBUS Toolhead board
 - E3D Revo Voron Hotend
 - Neodymium magnet bed
 - Clone daylight on a matchsticks
 - PCB railnuts

## Part sources:
 - Frame: SIBOOR
 - Motion: SIBOOR
 - Motors: SIBOOR
 - Rails: LDO (YZ), DFH (X)
 - Extruder: Filastruder
 - Hotend: Filastruder
 - Bed: Baiozraw
 - Fasteners: Baiozraw
 
# Voron v0.2 bringup TIWIK (Things I Wish I Knew):

## If you are self-sourcing:
 - Pulleys are GT2-20 tooth.
   - 16 tooth probably would have worked (sensorless homing value was the same).
 - You should buy a fastener set.
   - SIBOOR includes bearings, feet, magnets, springs, and clone bondtech bits for around the same price as Baiozraw which didn't.
 - If you buy a fastener set, consider buying quality shim washers.
   - I purchased both a Baiozraw and SIBOOR fastener sets and both contained stamped "shim washers" cupped far beyond tolerances.
   - I was able to use a good set of flat pliers and "massage" a set of cupped washers to within acceptable shim tolerances, but YMMV.
 - F623-ZZ bearings *may* rub your belts, creating dust dandruff debris around your idlers.
   - I had both ZZ and RS bearings and a measurement audit showed the RS had "better" tolerances, and after re-belting with RS, it didn't rub anymore.
 - 3M 5952 VHB tape should be the 3/4-inch variety if you don't want to be cutting a whole bunch.
 - Bowden tube 4x3 is also known as "reverse bowden", and is used to allow slack for retraction.
 - The listed Bowden Fittings are not required unless you are doing a bowden extruder (not direct drive with reverse bowden feed).

## Component notes:
 - If you get a batch of rails, the one with the most preload should be used for the X axis.
 - Installing the thermal fuse for the bed along the (logical) rear edge may limit travel on Z with or without kirigami.
 
## Assembly notes:
- Pg 30. Preload 3 for direct drive, 5 for bowden.
- Pg 53. You preload 2 M3 into the bottom channel if you're NOT using the 5V PSU, you'll need more for that part.
- Pg 155. You can coat a short M3 with vasaline to keep the nut retained while you glue it, this prevents glue seeping into threads.

### Supplier Links:

 - Filastruder (https://www.filastruder.com/)
 - DFH.FM (https://dfh.fm/)
 - SIBOOR (https://www.aliexpress.com/store/1101980497)
 - Mellow3D (https://mellow.aliexpress.com/store/1531088)
