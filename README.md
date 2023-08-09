# 2512-attenuator
RF-attenuator from 1W 2512 size resistors with both BNC and SMA connectors. Works OK from DC to 30MHz. 

![graph](2512-Attenuator_1M-50M.png)
![graph](2512-Attenuator_1M-300M.png)

Measured with NanoVNA-H4 using NanoVNA saver 

---

PCB size: 71.5 x  25 x 1.6 mm

PCB Stackup: Two layer FR-4 (No impedance control) 

Traces are not 50 ohm as this is mainly for < 50 MHz use and the size of the entire PCB is thus significantly smaller than the wavelength at this frequency. 

I tried to only use resistors from the E12 series as much as possible.

This calculator was used, with the modification that i used two parallel resistors for each position for increased thermal handling and to achieve a resistance closer to the calculated values. 

[Link to RF Attenuator calculator](https://leleivre.com/rf_pipad.html)

---

Made to fit the following heat sink. 

> Heat Sink, 4.4 °C/W, TO-218, TO-220, TO-247, 42 mm, 38.1 mm, 25 mm

> Farnell Order code 1710612

---

| Resistor | Value for 1dB Attenuator | Value for 2dB Attenuator | Value for 3dB Attenuator | Value for 6dB Attenuator | Value for 10dB Attenuator |
|----------|--------------------------|--------------------------|--------------------------|--------------------------|---------------------------|
| R1       | DNI                      | DNI                      | DNI                      | DNI                      | DNI                       |
| R2       | 2k2                      | 820                      | 560                      | 270                      | 180                       |
| R3       | DNI                      | DNI                      | DNI                      | DNI                      | DNI                       |
| R4       | 1k5                      | 1k                       | 560                      | 330                      | 220                       |
| R5       | 12                       | 22                       | 33                       | 68                       | 150                       |
| R6       | 10                       | 24                       | 39                       | 82                       | 150                       |
| R7       | 2k2                      | 1k                       | 560                      | 270                      | 180                       |
| R8       | 1k5                      | 820                      | 560                      | 330                      | 220                       |
| R9       | DNI                      | DNI                      | DNI                      | DNI                      | DNI                       |
| R10      | DNI                      | DNI                      | DNI                      | DNI                      | DNI                       |


DNI = Do Not Install
