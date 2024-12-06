# SoMduino
This is a sample design for a _mostly_ assembled PCB from a manufacturing service like JLCPCB, helping you get started with a custom SoM based design. The SoMduino is an Arduino Uno form factor breakout board intended to work with either BSoM or MSoM Particle products.

![particle-somduino-final](https://github.com/user-attachments/assets/60043049-87e8-497d-ab6a-1753abb38832)

## Overview
The SoMduino has the following features:
- USB Type C connector for programming
    - This development board cannot be powered via USB and will require either a LiPo battery or a DC barrel jack connection.
- ON / OFF switch
- Mode & Reset switches
- RGB LED indicator
- 5-17V DC barrel jack connector for battery charging and normal operation
- Qwiic connector for I2C expansion
- Charging indicator LED
- Arduino Uno form factor for Arduino shield compatibility
  
![particle-somduino-1](https://github.com/user-attachments/assets/905cba05-fcd3-4299-8dee-ec5a840c115c)

## BOM
You can find a complete list of LCSC parts used in the example design below:

| Designator | Quantity | Comment | LCSC Part # |
| --- | --- | --- | --- |
| D1 | 1 | LED RGB | C5342281 |
| D2 | 1 | LED Charging | C2297 |
| H1 | 1 | Threaded standoff | C2916321 |
| J1, J4 | 2 | 1x08 Header | C27438 |
| J2 | 1 | 1x10 Header | C5116489 |
| J3 | 1 | 1x06 Header | C40877 |
| J5 | 1 | Barrel Jack Power In | C720557 |
| J6 | 1 | 1x02 Battery connector | C295747 |
| J7 | 1 | 1x04 Qwiic connector | C160390 |
| J8 | 1 | USB-C connector | C5362630 |
| R1, R2, R3, R5 | 4 | 1k 0603 resistor | C21190 |
| R10, R9 | 2 | 5.1k 0603 resistor | C23186 |
| R4, R8 | 2 | 10k 0603 resistor | C15401 |
| R6, R7 | 2 | 4.7k 0603 resistor | C23162 |
| SW1, SW2 | 2 | Push button switch | C318884 |
| SW3 | 1 | Power switch | C963205 |
| U1 | 1 | M.2 connector for SoM | C2977809 |
