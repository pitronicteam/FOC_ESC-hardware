# Change LOG

## 09/15/2019-File structure clean up

+ Add a new hardware design based on STM32G431.
+ Clean up the old file structure.

## 06/16/2019-v1.2 Changes from v1.1.x
+ Named the board as CruxOne
+ Fixed some bugs to avoid incorrect processing when producing PCBs.
+ Added a boot pad broke from AIO6 (hold 8s to reset) .
+ Added an LED to indicate the working status of VSYS.
+ Added a logo.
+ Removed NC 3V3 from SWD connector, replace it with 5V (according to the datasheet, 3v3 can't initialize the microcontroller but 5V can) .

And as always, screenshots of PCB with silksreen shown as below:

![CruxOne_v1.2_top_with_silkscreen](PAC5523/images/CruxOne_v1.2_top_with_silkscreen.png?raw=true "CruxOne_v1.2_top_with_silkscreen")
![CruxOne_v1.2_bottom_with_silkscreen](PAC5523/images/CruxOne_v1.2_bottom_with_silkscreen.png?raw=true "CruxOne_v1.2_bottom_with_silkscreen")

## 05/26/2019-v1.1.1 Changes from v1.1
+ Added silkscreens for almost all components
+ Added two screenshots for quick review

![FOC_ESC_v1.1.1_top_with_silkscreen.png](PAC5523/images/FOC_ESC_v1.1.1_top_with_silkscreen.png?raw=true "FOC_ESC_v1.1.1_top_with_silkscreen.png")
![FOC_ESC_v1.1.1_bottom_with_silkscreen.png](PAC5523/images/FOC_ESC_v1.1.1_bottom_with_silkscreen.png?raw=true "FOC_ESC_v1.1.1_bottom_with_silkscreen.png")

## 05/09/2019-v1.1 Changes from v1.0
+ Added a TVS diode across input
+ Removed MOSFETs' pulldown resistors
+ Added some test points
+ Broke out serial interface
+ Redesigned the layout of electronic components
+ Reduced the number of layers to 4
