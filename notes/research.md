# Research for Plasmasta

## Mindmap

### Machinisation (CAM?)

- DXF -> [CAM ?] -> Toolpath? / G/M-Code
- Nesting?

- Piercing timing
- Lead in / out timing
- Lead in sizing for smaller cut
- Cut ordering
- Corner looping to avoid corner rounding

- Z control? or AHC/THC (Automatic/Torch Height Control)

Softwares:
- BobCAD-CAM
- SheetCAM

### Control

Brain:
- dedicated controller board?
- Standard PC with interface board?
- Embedded PC?

User Interface:
- PC itself?
- Small LCD screen + big button?


- End switches?
- Z reference?

Step motor control:
- microstep?
- feedback?
- vibration control?
- lifetime of module? spare?

Plasma:
- How to control the damn thing?
- feedback?
- AHC -> adjust the height based on voltage

Softwares:
- CandCNC / CommandCNC
- MAch3 ?

### Table

Base

- Base –> rigid steel frame
- Bucket to collect cut pieces?
- Or water surface to cooldown?
- How to move it? Wheel?
- Low plate to install the plasma generator?

Rails / Motors

- NEMA23 ok?

- cremaillere?
- courroie?
- separate motorisation for both side?

- Z axis ?

- Kit from ebay? with alu square 50x50mm

### Calibration

- How to set the reference plane ?
- How to define

### Details

- Mach3 (familiar for custom CNC)
- Mach4 newer, but need a driver for the interface

- Use a game controller (PS/XBOX) for the joystick

- Emergency stop -> big red button
  cut the motors. how to cut the plasma torch?

- Second head like laser for engraving?

- Cisaille mode? Specify width, then automatic detection of the position/presence of material

- Grounding the table is very important

- "IMHO the mach 3 THC is terrible and I never could get it work properly"

- Steel gantry better than aluminum (from https://www.trucutcnc.com/s1.html)

- Normally Close (NC) switches are safer for limit switches (trip if cables break)


## Links

https://nraynaud.github.io/webgcode/
https://github.com/fragmuffin/pygcode

board and software - https://planet-cnc.com/

https://buildyourcnc.com
http://chilipeppr.com/grbl
http://linuxcnc.org/docs/html/gcode.html
https://github.com/Protoneer/Raspberry-Pi-CNC
http://www.instructables.com/id/Raspberry-Pi-Alamode-CNC-Controller/

## References

- http://www.plasmaspider.com/
-
- pro cheap tables: https://www.trucutcnc.com/s1.html

- https://planet-cnc.com/tag/plasma-cutting/

- https://makezine.com/2016/08/29/cnc-plasma-cutter-3000/ 3000$ ?
- http://bobcad.com/cnc-software-for-the-g-code-programming-of-cnc-plasma-machines/
- https://www.sheetcam.com/features/plasma
- https://www.candcnc.com/store-home/bladerunner-dragon-cut-servo-system-4-with-3-gearheads-dthciv-ethercut/

- http://openbuildspartstore.com/cnc-xpro-v3-controller-stepper-driver/
