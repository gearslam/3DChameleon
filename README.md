# 3DChameleon
Klipper direct stepper  control for 3DChameleon

Setup for Ender 3 Max Neo, with Sprite Extruder Pro with K1 Hotend, silicone wipe purge bucket, and BTT SKR3 EZ with BTT_MOT_EXP expansion module.
ysplit_distance is configured for custom y-splitter, 2in1 & 4in1 Splitter by Solidoodle2 on Thingiverse: https://www.thingiverse.com/thing:3490163
distance will need to be increased for original 3DChameleon Y-Splitter.

TOOL_INIT there is a configuration value that needs to be adjusted for proper filament selection.

Purge Bucket for CR-10 with adjustable X-Axis by randyre on Thingiverse: https://www.thingiverse.com/thing:4134504
For K1 or volcano nozzle purge wipe bucket needs to be trimmed down about 6mm using negative parts volume in slicer.

PrusaSlicer Start G-code:
START_PRINT EXTRUDER_TEMP={first_layer_temperature[0]} BED_TEMP={first_layer_bed_temperature[0]}
T{initial_tool}

Filament Change withe Purge and Wipe is 15 seconds.
