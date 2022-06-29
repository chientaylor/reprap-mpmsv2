# Links to Generator

https://configtool.reprapfirmware.org/

**Note: Apparently, different MPMSV2 Printers will have their motors in different orientations. Check before you try anything.

## Relavent Settings

|Board Slot  |Where it Goes      |Extra bits |
|------------|-------------------|-----------|
|Driver_0    |X-Axis             |Backwards  |
|Driver_1    |Y-Axis             |           |
|Driver_2    |Z-Axis             |Backwards  |
|Driver_3    |Extruder           |Backwards  |
|Out_1       |Bed Heater         |           |
|Out_2       |Hotend Heater      |           |
|Out_3       |Hotend Cooling Fan |Always On  |
|Out_4       |80mm Cooling Fan   |           |
|Out_5       |40mm Cooling Fan   |Always On  |
|Out_6       |Part Cooling Fan   |           |
|Temp_0      |Bed Thermistor     |           |
|Temp_1      |Hotend Thermistor  |           |
|IO_2        |Z Endstop          |Active Low |
|IO_5        |X Endstop          |Active Low |
|IO_6        |Y Endstop          |Active Low |

Other settings can be found on the page for the Monoprice Mini Select (Malyan M200): https://mpselectmini.com/specifications