# bone xl distortion pedal
![BoneXL](front.png)
I recently got into electronics, and as a musician, I thought a guitar pedal would be a fun project. I followed this awesome tutorial by Brian Wampler of Wampler 
Pedals https://www.wamplerpedals.com/blog/lifestyle-hobby/2024/08/how-to-design-a-basic-distortion-pedal-circuit/. The circuit is slightly different (I use a 
different op-amp), but all credit for the circuit design should go to Brian. This is my first project learning and using KiCad for PCB design.
![back.png](back.png)

## bill of materials

| Reference               | Value      | Datasheet                                     | Footprint                                                                                        | Qty | DNP |
|-------------------------|------------|-----------------------------------------------|--------------------------------------------------------------------------------------------------|-----|-----|
| BT1                     | 9V         | ~                                             | standard_symbols:THT_Wire_Holes_x2                                                               | 1   |     |
| C1,C2                   | 47µF       | ~                                             | Capacitor_THT:CP_Radial_D4.0mm_P1.50mm                                                           | 2   |     |
| C3,C10,C11              | 22nF       | ~                                             | Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm                                                       | 3   |     |
| C4,C8                   | 100pF      | ~                                             | Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm                                                       | 2   |     |
| C5                      | 47nF       | ~                                             | Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm                                                       | 1   |     |
| C6                      | 50pF       | ~                                             | Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm                                                       | 1   |     |
| C7                      | 680nF      | ~                                             | Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm                                                       | 1   |     |
| C9,C12                  | 1µF        | ~                                             | Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm                                                       | 2   |     |
| D1,D2                   | LED        | ~                                             | LED_THT:LED_D3.0mm                                                                               | 2   |     |
| J1,J2                   | AudioJack2 | ~                                             | standard_symbols:THT_Offboard_Audio                                                              | 2   |     |
| R1,R2,R3,R7,R11,R12,RV2 | 10kΩ       | ~                                             | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal,standard_symbols:THT_Wire_Holes_x3 | 7   |     |
| R4,R8                   | 1MΩ        | ~                                             | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal                                    | 2   |     |
| R5                      | 4.7kΩ      | ~                                             | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal                                    | 1   |     |
| R6                      | 2.2kΩ      | ~                                             | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal                                    | 1   |     |
| R9                      | 680kΩ      | ~                                             | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal                                    | 1   |     |
| R10                     | 1kΩ        | ~                                             | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal                                    | 1   |     |
| R13                     | 220Ω       | ~                                             | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal                                    | 1   |     |
| RV1,RV3                 | 100kΩ      | ~                                             | standard_symbols:THT_Wire_Holes_x3                                                               | 2   |     |
| U1                      | LM358      | http://www.ti.com/lit/ds/symlink/lm2904-n.pdf | Package_DIP:DIP-8_W7.62mm                                                                        | 1   |     |
| U2                      | J201       | J201                                          | footprints:TO-92-3_4P58X4P58_ONS                                                                 | 1   |     |


