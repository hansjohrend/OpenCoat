
![OpenCoat_Logo](https://github.com/user-attachments/assets/e859ad37-010b-4dcf-b67d-dabb98fdcab7)

# OpenCoat v0.1.0-beta
This spin coater is based on the [Maasi](https://github.com/klotzsch-lab/Maasi) project from the Klotzsch Lab at HU Berlin.

OpenCoat is a project that aims to improve and to continue developing this project, as the original is no longer actively maintained.

## 1. Improvements:

- added screws to clamp the shaft adapter (i.e. sample holder) to the motor's shaft, as the original was only press fitted to the shaft
- changed the display with a 16x2 LCD as they are easier to source compared to the Nextion touch screens
- added a 3 button interface for navigating through the menu to keep the same form factor of the whole device
- using additional brass inserts for fastening the enclosure parts, like the shell and the base
- addition of 3D pritned TPU feet to dampen vibrations (if sourcing rubber feet is a problem)

![OpenCoat v1](https://github.com/user-attachments/assets/c90bd07d-411e-4615-8bfd-ac04005393a6)

## 2. Future deliverables:

- [ ] CAD file (.step)
- [ ] schematic
- [ ] firmware

## 3. Expected next iterations:

- Mainboard PCB, in order to:
    - minimize the volume taken up by the wiring
    - have an easier assembly experience
    - have a longer lasting device, as some off-the-shelf electronics modules typically used in hobby electronics come from various unknown manufacturers that might overlook quallity assurance
 
- Vacuum sample holding, based on hollow shaft BLDC motors. It should be mentioned that finding a good supplier for hollow motors might prove as a difficult task.
