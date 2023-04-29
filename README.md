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
 - You should buy a fastener kit.
  - SIBOOR includes bearings, feet, magnets, springs, and clone bondtech bits for around the same price as Baiozraw which didn't.
 - F623-ZZ bearings *may* rub your belts, creating dust dandruff debris.
  - I had both ZZ and RS bearings and an audit showed the RS had "better" tolerances, and after re-belting with RS, it didn't rub anymore.
 - If you get a batch of rails, the one with the most preload should be used for the X axis.
 - Installing the thermal fuse for the bed along the (logical) rear edge may limit travel on Z with or without kirigami. 

### Supplier Links:

 - Filastruder (https://www.filastruder.com/)
 - DFH.FM (https://dfh.fm/)
 - SIBOOR (https://www.aliexpress.com/store/1101980497)
 - Mellow3D (https://mellow.aliexpress.com/store/1531088)
