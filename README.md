XOL CPAP toolhead, LGX Lite PRO, Rapido 2F UHF.


Orcaslicer print start gcode.

M104 S120
M190 S[bed_temperature_initial_layer_single]
M140 S[first_layer_bed_temperature]
PRINT_START
SET_MATERIAL MATERIAL='{filament_type[initial_extruder]}'
PRINT_START EXTRUDER=[first_layer_temperature] BED=[first_layer_bed_temperature] CHAMBER=[chamber_temperature] NOZZLE={nozzle_diameter[initial_extruder]}
