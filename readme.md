# VPForce Joystick
See originial Gadroc design for credits and design change history. This version is modified to fit the larger motors using the same gimbal and may of the same other parts. Panels are not interchangeable due to the larger motor size

I've included a second option for a gimbal to be printed in several pieces without supports. This gimbal is experimental and if there are concerns about strength, I recommend printing Gadroc's gimbal or one of the orignal protomaker/Mabo designs. 

Power wires currently feed through the left panel and leave an XT60 connector dangling to allow for connection, future release mat see this mounted in the panel. 

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
* Export STLs for the TAG gimbal.
* Add CAD step files.
* 

# CAD
Fusion file only in CAD folder for now.

# Printed Parts
All STLs should be checked for best orientation in the slicer to minimize supports. I printed all my parts in eSUN PLA+ with a 0.6mm nozzle, 0.3mm layer height. Adapt as necessary to your printer and filament.

| File | Qty | Support | Description |
|------|-----|---------|-------------|
| gimbal_arm_x2 | 2 | Build Plate Only | Gimbal Arms |
| gimbal_pillow_x4 | 4 | Build Plate Only | Gimbal Pillow Blocks |
| gimbal_core | 1 | Build Plate Only | Gimbal Core Joint |
| gimbal_stick | 1 | Build Plate Only | Gimbal Stick Connector |
| ext_bearing_retainer_x3| 3 | None | Exterior Bearing Retainers |
| int_bearing_retainer_x8 | 8 | None | Interior Bearing Retainers |
| control_mount_retainer | 1 | None | Control Mount / Bearing retainer |
| 86 Rear Panel | 1 | None | Rear Case Plate (Roll Drive) |
| 86 Right Panel | 1 | None | Right Case Plate (Pitch Drive) |
| 86 Mid Panel | 1 | None | Mid Case Plate (Roll Bearing / Control Mount) |
| 86 Front Panel | 1 | None | Front Case Plate (Fan) |
| 86 Left Panel | 1 | None | Left Case Plate (Pitch Bearing) |
| 86 Top Panel | 1 | None | Case Top Plate |
| 86 Base Plate | 1 | None | Bottom Case Plate |
| pulley_gimbal | 1 | 72 Tooth Gimbal Pulley |
| USB Bracket | 1 | Holds USB in place on Left Panel |


# BOM
Where possible, all hardware has a McMaster Part # to help indicate correct specifications. BOM updated from Gadroc's where known to be different. (Belts, pulleys, motor mounting screws are correct for 86 Motors)

| Qty | McMaster  | Name | Notes |
|-----|-----------|------|-------|
|   4 | 4668K271  | [6808-2RS Bearings](https://www.amazon.com/dp/B0CGM2PG3Z) | Large Pulley Bearings |
|   8 | 5972k277  | [6802-2RS Bearings](https://www.amazon.com/dp/B0CGM2CHB8) | Gimbal Bearings |
|   2 | 57155k579 | [F625ZZ Bearings](https://www.amazon.com/dp/B07Z3DXF14) | Stick Adatper Bearings |
|  20 | 94459A150 | [M4 Threaded Inserts](https://www.amazon.com/dp/B08T9TXS9S) | Gimbal Screws |
|  10 | 92095A192 | [M4 x 12 Button Head Screw](https://www.amazon.com/dp/B09T9VFY5J) | Pulley Screws |
|   4 | 91100A313 | [19mm Washer](https://www.amazon.com/dp/B0B8SPK65J) | Gimbal Washers |
|  12 | 91292A122 | [M4 x 25 Socket Head Screw](https://www.amazon.com/dp/B0BMQ4WV1V) | Large Pulleys |
|   3 | 98689A114 | M5 Washer (Stock) | Gimbal Core Joint / Stick Adatper |
|   2 | 90591A260 | M5 Nut (Stock) | Gimbal Core Joint / Stick Adatper |
|   1 | 91290A199 | M5 x 60 Socket Head Screw (Stock) | Gimbal Core Joint |
|  52 | 94459A130 | [M3 Threaded Inserts](https://www.amazon.com/dp/B0CDH36ZMX) | Case, USB Bracket, Control Board Mount, Stick Connector |
|  44 | 91263A825 | [M3 x 12 Flat Head Screw](https://www.amazon.com/dp/B07WJKPCZY) | Case Screws, add two more if using printed motor pulleys |
|   2 | 92095A183 | M3 x 12 Button Head Screw (Stock) | USB Bracket Screws |
|  12 | 92095A119 | M3 x 15 Button Head Screw (Stock) | Pulley Bearing Retainer Screws |
|  12 | 90591A250 | M3 Nut (Stock) | Pulley Bearing Retainer Nuts |
|   4 | 92095A177 | M3 x 5 Button Head Screws (Stock) | Control Board Screws |
|   8 |           | [M6 x 20 Slim Socket Head Screw] | Motor Mounts |
|   2 |           | M2.5 x 10 Flat Head Screw (Stock) | Power Connector Mount |
|   2 |           | [5M-15T-20W Pulley](https://a.co/d/b9yMcuO) | Motor Pulley |
|   1 |           | 465mm long HTD 5M-15W Belt | Pitch Belt - 09W more readily available, sub if desired at your own risk |
|   1 |           | 380mm long HTD 5M-15W Belt | Roll Belt - 09W more readily available, sub if desired at your own risk |
|   1 |           | 5 Pin Mini Din Connector (Stock)| Stick connector - I used replacement parts from Thrustmaster for a Warthog stick that I bought a long time ago. |
|   1 |           | [80mm Case Fan](https://www.amazon.com/dp/B00IOIJ4AC) | Parts designed to use standard PC fan screws which are included with this fan. |
|   1 |           | [E-Stop Switch](https://www.amazon.com/dp/B08B87GJGB) | |
|   1 |           | [10k Type B Linear Potentiometer](https://www.amazon.com/dp/B09897HR3C) |
|   1 |           | [XT60E-M Connector](https://www.amazon.com/dp/B07VV92WZS) | |

# Assembly
Since this is a very close derivative of protmakers work his assembly guide should be enough to figure out how to build using these parts.
