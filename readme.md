# VPForce Joystick
This is a remake of Mabo's FFB Joystick for 3D printing including several enhancments from protmakers version as well.

Changes from Mambo's design:
* Gimbal is redsigned to minimize support material and optimze mating surfaces for fitment.
* 72 Tooth pulley used for 6:1 gear ratio
* Shell adjusted for 3D printing

Changes from Protomaker's design:
* Heat set threaded inserts are used anywhere where a screw is used to fasten two printed parts.
* Single pot similar to Rhino
* No top panel cover
* Fan grate incorporated into case
* XT60 connector for power supply

# Credits
This is nearly zero original work from me.  All critical deminsions and ratios came from the original designers.  I just cleaned up some CAD work and injected some of my personal preferences for printing.  Original authors listed below:

* [walmis](https://github.com/walmis/FFB-Joystick-Base) - Electronics, firmware and original base design.
* [mabo](https://github.com/mabo1972/FFB-Joystick-Base-Plywood) - Expanded base design including full gimbal.
* [protmaker](https://github.com/protomaker964/Rhino-FFB-Clone-3D_Printed) - Modification for 3D printing and refinements

# Open Items
* Converting the stick connector part to be two parts similar to the design used in the Rhino sold by walmis. An adpater that finshies the gimbal with mouting point for a metal tube or extrusion and
* No throw limiters (I don't use one so didn't add it).  Base has 22 degrees in all directions the same as the Rhino.
* Boot clamp has not be tested yet.  Design changes may be necessary.
* CAD Still has control board mount for under the gimbal, but there is not enough space to connect power wires in that location.
* Stick connector is designed for thrustmater replacement parts, need to create version that will work for the [MD-50PL100](https://www.digikey.com/en/products/detail/cui-devices/MD-50PL100/500828).  Stick connector from protmaker and mabo should be compatible, but I have not tested.
* Optimize for screw types.  There are a few places where we could eliminate screw variations (ex: bearing retainers vs case screws).
* Internal bearing retainer nuts are a pain especially once motors are install.  Switch them to some kind of captive nut.

# CAD
Both STEP and Fusion 360 files can be found in the CAD directory.

# Printed Parts
All STLs are in print orientation and should be able to be directly inserted and arranged in your slicer.  I printed all of my parts in polymaker PLA Pro with a .2mm layer height using voron part specs.  Adapt as necessary to your printer and filament.

| File | Qty | Support | Description |
|------|-----|---------|-------------|
| gimbal_arm_x2 | 2 | Build Plate Only | Gimbal Arms |
| gimbal_pillow_x4 | 4 | Build Plate Only | Gimbal Pillow Blocks |
| gimbal_core | 1 | Build Plate Only | Gimbal Core Joint |
| gimbal_stick | 1 | Build Plate Only | Gimbal Stick Connector |
| ext_bearing_retainer_x3| 3 | None | Exterior Bearing Retainers |
| int_bearing_retainer_x8 | 8 | None | Interior Bearing Retainers |
| control_mount_retainer | 1 | None | Control Mount / Bearing retainer |
| case_rear | 1 | None | Rear Case Plate (Roll Drive) |
| case_right | 1 | None | Right Case Plate (Pitch Drive) |
| case_mid | 1 | None | Mid Case Plate (Roll Bearing / Control Mount) |
| case_front | 1 | None | Front Case Plate (Fan) |
| case_left | 1 | None | Left Case Plate (Pitch Bearing) |
| case_top | 1 | None | Case Top Plate |
| case_bottom | 1 | None | Bottom Case Plate |
| pulley_gimbal | Build Plate Onley | 72 Tooth Gimbal Pulley |
| pulley_motor | None | 12 Tooth Motor Pulley (Optional if you don't want to buy metal pulley) |
| jig_center_x2 | 2 | Centering Jig for intial assembly and calibration |
| boot_clamp_lower | 1 | Lower Boot Clamp |
| boot_clamp_upper | 1 | Upper Boot Clamp |
| boot_clamp_ring | 1 | Boot Clamp Ring for Stick Connector |

# BOM
All hardware where possible has a McMaster Part # to help in getting specifications correct. Parts I used are linked from the description when I didn't already have them in stock from old projects.

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
|   8 |           | [M6 x 15 Slim Socket Head Screw](https://www.amazon.com/dp/B0CK264Y73) | Motor Mounts |
|   2 |           | M2.5 x 10 Flat Head Screw (Stock) | Power Connector Mount |
|   2 |           | M3 x 6 Grub Screw | Motor Pulley Screw for 3D Printed Pulley |
|   2 |           | [5M-12T-16W Pulley](https://www.amazon.com/dp/B07R49G8BK) | Motor Pulley - 3D printed version is optional as well |
|   1 |           | 465mm long 5M-16W Belt | Pitch Belt |
|   1 |           | 415mm long 5M-15W Belt | Roll Belt |
|   1 |           | 5 Pin Mini Din Connector (Stock)| Stick connector - I used replacement parts from Thrustmaster for a Warthog stick that I bought a long time ago. |
|   1 |           | [80mm Case Fan](https://www.amazon.com/dp/B00IOIJ4AC) | Parts designed to use standard PC fan screws which are included with this fan. |
|   1 |           | [E-Stop Switch](https://www.amazon.com/dp/B08B87GJGB) | |
|   1 |           | [10k Type B Linear Potentiometer](https://www.amazon.com/dp/B09897HR3C) |
|   1 |           | [XT60E-M Connector](https://www.amazon.com/dp/B07VV92WZS) | |

# Assembly
Since this is a very close derivative of protmakers work his assembly guide should be enough to figure out how to build using these parts.