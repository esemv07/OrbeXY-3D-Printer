# OrbeXY 3D Printer  <img src="https://imgproxy.attic.sh/J0q85Odp_n0Dnz9TO92wiwIQ-JiZ9BF4dwz4huLeQFI/rs:fit:768:768:1:1/t:1:FF00FF:false:false/pngo:false:true:256/aHR0cHM6Ly9hdHRp/Yy5zaC84MGs0d3d3/cDltMGJ5dThkYXFp/MGo0cHJ6YXo5.png" width="40">⚙️🛠️

A fully DIY 3D printer that I designed


## <img src="https://imgproxy.attic.sh/j5JHPIk7QB0ASMlUIvgOEh2AaUaYaIJwSPbzzrfdK8A/rs:fit:768:768:1:1/t:1:FF00FF:false:false/pngo:false:true:256/aHR0cHM6Ly9hdHRp/Yy5zaC9ydW5wb2Qv/ODA3MjQyMjEtOGMy/Yy00ZTYxLWE0NDYt/Y2RlZGQ3ZGE0NDRm/LnBuZw.png" width="30"> Overview

This is a small CoreXY 3D printer that I have designed from scratch including designing the Toolhead, Bed Assembly, Gantry and Belt System, as well as the Optical Endstops. See my journey of designing and building the printer [here](https://github.com/esemv07/OrbeXY-3D-Printer/blob/main/JOURNAL.md). This printer costs under $476.04AUD ($300USD). See my list of materials and prices [here](https://github.com/esemv07/OrbeXY-3D-Printer/blob/main/BOM.md).

## ✨ Key Features

- CoreXY Kinematics
- 100mm<sup>3</sup> Build Area
- Under 250mm<sup>3</sup> Full Size
- Runs Klipper
- Remote Printer
- Pico MMU Compatible
- NEMA 14 Stepper Motors used for the X and Y Axes
- NEMA 17 Stepper Motor with Lead Screw used for the Z Axis
- Optical Endstops for Homing


## 🏆 Goals

For this printer there were a few things that I wanted to achieve:
1. ***A Compact Overall Size:*** I wanted this printer to fit into small desk space so that people can have easy access to printing without having to have a big area dedicated to the printer. I wanted the build area to also be fairly small, at 100mm<sup>3</sup>, making the printer suitable for quick, and small prints. A lot of the choices I made while designing this printer centred around having a compact size while still preserving the full 100mm<sup>3</sup> build area.
2. ***Runs Klipper with Remote Printing:*** I wanted the printer to run Klipper to improve the overall easy and quality of the printer. On top of this I wanted to have remote printing, so that you can start prints from anywhere and come home to an already started, or even finished print. This meant I had to consider the hardware I was using and how I could configure these parts into the Klipper software. This includes the Optical Endstops, which I designed myself, which will be configured to the Klipper file.
3. ***Pico MMU Compatible:*** I also wanted this printer to be able to print multicoloured if desired. To achieve this I have made the printer compatible with the Pico MMU, meaning that multicoloured prints can be printed if desired. This also meant that in the Klipper configuration file, I had to configure the MMU to make sure that I could still use it via remote printing.
4. ***Separated Spool Holder:*** I decided that in this printer, I would have the spool holder separate from the main printer. This aligns with my goal for the size constraints meaning that if the user does not have enough desk space for the spool as well, the spool could be stowed underneath the desk even while printing. The spool holder is connected to the printer via bowden tubing that will run from the spool holder, into the extruder. The same will apply for if the Pico MMU is used. The spool holders can stay under the desk as well as the Pico MMU and the bowden tubing will run from the Pico MMU to the extruder.


## 📋 Checklist

### Design:
- [x] Toolhead
- [x] Bed Assembly
- [x] Z Axis System
- [x] X and Y Axis Belt System
- [x] Screen Holder
- [ ] Motherboard and Battery Mount
- [ ] Spool Holder
- [ ] Full CAD Model

Here is the [link](https://a360.co/3FXQvPA) to my live updating Full CAD Model!

### Firmware:
- [ ] Remote Printing
- [ ] Configured Optical Endstops
- [ ] Pico MMU Configured
- [ ] Full Klipper config File

### Build:
- [ ] Assemble Gantry
- [ ] X and Y Axis Belt System
- [ ] Z Axis Assembly
- [ ] Bed Assembly
- [ ] Screen and Electronics
- [ ] Full Build

### Tuning:
- [ ] To be added

## 📸 Photos

### Design:

Will add when it is finished

### Build:

Will add as I build it
