# Doom-Cube

![DOOMCUBE](Images/DCLogo.png)


A mod for V2.4 designed by the Voron community, for the Voron community! Please note that it is a work in progress, design iterations are expected. The files are hosted on github so we have a log of the past history for the parts.

[Make sure to join our discord!](https://discord.gg/EAANfEk25f)


#### Key features:

-4040 vertical components to allow for insulation with air gap stock

-Top mounted Z drives

-Top mounted low voltage components

-Bottom mounted high voltage components

#### Optional
-Replace X/Y cable chains with umbelical (Z chain retained for A/B motors and Y endstop)


#### Changes required:

-4pcs 4040 extrusions (HFSB5-4040)   -or-   4pcs 404020 rounded extrusions (HFSR5-404020)

-New Z Idlers  (only printed parts required)

-Relocate X/Y endstops  (only printed parts required)

-Cable Glands for Umbelical

#### Tips for printing parts:

-For any Voron stock parts, or the Z idlers, please use standard settings

-For skirts, etc, you may use other settings to reduce filament usage. Currently I am using: 0.3mm layer height, 2 perimeters, 2 bottom, 3 top, 20% infill. 

## BOM 
All extrusions are listed using Misumi part numbers.

Part numbers are listed for both square 4040, and rounded 404020 vertical extrusions.  Choose only one type.  The first set of part numbers is for plain cut extrusions.  The second part number is for square extrusions that are both cut and drilled by misumi.  

####Note:
If you choose to use rounded corners, you will need to reuse your frame's existing 2020 vertical extrusions, or purchase a set of them for a scratch build.  The rounded verticals do not require machining, but the 2020 verticals that nest into them will need to have holes drilled to enable securing the rounded piece with blind joints, as shown here.
<img src="Images/404020-1.jpg" alt="drawing" width="200"/>

## Extrusions Based on Standard V2 Build Sizes

## DOOM-350
### Frame Extrusions
#### DIY
Misumi Part #  |Qty
----|----|
Square Verticals: HFSB5-4040-530 |4 
Rounded Verticals: HFSR5-404020-530 |4

#### Pre-Drilled
Misumi Part #  |Qty
----|----|
Square Verticals: HFSB5-4040-530-LCP-RCP |4

### Door Extrusions

#### DIY
Misumi Part #  |Qty
----|----|
HFSB5-2020-530|2
HFSB5-2020-428|2

#### Pre-Drilled
Misumi Part #  |Qty
----|----|
HFSB5-2020-530-AH10-BH520|2
HFSB5-2020-428|2

## DOOM-300
### Frame Extrusions
#### DIY
Misumi Part #  |Qty
----|----|
Square Verticals: HFSB5-4040-480 |4
Rounded Verticals: HFSR5-404020-480 |4

#### Pre-Drilled
Misumi Part #  |Qty
----|----|
Verticals: HFSB5-4040-480-LCP-RCP |4

### Door Extrusions
#### DIY
Misumi Part #  |Qty
----|----|
HFSB5-2020-480|2
HFSB5-2020-378|2

#### Pre-Drilled
Misumi Part #  |Qty|
----|----|
HFSB5-2020-480-AH10-BH470|2
HFSB5-2020-378|2

## DOOM-250
### Frame Extrusions
#### DIY
Misumi Part #  |Qty
----|----|
Square Verticals: HFSB5-4040-430 |4
Rounded Verticals: HFSR5-404020-430 |4

#### Pre-Drilled
Misumi Part #  |Qty|
----|----|
Square Verticals: HFSB5-4040-430-LCP-RCP| 4

### Door Extrusions

#### DIY
Misumi Part #  |Qty| 
----|----|
HFSB5-2020-430|2
HFSB5-2020-328|2

#### Pre-Drilled

Misumi Part #  |Qty| 
----|----|
HFSB5-2020-430-AH10-BH420|2
HFSB5-2020-328|2

## Door Hinges
Silver and Black are listed 

|Misumi Part #  |Qty|Color
------|---|---|
HHPSN5-SET|2| Silver
HHPBSN5-SET|2| Black


# Ongoing and Future Development
While we all have many irons in the fire, Doomcube v2 is still being worked on.  Keep an eye out for changes coming to the panel printed parts, as well as some coming mods from the community.  In the interest of encouraging more Doom builds, as well as more mods, a complete DOOM CAD file is now available with all the Doom and Voron components together.  Find it in the CAD folder with all the individual component CAD files.  Now that this is done, work can begin on making the whole project polished and cohesive.  This means finding all the missed chamfers and fillets, making the holes all the correct size, etc.  These changes will be posted to the CAD and STL folders as they are made.  

### CAD Notes
If you examine the complete CAD file you will see it is not limited to the basic DOOM and Voron components.  Included are two optional gantry variants, with a handful of popular community produced V2 mods installed.  The file is structured to be very easy to see what you want, and hide what you don't.  I have been unable to export a step file containing the complete cad small enough to load onto github.  I am working on a solution to that.  The f3z will have to do in the mean time.  

DoomCube is an excellent mod on it's own.  But Doomcubing is a great time to install several mods, while you have things partially disassembled.  The optional modded sample gantries in the complete cad file contain the following excellent mods:
(big thanks to all original authors for permission!  Always follow the links to their respective repos for the latest stl's and info on how to best make use of their mod)

#### Afterburner MGN12 Gantry
-Ark's MGN12 Mod	https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12
-Hartk's GE5C Spherical Z Joint Mod   https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_GE5C
-Hartk's Pin Mod (X/Y Joints, ,A/B Drive Frames, A/B idlers, Z idlers)	https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Pins_Mod
-whoppingpochard's Gantry Rail Backers Mod	https://github.com/tanaes/whopping_Voron_mods/tree/main/extrusion_backers


#### Mantis MGN12 Gantry
-Long's Mantis Toolhead Mod	https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Long/Mantis_Dual_5015
-Hartk's GE5C Spherical Z Joint Mod	https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_GE5C
-Hartk's Pin Mod (X/Y Joints,A/B Drive Frames, Z idlers)	https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Pins_Mod
-whoppingpochard's Gantry Rail Backers Mod	https://github.com/tanaes/whopping_Voron_mods/tree/main/extrusion_backers
-Phalanx's Other Idlers Mod	https://github.com/selliott79/Other-V2-Idlers

#### Omnipresent Mods
The following mods are present in all Doomcube variants in the complete CAD file.  These mods rock!
-L.e.o.p.a.r.d and Hartk's Sexbolt Z Endstop Mod	https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_SexBolt_ZEndstop
-josar's Klicky Probe Mod   https://github.com/jlas1/Klicky-Probe  
(OK Klicky and sexbolt aren't in there yet but I didn't want to keep people waiting.  I'm working on getting them installed next. -KM)

##### A set of stl checklists to match these mod sets is in the works.  That can be one of the most confusing parts of building up a modded printer from scratch, or doing many mods at once with redundant components.  Hopefully a few checklists will simplify things a little bit.  A huge debt is owed to all the mod makers and their willingness to share their work!  Keep up the good work y'all!