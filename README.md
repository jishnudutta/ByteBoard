# ByteBoard

ByteBoard is my custom 3×3 mechanical macropad powered by the Seeed Studio XIAO RP2040. It has 9 programmable mechanical keys, a rotary encoder, a 0.91" OLED display, per-key RGB lighting, and a custom PCB and 3D-printed case that I designed from scratch.

I started this project as part of Hack Club Stardance because I wanted to learn PCB design, CAD, and keyboard firmware by building something I would actually use. Instead of modifying an existing design, I challenged myself to design everything—from the schematic and PCB to the enclosure and firmware.

The result is a compact macropad that's useful for coding, video editing, media controls, and everyday shortcuts while also being a fun project to customize. Since everything is open source, you can easily change the firmware, modify the hardware, or even design your own version.

### Assembled Case

<img src="devlog-assets/assembledcase.png" alt="ByteBoard assembled case" width="800">

*The completed ByteBoard with its 3D-printed case.*

### Top Case

<img src="devlog-assets/topplate-v2.png" alt="ByteBoard assembled case" width="800">

*The top part of the case.*

### Bottom Case

<img src="devlog-assets/bottomplate-v2.png" alt="ByteBoard assembled case" width="800">

*The bottom part of the case.*

<<<<<<< Updated upstream
=======

>>>>>>> Stashed changes
### Matrix Schematic

<img src="devlog-assets/day2-sch.png" alt="ByteBoard matrix schematic" width="600">

*The schematic for the 3×3 key matrix.*

### Routed PCB

<img src="devlog-assets/routed-pcb.png" alt="ByteBoard routed PCB" width="600">

*The completed PCB layout after routing.*

### PCB 3D Model

<img src="devlog-assets/3d-pcb.png" alt="ByteBoard 3D PCB model" width="600">

*The finished PCB visualized in 3D.*

# ByteBoard — Bill of Materials (BOM)

## Components

| ID | Designator        | Footprint                                        | Quantity | Designation                                    | Supplier / Reference                                                                               | Notes                                                                            |
| -: | ----------------- | ------------------------------------------------ | -------: | ---------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
|  1 | D1–D9             | `D_DO-35_SOD27_P7.62mm_Horizontal`               |        9 | 1N4148                                         | —                                                                                                  | Included in Hackpad Kit                                                          |
|  2 | D10–D18           | `LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount` |        9 | SK6812MINI-E                                   | —                                                                                                  | Included in Hackpad Kit                                                          |
|  3 | SW1–SW9           | `SW_Cherry_MX_1.00u_PCB_Custom`                  |        9 | MX Switch                                      | —                                                                                                  | Included in Hackpad Kit                                                          |
|  4 | SW10              | `RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm` |        1 | EC11 Rotary Encoder                            | —                                                                                                  | Included in Hackpad Kit                                                          |
|  5 | U1                | `XIAO-Generic-Hybrid-14P-2.54-21X17.8MM`         |        1 | Seeed Studio XIAO RP2040                       | —                                                                                                  | Included in Hackpad Kit                                                          |
|  6 | U2                | `ER_OLEDM0.91_1x-I2C`                            |        1 | 0.91-inch I2C OLED                             | —                                                                                                  | Included in Hackpad Kit                                                          |
|  7 | Soldering Station | N/A                                              |        1 | YIHUA 926LED-III 60W Digital Soldering Station | [Robu.in Product Page](https://robu.in/product/yihua-926led-iii-60w-digital-soldering-iron-tools/) | Required for assembly; not included in Hackpad Kit. Grant requested if possible. |

## Summary

| Category                            | Quantity |
| ----------------------------------- | -------: |
| Diodes (1N4148)                     |        9 |
| Addressable RGB LEDs (SK6812MINI-E) |        9 |
| Mechanical switches                 |        9 |
| Rotary encoders                     |        1 |
| Microcontrollers (XIAO RP2040)      |        1 |
| OLED displays                       |        1 |
| Soldering stations                  |        1 |

**Note:** The Hackpad Kit includes all components except the soldering station. The soldering station is required for assembly.


➡️ [Read the full journal](./JOURNAL.md)
