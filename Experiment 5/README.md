# Design and Develop a PCB Board

## Aim:
To design and develop a PCB board for any specific application.

## Design Steps:
1. Design the schematic using Eagle.
2. Create the PCB layout in Eagle, ensuring proper component placement and trace routing.
3. Generate Gerber files in Eagle for manufacturing.
4. Import the Gerber files into CopperCAM and generate GCODE.
5. Set up the PCB prototyping machine and load the PCB blank.
6. Load the GCODE into the machine's control software.
7. Run the machine to mill traces, drill holes, and cut out the PCB.

## G-Code:
### Drill
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM2\CopperCAM.iso created 14/06/2023 at 11:44 )
( Workpiece dimensions: 84.76 x 62.22 x 0.1 mm )
G21 G40 G54
G80 G90 G94
( Tool #3 "Basic Drill" / Diameter 0.8 mm )
T3 M06
M03 S12000
M07
G00 X38.978 Y51.863
G00 Z0
G01 F60 Z-0.1
G01 F300 X39.293
G02 I-0.315 J0 X39.293 Y51.863
G00 Z2
G00 X35.016
G00 Z0
G01 F60 Z-0.1
G01 F300 X35.33
G02 I-0.315 J0 X35.33 Y51.863
G00 Z2
G00 X31.053
G00 Z0
G01 F60 Z-0.1
G01 F300 X31.368
G02 I-0.315 J0 X31.368 Y51.863
G00 Z2
G00 X32.628 Y42.973
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X40.248
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X46.598 Y36.623
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X49.138
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X61.838 Y39.163
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X64.378
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X71.998 Y36.623
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X79.618
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X78.348 Y29.002
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X70.728
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X69.458 Y23.923
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X71.998 Y17.573
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X70.728 Y12.493
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X75.3 Y6.524
G00 Z0
G01 F60 Z-0.1
G01 F300 X75.497
G02 I-0.197 J0 X75.497 Y6.524
G00 Z2
G00 X77.84
G00 Z0
G01 F60 Z-0.1
G01 F300 X78.037
G02 I-0.197 J0 X78.037 Y6.524
G00 Z2
G00 X78.348 Y12.493
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X79.618 Y17.573
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X61.838 Y23.923
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X60.568 Y12.645
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 Y7.26
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X35.168 Y23.923
G00 Z0
G01 F60 Z-0.1
G00 Z2
G00 X32.628
G00 Z0
G01 F60 Z-0.1
G00 Z2
M09
M05
M02
%
```
### Cutout
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM2\CopperCAM.iso created 14/06/2023 at 11:45 )
( Workpiece dimensions: 84.76 x 62.22 x 0.1 mm )
G21 G40 G54
G80 G90 G94
( Tool #2 "Basic Cutter" / Diameter 3 mm )
T2 M06
M03 S12000
M07
G00 X1.04 Y1.04
G00 Z0
G01 F60 Z-0.1
G01 F300 X83.72
G01 Y61.18
G01 X1.04
G01 Y1.04
G00 Z2
M09
M05
M02
%
```

## Schematic Layout:
![14-06-2023 schematic](https://github.com/Marinto-Richee/Embedded-System-Design/assets/65499285/93c00ae1-30c3-41d3-b38a-5473d1e45d05)

## PCB Layout:
![14-06-2023 layout](https://github.com/Marinto-Richee/Embedded-System-Design/assets/65499285/920d3aa8-7cda-4f42-8e26-e178141e66a1)

## CopperCAM Output:
![14-06-2023 Board](https://github.com/Marinto-Richee/Embedded-System-Design/assets/65499285/b7b34379-89be-4956-9afd-28974be78ffd)

## Manufactured PCB:
![image](https://github.com/Marinto-Richee/Embedded-System-Design/assets/65499285/e93469dd-a8f9-4f7e-b185-80010be7771e)

## Result:
Thus, a PCB board is designed and developed for a specific application.
