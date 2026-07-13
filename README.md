# Compliant-Pin-Mounting-Replacement

## Overview
This project is a reverse-engineered replacement for a failed factory mounting pin. The goal is to reproduce the original compliant mechanism while improving durability and ease of removal.

## The problem
The factory mounting pins broke due to mechanical stress. A replacement part was designed to replicate the original function while maintaining their compliant properties.
![original part](Images/originalPart.jpg)

## Material
PLA was chosen for the initial design due to:
- low-cost
- ease of manufacturing
- good dimensional accuracy
- sufficient mechanical properties for compliant design
For the final version tougher materials like ABS or NYLON may be considered.


### Printing
- Printer: Bambu Lab A1
- Nozzle: 0.2mm
- Layer height: 0.1mm
- Orientation: printed horizontally on its longest side to align layers with the expected tensile and shear stress

### v0.1 Initial Prototype
Initial measurements were taken with digital calipers. The focus of the initial prototype is on replicating the compliant part.

The first prototype was undersized, multiple scaled versions were printed:

| Scale | Result |
|---|---|
| 120% | Too small |
| 125% | Optimal balance between fit and removability |
| 130% | Tighter fit |
| 135% | Secure connection but difficult to remove |
| 140% | Too large to fit |

![sizes tested](Images/v0.1_differentSizes.jpg)

Based on the tested scaling factors 125% was chosen as the most balanced option but 130% may be considered in the future.

![chosen size](Images/v0.1_chosenSize.jpg)

#### Planned Changes
##### Removal Mechanism
Initial prototype require partial disassembly to remove. Planned improvements:
- Adding a ramp to the back side of the pin
- Lengthening the opening
##### Strength Improvements
- Narrowing the opening to improve strength as the additional compliance was found to be unnecessery
##### Mounting Interface
- Adding the mounting system.

### v1.1
The added backramp and line holder function as intended.
However the adjusted gap is too small and requires a large amount of force to put it and remove.

#### Planned Changes
- Widen the gap to allow for easier addition and removal
- Make the pins shaft shorter to better match the original part in length


