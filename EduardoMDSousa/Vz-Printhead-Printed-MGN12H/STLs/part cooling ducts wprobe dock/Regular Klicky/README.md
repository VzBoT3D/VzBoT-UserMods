Klicky_Trihorn Fan Duct v2

this duct includes a dock for the regular klicky prob.

easy to print and assemble.
duct dock assembly instructions are the same for any regular klicky dock model.

Credits, from the original ductversion, go to Simon Vez

<img width="400" alt="image" src="https://github.com/EduardoMDSousa/VzBoT-UserMods/blob/master/EduardoMDSousa/Vz-Printhead-Printed-MGN12H/Galery/Klicky-regular/Klicky_TrihornFanDuctv2_1.jpg"> <img width="400" alt="image" src="https://github.com/EduardoMDSousa/VzBoT-UserMods/blob/master/EduardoMDSousa/Vz-Printhead-Printed-MGN12H/Galery/Klicky-regular/Klicky_TrihornFanDuctv2_2.jpg">
Print Orientation:
<img width="400" alt="image" src="https://github.com/EduardoMDSousa/VzBoT-UserMods/blob/master/EduardoMDSousa/Vz-Printhead-Printed-MGN12H/Galery/Klicky-regular/Klicky_TrihornFanDuctv2_3.jpg"> 

<img width="300" alt="image" src="https://github.com/EduardoMDSousa/VzBoT-UserMods/blob/master/EduardoMDSousa/Vz-Printhead-Printed-MGN12H/Galery/Klicky-regular/Klicky_TrihornFanDuctv2_4.jpg"><img width="300" alt="image" src="https://github.com/EduardoMDSousa/VzBoT-UserMods/blob/master/EduardoMDSousa/Vz-Printhead-Printed-MGN12H/Galery/Klicky-regular/Klicky_TrihornFanDuctv2_5.jpg"><img width="300" alt="image" src="https://github.com/EduardoMDSousa/VzBoT-UserMods/blob/master/EduardoMDSousa/Vz-Printhead-Printed-MGN12H/Galery/Klicky-regular/Klicky_TrihornFanDuctv2_6.jpg"><img width="300" alt="image" src="https://github.com/EduardoMDSousa/VzBoT-UserMods/blob/master/EduardoMDSousa/Vz-Printhead-Printed-MGN12H/Galery/Klicky-regular/Klicky_TrihornFanDuctv2_7.jpg">

How to assemble

<img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/1.jpg"> <img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/2.jpg">
<img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/3.jpg"> <img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/4.jpg">
<img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/5.jpg"> <img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/6.jpg">
<img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/7.jpg"> <img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/8.jpg">
<img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/9.jpg"> <img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/10.jpg">
<img width="300" alt="image" src="https://github.com/EduardoMDSousa/Vz-Printhead-MGN12H-main/blob/main/Galery/Klicky-regular/how-to/11.jpg">


Added vertion for soldering magnets


Abaut

# Klicky Probe
Microswitch probe with magnetic attachment, primarily aimed at CoreXY 3d printers.

Initially it was focused on the [Voron printers](https://vorondesign.com/) (V2.4, V1.8, Trident, V0) and derivatives, now it's been restructured to better allow other printers to be documented here.

The objectives for this project are:
- drop in replacement for Omron TL-Q5MC2 or PL-08N2 (you don't need to replace the toolhead), replacement of BLtouch probes
- soldering not required
- minimal adjustments required
- be able to detect all the print surfaces
- be as close to the hotend tip as possible
- highly repeatable and accurate probes
- less temperature variations
- no melting of its parts
- cheap to build
- reuse spare parts if possible

Most of the Klicky probe users are using klipper, there are some macros in here that ease the probing process, by automating the attach, dock and use of the probe.

Some work has been developed to have the same functionality on RRF.

It can also be used with the [automatic Z calibration](https://github.com/protoloft/klipper_z_calibration) klipper plugin to effectively calculate the Z offset from the probe and from the Z endstop if your printers supports a Z endstop triggered by the nozzle (like most Voron's do)

The inspiration for the Klicky Probe comes from the [Quickdraw](https://github.com/Annex-Engineering/Quickdraw_Probe) and the [Euclid probe](https://github.com/nionio6915/Euclid_Probe), it uses some concepts from each of the projects.

Updated instructions provided by StefanRaatz.
oc_geek and TurBoxxs were also a great help in refining and testing the CAD files.
Garrettwp provided the initial revised macro files.
User richardjm revised the macro variables and added some functions.
Mental created the initial macro and one of the first magnetically attached microswitch probes.

Without them, and some others this effort would not be in the current state, many thanks to them all.

It is working very well, if you decide to use it, give me feedback, either here, or on discord, my discord user is JosAr#0517.

If you want to donate something regarding this project, use this [link](https://paypal.me/Josar154) or [__Buy me some ABS!__](https://www.buymeacoffee.com/JosAr), thanks

# Upgrading from an earlier version

If you are upgrading from an earlier version, check the [klipper macros](https://github.com/jlas1/Klicky-Probe/tree/main/Klipper_macros) folder, it contains update instructions.

# Probe options

Right now, there are two probe attachment options, each with two probe types.

## Regular Klicky

First klicky probe, based on the [Quickdraw probe](https://github.com/Annex-Engineering/Quickdraw_Probe), with an added third magnet for added stability and fixed dock gantry setups.

<img src="https://github.com/jlas1/Klicky-Probe/blob/main/Probes/KlickyProbe/Photos/KlickyProbe.png" alt="klickyprobe" style="zoom:50%;" />

It uses magnets to secure the probe to the mount and also to make the electrical connection.
The magnets can be glued to prevent them from coming loose.

# Klicky components

All the compatible printers require:

* Toolhead mount (the thing that the probe attached to when it's being used)
* Klicky probe (there are three versions, all are interchangeable and compatible, more information on the specific printer page), what actually is used to probe the bed
* Probe dock (all the printers use the same)
* Probe dock mount (what attaches to the printer to dock the probe when not in use)

The CAD with all the files is located [Here](https://github.com/jlas1/Klicky-Probe/tree/main/CAD)

KlickyProbe STL's are now located on each probe type directory.

Printer specific STL are in each printer directory.

The klipper macros are ![here](https://github.com/jlas1/Klicky-Probe/tree/main/Klipper_macros), the RRF ![here](https://github.com/EduardoMDSousa/Klicky-Probe/tree/main/RRF_macros).


## Probe accuracy

The probe accuracy output is better than a range of 0.025mm (difference between highest and lowest), and a standard deviation of 0.01mm.



## Print Settings

There are no need for supports, recommended settings are 4 perimeters/top/bottom, at least 23% infill, the STL's are already oriented, you only need to send them to the slicer.

![here](https://github.com/EduardoMDSousa/Klicky-Probe/blob/main/Photos/Klicky_Probe_recommended_printing_orientation.png)

Each printer family/version has it's own mounting options, Bill of Materials, assembly instructions and dock/attach setup.

# General Bill of Materials (BOM)

Tools:

- 1.5mm Drill (optional)
- Multimeter to check for Continuity 
- Super Glue
- Soldering Iron for the heat inserts

Probe BOM:

- 1x microswitch (the omron D2F-5 or D2F-5L (removing the lever) is recommended), D2F-1 and similar sizes microswitch also work
- 2x M2x10 mm self tapping
- some 6 mm x 3 mm magnets (it ranges from 8 to 10)
- some m5 screws
- some m3 screws
- some m3 heat inserts
- some m3 nuts

# Sourcing guide



