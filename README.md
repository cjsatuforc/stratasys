﻿## Stratasys Reprap Project

Repurposing and rebuilding 3D printers made by stratasys "Strat-a-trap"

This will cover various models, mainly the ones that are old enough to get for free, however these printers are very similar in design so small modifications in configuration may be needed for your printer.

**Something to consider only if you have an older printer** these printers use high torque - high voltage NEMA 23 stepper motors this means you may have to replace them with something more suitable for use with modern stepper drivers. 

This guide will cover the following printers:
Dimension 1200 SST
uPrint


Bake Oven Tempature Range

    75° C (167° F) Max

Gantry

    254 x 254 x 305 mm (10 x 10 x 12 in)


Max Travel

    X:237.162 mm (9.33 in) 
    Y:265.613 mm (10.45 in)
    Z:330.2 mm
  
Normal Travel

    X:254
    Y:254
    Z:305

End Stops

    24v optical end stop.... crap nothing supports this
  
Origin

    X:6.35
    Y:5.08

Steps Per mm - Vefied Working!

    X:126 
    Y:267.5
    Z:1266
Thank You!
https://reprap.org/forum/read.php?1,418999,435031#msg-435031 

Gantry Specs

    12 mm GT3 Belts (Stronger Version of GT2)
    16 mm Linear Rods
Motors

    X (motor 16 tooth pulley) - (60 tooth pulley)
    Y (20 tooth pulley) to (ideler pulley)
    Z (36 tooth pulley) to (36 tooth) to (big lead screw pitch unknown)
Electronics

    2x 120v DC 400 Watt (B075 CAT NO. FS2001G102) - Build Chamber Heaters one on each side
    4x 24V 0.48A Radial Blower Fans (blows air through the heating elements)
    1x 24V Radial Blower Fan (blows cooler air on the print head via a tube that runs down to the bottom of the printers case)

Motion

    Standing at the front of the printer.
    X asix moves right in the positive direction
    Y axis moves away from you to the back of the printer in the negative direction
    Z asix moves up in the positive direction

![ScreenShot](Stratasysxyz_illustration1.jpg)

    XY Axis Belt Specs

>Gates 3MR-282-09 Belt
>SKU 9390-4094
>Part Number 3MR-282-09
>Profile GT
>Pitch	3 mm
>Number of Teeth 94
>Length (inch)	11.1
>Length (mm)	282


    Y Axis Small Belt

>SDP A 6T53M280090
>Bet Thikness 9mm
>Pitch Length 840mm
>Part Number: A 6R53M280090
>Belt Type: Single Sided
>Number of Grooves: 280
>Belt Witdth: 9mm
>Pitch Length: 840mm

>GT®3 is an equivalent and direct replacement for GT®2 belts.

>Neoprene - Nylon Covered, Fiberglass Reinforced
>Breaking Strength: 158 N per 1 mm (113 lbf per 1/8 in.) 
>Belt Width; not representative of the load-carrying capacity of the belt.
>Working Tension:507 N for 25.4 mm belt (114 lbf for 1 in. belt).
>Temperature Range: -34°C to +85°C (-30°F to +185°F)