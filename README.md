# 3KU_K-3000_marlin_configs
3KU K-3000 Delta 3D printers Marlin 1.1.9 configs, with added E3D V6 hotend, Titan extruder and TMC2130 drivers.

Titan mounting:

![titan](https://raw.githubusercontent.com/Jurevic/3KU_K-3000_marlin_configs/master/img/titan_mount.jpg)

E3D V6 mounting:

![v6](https://raw.githubusercontent.com/Jurevic/3KU_K-3000_marlin_configs/master/img/v6_mount.jpg)

For TMC2130 please note that X_CS_PIN and Y_CS_PIN are remaped in pins_RAMPS.h becouse of LCD screen connector, as shown here:

![tmc2130](https://raw.githubusercontent.com/Jurevic/3KU_K-3000_marlin_configs/master/img/tmc2130_conn.jpg)

More info on [RAMPS With TMC2130](https://www.instructables.com/id/Upgrading-RAMPS-14-With-TMC2130-Stepper-Drivers/)

Active cooling for TMC2130 running on 12v is required.