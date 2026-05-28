<img width="720" height="1104" alt="Zine" src="https://github.com/user-attachments/assets/13b83ce3-e70f-47e5-935b-8590749b3c1d" />

# HexaHub-v2

NOTE: This is still a WIP project. Follow at your own risk!

A USB 2.0 Hub using the SL2.1A which has 4 downstream USB-A port and USB-C upstream port, with ESD and overcurrent protection enclosed in a 3D printed case with a hexagon-shaped PCB.

This USB Hub was made because of unavailability of the SL2.1S IC, which was used in the previous version and also as an improved version with polyfuses and ESD protection diodes.

This Hub was designed using KiCad and Autodesk Fusion for PCB and CAD Design. Fusion was also used for the case renders.

Made for Hack Club Fallout.

# PCB

- Schematic
<img width="1159" height="826" alt="image" src="https://github.com/user-attachments/assets/c0528142-8e69-4364-a212-0df91dc4e0fd" />

- PCB without Ground Plane
<img width="983" height="600" alt="image" src="https://github.com/user-attachments/assets/b5181329-2cee-4c58-9fd5-36b3414c4926" />

- Overall PCB
<img width="1037" height="641" alt="image" src="https://github.com/user-attachments/assets/8f3a90b3-b7d0-467b-8289-cf1a5da0860d" />

# CAD

- Full Assembly
<img width="1053" height="710" alt="image" src="https://github.com/user-attachments/assets/94202c58-15c5-4a8d-b3b5-4d26041acfa3" />

- Exploded View
<img width="832" height="674" alt="image" src="https://github.com/user-attachments/assets/ac8a5b1e-4998-4d0b-917d-ba2f98b2d712" />

# Renders
- Enclosed
<img width="2048" height="1536" alt="HexahubV2_2026-May-25_07-50-50AM-000_CustomizedView698346096" src="https://github.com/user-attachments/assets/0ec75e2d-7d57-4a21-9361-f4d4ceac58f6" />
- Exploded
<img width="2048" height="1536" alt="HexahubV2_2026-May-25_08-39-06AM-000_CustomizedView19009070130" src="https://github.com/user-attachments/assets/dae30415-6c82-4f71-a0fb-049ab90b2ba6" />

# Build Guide
- Acquire your parts from your favourite platform.
- Order the PCB from your manufacturer
- Solder the components to the PCB
- 3D print the case, place PCB in the bottom, then close the top.
- Done!
If any footprints or 3D models are missing, you may use the footprints, symbols etc. from the Assets folder. Check your project folder and paths before importing.

# Bill of Materials

| MPN | Designator | Package | Quantity | Unit Price | Price (Ext.) | LCSC Link |
|---|---|---|---|---|---|---|
| SL2.1A | U1 | SOP-16 | 5 | 0.2677 | 1.34 | https://www.lcsc.com/product-detail/C6798314.html |
| 10.0 QHHTZB6.3 | J1 | SMD | 10 | 0.0665 | 0.67 | https://www.lcsc.com/product-detail/C668591.html |
| 676430910 | J2, J3, J4, J5 | Through Hole, Right Angle | 4 | 0.9415 | 3.77 | https://www.lcsc.com/product-detail/C2798029.html |
| 1206L200/24NR | F1 | 1206 | 5 | 0.1404 | 0.70 | https://www.lcsc.com/product-detail/C42396578.html |
| 1206L005/110WR | F2, F3, F4, F5 | 1206 | 5 | 0.1387 | 0.69 | https://www.lcsc.com/product-detail/C46422913.html |
| PRTR5V0U2X-ES | D1, D2, D3, D4, D5 | SOT-143 | 5 | 0.0404 | 0.20 | https://www.lcsc.com/product-detail/C5180302.html |
| X32258MOB4SI | Y1 | SMD3225-4P | 5 | 0.1738 | 0.87 | https://www.lcsc.com/product-detail/C2682775.html |
| RC0603FR-075K1L | R1, R2 | 0603 | 100 | 0.0018 | 0.18 | https://www.lcsc.com/product-detail/C105580.html |
| CL10A106KP8NNNC | C1, C2, C3, C4, C5, C6 | 0603 | 20 | 0.0108 | 0.22 | https://www.lcsc.com/product-detail/C19702.html |
| CC0402JRNPO9BN220 | C7, C8 | 0402 | 100 | 0.0012 | 0.12 | https://www.lcsc.com/product-detail/C106203.html |
| JLCPCB(PCB+shipping) | - | - | 5 | 4.66 | 14 | jlcpcb.com
| Total | - | - | - | 22.76 | - |
Apart from the IC, you may choose any brand of parts but with same package.
