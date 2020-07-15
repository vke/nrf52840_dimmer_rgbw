# KiCad source files for nrf52840-based RGBW dimmer project.

Available firmware:

https://github.com/vke/nrf52840_dimmer_rgbw_thread (Thread/OpenThread)

https://github.com/vke/nrf52840_dimmer_rgbw_zigbee (ZigBee, incomplete due to a lot of bugs in ZBOSS ZigBee SDK)

Motherboard with nrf52840 (version 2.05):

https://github.com/vke/EFEKTA-nRF52840-MINI-DEV-BOARD

# Images:

![bottom](/doc/bottom.png?raw=true "bottom")
![top](/doc/top.png?raw=true "top")
![bottom pcb](/doc/bottom-pcb.png?raw=true "bottom pcb")
![top pcb](/doc/top-pcb.png?raw=true "top pcb")

# BOM:

Q5; "digital" transistor:

https://lcsc.com/product-detail/Digital-Transistors_Leshan-Radio-LMUN2233LT1G_C12777.html

R10, R16; 0805, 1%, 22.1K:

https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0805W8F2212T5E_C17552.html

Q1-Q4; any suitable mosfet:

https://lcsc.com/product-detail/MOSFET_Infineon-Technologies-BSC067N06LS3G_C24199.html

https://lcsc.com/product-detail/MOSFET_Infineon-Technologies-BSC022N04LS_C148266.html

C4; 0805, 1uF:

https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL21B105KBFNNNE_C28323.html

C1, C6, C10, C14; 0805, 4.7 uF:

https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_TDK-C2012X7R1V475KT000E_C76651.html

https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL21A475KBQNNNE_C98192.html

https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Murata-Electronics-GRM21BC71H475KE11L_C162320.html

C5; 390 uF, 25V:

https://lcsc.com/product-detail/Solid-Polymer-Electrolytic-Capacitor_NCC-Nippon-Chemi-Con-APSG250ELL391MJB5S_C133441.html

C2, C7, C11, C12, C13; 0805, 0.1 uF:

https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL21B104KBFNNNE_C136621.html

C15; 47 uF, 10V:

https://lcsc.com/product-detail/Tantalum-Capacitors_KEMET-T520B476M010ATE035_C141441.html

U1, U2; TC4427 mosfet drivers:

https://lcsc.com/product-detail/MOS-Drivers_Microchip-Tech-TC4427COA713_C144205.html

R9, R15; 0805, 1%, 100K:

https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0805W8F1003T5E_C149504.html

U4; TPS54202 step-down converter:

https://lcsc.com/product-detail/DC-DC-Converters_Texas-Instruments-TPS54202DDCR_C191884.html

R1-R4; 0805, 200R:

https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0805W8J0201T5E_C25292.html

R5-R8; 0805, 10K:

https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_SANYEAR-SY0805JN10KP_C380776.html

L2; 10uH 1.5A:

https://lcsc.com/product-detail/Inductors-SMD_GLE-GCNR4030-100MC_C439346.html
