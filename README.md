![Toolhead](https://img.shields.io/badge/Toolhead-RapidBurner-blue)
![Belts](https://img.shields.io/badge/Belts-9mm-brightgreen)
![Belts](https://img.shields.io/badge/Belts-6mm-green)
![Hotend](https://img.shields.io/badge/Hotend-Rapido%202%20UHF-orange)
![Hotend](https://img.shields.io/badge/Hotend-chcXL-orange)
![CPAP](https://img.shields.io/badge/4010-Ready-cyan)
![Status](https://img.shields.io/badge/Status-Ready-Green)
![Status](https://img.shields.io/badge/Status-MILF-blue)
-------------------------------------------------------------------------------------------------

<img width="1983" height="793" alt="223f9bb9-dabb-4646-a062-f38930a52731" src="https://github.com/user-attachments/assets/3a071399-5f96-4e7a-b110-da3b01cb0308" />


# Save the Rapid Burner... Same Campaign as "Save the StealthBurner" but Chirpy 

Same rules as SB-COM....

We design, rework, print, weigh, adjust, implement, check COM

This is an intensly time consuming project and I for one do not wnat to develop this for every single hotend out htere. so... if you want to take a stab at it please do it. 

RB-COM is currently ONLY for Mellow Goliath / CHC-XL hotends. I plan on developing this for the Rapdio 2 UHF hotends as well. 

## COM Calibration Method

Before we dive in:

Fusion 360 calculates **solid mass (no air)**.  
3D printed parts are not solid — even at 100% infill — so calculated weights are inaccurate.

To fix this:

- Printed a real part  
- Measured actual weight  
- Back-calculated density for accurate COM simulation
- New Density = Current Density × (Target Mass ÷ Current Mass)​

## Check out my Fusion 360 Density calculator here: https://thevoronmodder.github.io/SB-COM/

---

### Print Settings Used

- 4 walls  
- 4 top / bottom layers  
- 40% rectilinear infill  
- 0.4 mm nozzle  
- Ambrosia ASA  

<img width="3000" height="700" alt="COM Weight Issues" src="https://github.com/user-attachments/assets/ddc78743-416e-417e-9333-a8aa3d476adc" />

## Image shows the weight variance between CAD and SLICER... The real world weights found below are from using my wifes Sourdough kitchen scale 🤣
---

## Important Component Weights

| Component | Weight |
|----------|--------|
| ECAS fitting | 1 g |
| Cartographer v3 | 4 g |
| 4010 Winsinn fan | 11 g |
| Standard 4010 fan | 13 g |
| Rapido 2 UHF | 47 g |
| LDO-36STH20-1004AHG | 85 g |

## Important Printed Part weights:
These are all printed using Ambrosia ASA Filament, please note your filament weights may be slightly different due to filament manufacturing and filament mix, Ambrosia is known to have some PETG very minimal though.

| Component                                   | Weight                                                                 | Notes                          |
|--------------------------------------------|--------------------------------------------------------------------------|----------------------------------|
| Rapdio 2 UHF 6mm Voron Style Back Plate | 26g (printed total weight) - 5 walls, 5 top/bottom 100% rectilinear infill | Reflected in Fusion CAD file |
| CW3 Cover NON MMU | 20g (printed total weight) - 5 walls, 5 top/bottom 20% rectilinear infill | Reflected in Fusion CAD file |
| CW3 Counter Weight | 18g (printed total weight) - 5 walls, 5 top/bottom 100% rectilinear infill | Reflected in Fusion CAD file |


