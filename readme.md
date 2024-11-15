# VPForce Joystick with 86BLF03 or 86BLF04 motors
See originial Gadroc design for credits and design change history. This version is modified to fit the larger motors using the same gimbal and many of the same other parts. Panels are not interchangeable due to the larger motor size. Panels should be able to be printed on any 3D printer with a bed size equivalent to an Ender3 or larger. 

I've not included a gimbal to remove some confusion around assembly based on some questions I've received. I recommend printing the Protomaker gimbal (linked below) and following the assembly steps there. Any of the gimbals will work with this project (Protomaker, Gadroc, mrusk, mabo, etc)  

You will also need to purchase a 2x86BLF03 + USBkit or a 2x86BLF04 + USBkit from VPForce. The 86BLF04 will be the strongest option but either of them will fit this case. 

There are two options for gear ratios, you need to chose the one you would like below and buy the appropriate size belts. 60T/15T will be 1.7x the standard Rhino peak torque, 72T/15T will be 2.0x the standard Rhino peak torque. 


# Credits
Original authors are listed below:

* [walmis](https://github.com/walmis/FFB-Joystick-Base) - Electronics, firmware, and original base design.
* [mabo](https://github.com/mabo1972/FFB-Joystick-Base-Plywood) - Expanded base design, including full gimbal.
* [protomaker](https://github.com/protomaker964/Rhino-FFB-Clone-3D_Printed) - Modification for 3D printing and refinements
* [Gadroc](https://github.com/Gadroc/vpforce-ffb-joystick) - Basis for modifications

# To be done:
* 15 deg throw limiter in CAD file is optional. Export STLs if you want it or create a different throw limiter using the tool on the VFP discord.
* Boot clamp has not been tested yet. Design changes may be necessary. (No change from Gadroc, removed STLs but it is in the CAD file)
* Update BOM for minor hardware, screws, etc. Most of the hardware should be the same as the original Gadroc design, the major difference will be quantities and M6 bolts for mounting the 86 motors.
* Add CAD step files.
* 

# CAD
Fusion file only in CAD folder for now, step files TBD. 57 Series also included as reference in a sub folder. 

# Printed Parts
All STLs should be checked for best orientation in the slicer to minimize supports. Placing the long edge of the case plates in the X direction worked best for my set up.  I printed all my parts in eSUN PLA+ with a 0.6mm nozzle, 0.3mm layer height. Adapt as necessary to your printer and filament.

Necessary Parts for all Gimbal Types, Print these then choose a Gear Ratio to print. 
| File | Qty | Support | Description |
|------|-----|---------|-------------|
| ext_bearing_retainer_x3| 3 | None | Exterior Bearing Retainers |
| int_bearing_retainer_x8 | 8 | None | Interior Bearing Retainers |
| control_mount_retainer | 1 | None | Control Mount / Bearing retainer |
| 86 Rear Plate | 1 | None | Rear Case Plate (Roll Drive) |
| 86 Right Plate | 1 | None | Right Case Plate (Pitch Drive) |
| 86 Mid Plate | 1 | None | Mid Case Plate (Roll Bearing / Control Mount) |
| 86 Front Plate | 1 | None | Front Case Plate (Fan) |
| 86 Left Plate | 1 | None | Left Case Plate (Pitch Bearing) |
| 86 Top Plate | 1 | None | Case Top Plate |
| 86 Base Plate | 1 | None | Bottom Case Plate |
| USB Bracket | 1 | None | Holds USB in place on Left Plate |

Gear Ratio Options
| File | Qty | Support | Description |
|------|-----|---------|-------------|
| HTD-5M-60 Pulley | 2 | None | 60 Tooth Gimbal Pulley 1.7x Standard Rhino USE BELTS 465mm/380mm |
| HTD-5M-72 Pulley | 2 | None | 72 Tooth Gimbal Pulley 2.0x Standard Rhino USE BELTS 500mm/420mm |

| Print and Assemble the Protomaker gimbal or another of your choice (link to Protomaker above) |
|-----------------------------------------------------------------------------------------------|


<!--Gadroc's Gimbal
| File | Qty | Support | Description |
|------|-----|---------|-------------|
| gimbal_arm_x2 | 2 | Build Plate Only | Gimbal Arms |
| gimbal_pillow_x4 | 4 | Build Plate Only | Gimbal Pillow Blocks |
| gimbal_core | 1 | Build Plate Only | Gimbal Core Joint |
| gimbal_stick | 1 | Build Plate Only | Gimbal Stick Connector |

TAG Gimbal - Experimental, bearing journals attach with M5 screws to minimize supports.
| File | Qty | Support | Description |
|------|-----|---------|-------------|
| OptiArmFramex2 | 2 | Build Plate Only | Gimbal Arms |
| GIMBAL_ARM_BEARING_PILLOWx4 | 4 | Build Plate Only | Gimbal Pillow Blocks |
| OptiCore Main | 1 | None | Gimbal Core Joint |
| Core Journal x2 | 2 | None | Gimbal Core Joint Bearing Journals |
| 2020GIMBAL_STICK_CONNECTOR_TAG | 1 | Build Plate Only/None | Gimbal Stick Connector for 2020 Extensions |
| Main Connector Journal x2 | 2 | None | Stick Connector Journals |
| 2020Extension_TM_WARTHOG | 1 | Build Plate Only/None | TM Warthog Threads for 2020 Extension |

Mabo Gimbal - This is the orignal gimbal I based the TAG gimbal off of, if you want to print a traditional gimbal that is a bit beefed up but less optimized choose this one. This has both the 2020 extension option and the one piece threaded TM grip attachment for the main stick as an option. Use above reference quantities to determine how much of each STL to print. 
-->
# BOM
Reference Protomaker BOM and assembly instructions for additional information on part usage. BOM updated from Protomaker's where known to be different. (Belts, pulleys, motor mounting screws are correct for 86 Motors). Due to bulk quantities from Amazon links you may end up with hardware left over, organize them and save them for your next project!


| Qty | Name | Notes |
|-----|------|-------|
|   4 | [6808-2RS Bearings](https://www.amazon.com/dp/B0CGM2PG3Z) | Large Pulley Bearings |
|   8 | [6802-2RS Bearings](https://www.amazon.com/dp/B0CGM2CHB8) | Gimbal Bearings |
|   2 | [F625ZZ Bearings](https://www.amazon.com/dp/B07Z3DXF14) | Stick Adatper Bearings |
| 100 | [M4 Threaded Inserts](https://www.amazon.com/dp/B08T9TXS9S) | Various, you won't use all of them |
|  12 | M4 x 35 Button Head Screw | Pulley Screws |
|  12 | M4 Nut | Pulley Screws |
|  24 | M4 Washer | Pulley Screws |
|   4 | [M5x19mm Washer](https://www.amazon.com/dp/B0B8SPK65J) | Gimbal Washers |
|  12 | [M4 x 25 Socket Head Screw](https://www.amazon.com/dp/B0BMQ4WV1V) | Large Pulleys |
|   3 | M5 Washer (Stock) | Gimbal Core Joint / Stick Adatper |
|   2 | M5 Nut (Stock) | Gimbal Core Joint / Stick Adatper |
|   1 | M5 x 60 Socket Head Screw (Stock) | Gimbal Core Joint |
|  12 | M4 x 10 Button Head Screw (Stock) | 6802 Bearing Retainer Screws with 19mm Washers |
|  12 | M5 x 10 Button Head Screw (Stock) | Pillow Block to Gimbal Arm Attachment Screws |
| 100 | [M3 Threaded Inserts](https://www.amazon.com/dp/B0CDH36ZMX) | Case, USB Bracket, Control Board Mount, Stick Connector, you won't use all of them. |
|  80 | [M3 x 12 Flat Head Screw](https://www.amazon.com/dp/B07WJKPCZY) | Case Screws, you won't use all of them |
|   2 | M3 x 12 Button Head Screw (Stock) | USB Bracket Screws |
|  12 | M3 x 15 Button Head Screw (Stock) | Pulley Bearing Retainer Screws |
|  12 | M3 Nut (Stock) | Pulley Bearing Retainer Nuts |
|   4 | M3 x 5 Button Head Screws (Stock) | Control Board Screws |
|   8 | M6 x 20 Socket Head Screw | Motor Mounts |
|   2 | M2.5 x 10 Flat Head Screw (Stock) | Power Connector Mount |
|   2 | [5M-15T-20W Pulley](https://a.co/d/b9yMcuO) | Motor Pulley |
|   1 | 5 Pin Mini Din Connector (Stock)| Stick connector - I used replacement parts from Thrustmaster for a Warthog stick that I bought a long time ago. |
|   1 | [80mm Case Fan](https://www.amazon.com/dp/B00IOIJ4AC) | Parts designed to use standard PC fan screws which are included with this fan. |
|   1 | [E-Stop Switch](https://a.co/d/37DwknT) | |
|   2 | [10k Type B Linear Potentiometer](https://www.amazon.com/dp/B09897HR3C) |
|   1 | [XT60E-M Connector](https://www.amazon.com/dp/B07VV92WZS) | |

CHOOSE ONE PAIR of these based on the Gimbal Pulley you have chosen to print. 
| Pair | Qty | PULLEY SIZE  | Name | Notes |
|------|-----|--------------|------|-------|
|   A  |   1 | 60T | 465mm long HTD 5M-15W Belt | Pitch Belt - Belts Sized for 15T Motor/60T Gimbal Pulleys |
|   A  |   1 | 60T | 380mm long HTD 5M-15W Belt | Roll Belt - Belts Sized for 15T Motor/60T Gimbal Pulleys  |
|   B  |   1 | 72T | 500mm long HTD 5M-15W Belt | Pitch Belt - Belts Sized for 15T Motor/72T Gimbal Pulleys |
|   B  |   1 | 72T | 420mm long HTD 5M-15W Belt | Roll Belt - Belts Sized for 15T Motor/72T Gimbal Pulleys  |

# Assembly
Since this is a very close derivative of protmakers work his assembly guide should be enough to figure out how to build using these parts.
