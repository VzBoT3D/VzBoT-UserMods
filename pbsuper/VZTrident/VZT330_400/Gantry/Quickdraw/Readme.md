Quickdraw mount for VZbot Alu Printhead.

Quickdraw 1 is the original older version. We have since updated to Quickdraw 2 and i would recommend everyone to use that.


Strip 2 24AWG wires for about 2cm twist the wire so no strands are loose and stick it in the back of the Quickdraw mount. Cut wires flush with magnets after they have been added into the mount and put a dot of glue on the wire where it enters the Quickdraw Mount. For added security you can add a tiny dot of solder onto the wire/magnet where they touch. be carefull not to heat the magnet since it will loose it's strength then.

The printed Printhead version is made for the backplate without tensioners. If you still tension your belts at the backplate this won't fit.

QD1 BOM
```
6x3mm Magnets 6x
M3 Heat inserts 8x
15cm 24AWG wire 2x
M2x10mm socket head NOT RVS/Stainless. Needs to be attracted to magnets.
Omron D2F-5 1x
```

QD2 BOM
```
6x6mm Magnets 4x
M3 heat inserts 5x
15cm 24AWG wire 2x
Omron D2F-5 1x
6x3-3mm ring magnets 2x [ring magnet](https://www.aliexpress.com/item/1005003026319118.html?)
M3x8mm Ultra Flat Head bolt Black 2x [Ultra Flats](https://a.aliexpress.com/_uH3ne5)
M3x12mm Button head or Ultra flat head 1x
M2x10mm socket head NOT RVS/Stainless. Needs to be attracted to magnets.
```

To use quickdraw a module needs to be added.

SSH into your Pi with a application like Putty and type:
```
cd ~/klipper/klippy/extras
wget https://raw.githubusercontent.com/Annex-Engineering/klipper/master/klippy/extras/dockable_probe.py
sudo service klipper restart 
```
For more info go to [Quickdraw](https://github.com/Annex-Engineering/Quickdraw_Probe)
Credits to Annex-Engineering for designing it.

Example Config for VZTrident 400 on BTT Octopus board:
```
[dockable_probe]
pin: PG10 #your probe pin goes here
x_offset: 26 # offset for microswitch x direction off nozzle
y_offset: 56 # offset for microswitch y direction off nozzle
#z_offset: 6.42 # offset for microswitch in z height
samples: 3
sample_retract_dist: 3 # this is so the machine has time for the switch to reset properly, especially with a higher retract speed
samples_result: median
samples_tolerance: 0.04
samples_tolerance_retries: 3
speed: 15 # do not go higher than 10mm/s, you will destroy the switch
lift_speed: 20

dock_position:             390,380, 25 #you need to set these on your own
safe_z_position:           200,200 #used the center of the bed for this
approach_position:		   380,380, 25 #you need to set these on your own
detach_position:		   360,330 #you need to set these on your own
attach_speed:              8
detach_speed:              10
travel_speed:              300
check_open_attach:         True #checks to see if the probe is attached before moving the toolhead, if not retries to pick up the probe
dock_fixed_z:              True # k series printers use a dock fixed in the z axis, this was off a K2
dock_retries:			   3
```
