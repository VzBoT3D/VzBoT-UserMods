VZ Sexbolt Sidepiece Z Endstop swich
Switch is a mod of the Voron 2.4 Sexbolt Z endstop by Hartk and uses it's internal components. 
https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202-Trident/2.4/Voron2.4_SexBolt_ZEndstop

It's designed to mount to the inside edge of the VZ bed frame so the print head can reach the switch to probe the nozzle.
Replace the normal M4x10MM screw in the Voron Sexbolt kit with a M4x20 cap screw. This compensates for the added length of the switch housing. 

Klicky Probe
https://github.com/jlas1/Klicky-Probe

Githib for the Auto Z offset for Klipper
https://github.com/protoloft/klipper_z_calibration#how-to-test-it

Klicky probe kit from DeepFriedHero
https://deepfriedhero.in/products/klicky-probe-kit?_pos=1&_sid=3162f024a&_ss=r

Voron Sexbolt switch component kit from DeepFriedhero
https://deepfriedhero.in/products/voron-2-4-sexbolt-z-endstop-super-kit?_pos=1&_sid=2edcd4e6b&_ss=r

Sample config segments you find helpfull.

[stepper_z]

endstop_pin: P1.29
position_endstop: 1.34
homing_retract_dist: 5.0
homing_speed: 5.0
second_homing_speed: 2.5

[z_calibration]
nozzle_xy_position:   332,168
switch_xy_position:   314,150
bed_xy_position:      150,150
switch_offset:        0.4
max_deviation:        1.0
samples:              3
probing_first_fast: false
start_gcode:          ATTACH_PROBE
end_gcode:            DOCK_PROBE

[bed_mesh]
speed: 120
probe_count: 5,5
relative_reference_index: 12
horizontal_move_z: 10
algorithm: lagrange
mesh_min : 20,20
mesh_max : 290,290
mesh_pps: 0

[probe]
x_offset: 10
y_offset: 10
pin: sht36:PA1
z_offset:  4.03
speed: 5.0
samples: 3
samples_result: median
sample_retract_dist: 5.0
samples_tolerance: 0.01
samples_tolerance_retries: 3
