# OpenPlotter
An open source machine for plotting stuff, this repo is still a work in progress, more parts and drawings will soon be uploaded. 
[Mechanical source files](https://cad.onshape.com/documents/46722cd283d12a82f0ec8435/w/54065c5dafbb0bb403c8ca67/e/3b850448fa15e10835d7a433?renderMode=0&uiState=66955be95deb832b1e9f9248) are available. 

Feel free to open an issue if you encounter any problem. 

# Tools required
-3D Printer
-M6 Tap wrench
-M3, M5, M6 allen Keys
-Soldering iron
-Metal saw
-Power drill + 7mm Metal drill bit

# Bill of materials

## Nuts'n'Bolts Needed

- M3x10mm Hex screws (x50)
- M3 nuts (x8)
- M3 T-Slot nuts (x50)
- M5x8mm Hex screws (x30)
- M5x25mm Hex screws (x10)
- M5x40mm Hex screws (x3)
- M5 Nut (x15)
- M5 T-Slot nuts (x50)
- M6x10mm Hex screws (x6)
- M6x18mm Hex screws (x3)
- M6x35mm Hex screws (x8)
- M5 Wing nuts (x2)
- M3 Nut (x15)
- M6 Washer (x8)

## Aluminium profiles
### 2040 V-slot
- 1000mm (x2)
- 850mm (x1) 

### 2020 V-slot
- 828mm (x1)
- 360mm (x2)
- 190mm (x2)
- 170mm (x2)
- 80mm (x2)
- 60mm (x2)

### 6mm round tube 
- 85 mm (x1)
- 75 mm (x1)

## Other Mechanical parts
- 10 x 10 x 1000 mm Cable chain (x2) [Like this one](https://www.amazon.fr/chudian-10mmx10mm-Transporteur-Imprimante-Machine%EF%BC%8CNoir/dp/B07Y6769LL?pd_rd_w=SgpTm&content-id=amzn1.sym.2feba941-c3ea-43f7-9bb0-8595e66c71e9&pf_rd_p=2feba941-c3ea-43f7-9bb0-8595e66c71e9&pf_rd_r=PNCYDVQPMEP8R8EMBY00&pd_rd_wg=k4awF&pd_rd_r=3dc373b0-0f3b-4564-b3dd-3d22f7814f42&pd_rd_i=B07Y6769LL&psc=1&ref_=pd_bap_d_grid_rp_0_1_ec_pd_nav_hcs_rp_2_t)
- GT2 20Teeth Idler Pulley Bore 5mm (x5)
- GT2 20Teeth Pulley Bore 5mm (x4)
- GT2 6mm wide timing belt (6m minimum)
- OpenBuilds V-Slot Gantry Kits 20 mm (x3) [These little guys](https://openbuildspartstore.com/v-slot-gantry-kit-20mm/)
- PETG 3D printing filament compatible with your printer (1kg)
- 15 x 840 x 1000 mm piece of MDF board
- zipTies : a lot
  

## Electronics
- Arduino UNO (x1)
- Arduino CNC Shield V3 (x1)
- Stepstick A4988 - Stepper motor driver (x4)
- NEMA 17 stepper motor (x4)
- 150W(mini) 24V Power Supply (x1)
- A fan to keep the drivers cool


# Software

This machine uses [GRBL](https://github.com/gnea/grbl) as a firmware, the configuration file is in the software folder. 
In order to send G-code to the machine we use [Universal G-Code Sender](https://winder.github.io/ugs_website/) on a laptop. 
