# WattsUp's Component Library #
Primarily personal use only

## SKU Legend ##
| SKU | Category | Numbering |
|-----|----------|-----------|
| 00-0000 | No Real Part | None |
| 01-xxxx | Batteries | Increment unique |
| 02-xxxx | Solar Cell | Increment unique |
| 03-xxxx | All boards | Increment unique |
| 04-xxxx | Connectors SMD | Increment unique, suffix P for plug |
| 05-xxxx | Connectors THT | Increment unique, suffix P for plug |
| 06-xxxx | Fuses SMD | Increment unique |
| 07-xxxx | Fuses THT | Increment unique |
| 08-xxxx | Amplifiers (excluding RF) | Increment unique |
| 09-xxxx | Communication ICs | Increment unique |
| 10-xxxx | Ceramic 1005 (0402 in) | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 11-xxxx | Ceramic 1608 (0603 in) | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 12-xxxx | Ceramic 2012 (0805 in) | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 13-xxxx | Ceramic 3216 (1206 in) | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 14-xxxx | Ceramic 3225 (1210 in) and larger | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 15-xxxx | Ceramic THT | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 16-xxxx | Tantalum SMD | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 17-xxxx | Tantalum THT | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 18-xxxx | Electrolytic SMD & THT | First three characters is the value in pF (i.e. 223 = 22*10³pF = 22nF). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 19-xxxx | All other capacitors | Increment unique |
| 20-xxxx | Resistor 1005 (0402 in) | 4 characters are a standard 4-stripe resistor numbering (i.e 2223 = 222 * 10³Ω = 222 kΩ). Values requiring a negative exponent will use a decimal notation instead (i.e. 0.10Ω). If multiple variants of the same value and package exist, an incremented suffix is added (i.e. 21-1001 and 21-1001A) |
| 21-xxxx | Resistor 1608 (0603 in) | 4 characters are a standard 4-stripe resistor numbering (i.e 2223 = 222 * 10³Ω = 222 kΩ). Values requiring a negative exponent will use a decimal notation instead (i.e. 0.10Ω). If multiple variants of the same value and package exist, an incremented suffix is added (i.e. 21-1001 and 21-1001A) |
| 22-xxxx | Resistor 2012 (0805 in) | 4 characters are a standard 4-stripe resistor numbering (i.e 2223 = 222 * 10³Ω = 222 kΩ). Values requiring a negative exponent will use a decimal notation instead (i.e. 0.10Ω). If multiple variants of the same value and package exist, an incremented suffix is added (i.e. 21-1001 and 21-1001A) |
| 23-xxxx | Resistor 3216 (1206 in) | 4 characters are a standard 4-stripe resistor numbering (i.e 2223 = 222 * 10³Ω = 222 kΩ). Values requiring a negative exponent will use a decimal notation instead (i.e. 0.10Ω). If multiple variants of the same value and package exist, an incremented suffix is added (i.e. 21-1001 and 21-1001A) |
| 24-xxxx | Resistor 3225 (1210 in) and larger | 4 characters are a standard 4-stripe resistor numbering (i.e 2223 = 222 * 10³Ω = 222 kΩ). Values requiring a negative exponent will use a decimal notation instead (i.e. 0.10Ω). If multiple variants of the same value and package exist, an incremented suffix is added (i.e. 21-1001 and 21-1001A) |
| 25-xxxx | Resistor THT | 4 characters are a standard 4-stripe resistor numbering (i.e 2223 = 222 * 10³Ω = 222 kΩ). Values requiring a negative exponent will use a decimal notation instead (i.e. 0.10Ω). If multiple variants of the same value and package exist, an incremented suffix is added (i.e. 21-1001 and 21-1001A) |
| 26-xxxx | All other resistors | Increment unique |
| 27-xxxx | Conversion Ics | Increment unique |
| 28-xxxx | Logic Ics | Increment unique |
| 29-xxxx | Memory | Increment unique |
| 30-xxxx | Inductor 1005 (0402 in) | First three characters is the value in nH (i.e. 223 = 22*10³nH = 22µH). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 31-xxxx | Inductor 1608 (0603 in) | First three characters is the value in nH (i.e. 223 = 22*10³nH = 22µH). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 32-xxxx | Inductor 2012 (0805 in) | First three characters is the value in nH (i.e. 223 = 22*10³nH = 22µH). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 33-xxxx | Inductor 3216 (1206 in) | First three characters is the value in nH (i.e. 223 = 22*10³nH = 22µH). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 34-xxxx | Inductor 3225 (1210 in) and larger | First three characters is the value in nH (i.e. 223 = 22*10³nH = 22µH). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 35-xxxx | Inductor THT | First three characters is the value in nH (i.e. 223 = 22*10³nH = 22µH). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 36-xxxx | Ferrites | Increment unique |
| 37-xxxx | Chokes | Increment unique |
| 38-xxxx | Transformers | Increment unique |
| 39-xxxx | All other coils | Increment unique |
| 40-xxxx | Crystal SMD | First three characters is the value in Hz (i.e. 223 = 22*10³Hz = 22kHz). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 41-xxxx | Crystal THT | First three characters is the value in Hz (i.e. 223 = 22*10³Hz = 22kHz). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 42-xxxx | Oscillator SMD | First three characters is the value in Hz (i.e. 223 = 22*10³Hz = 22kHz). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 43-xxxx | Oscillator THT | First three characters is the value in Hz (i.e. 223 = 22*10³Hz = 22kHz). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 44-xxxx | Resonator SMD | First three characters is the value in Hz (i.e. 223 = 22*10³Hz = 22kHz). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 45-xxxx | Resonator THT | First three characters is the value in Hz (i.e. 223 = 22*10³Hz = 22kHz). Last character is an incremented letter for each variant of the same value and package A-Z. Namely different temperature and or voltage ratings |
| 46-xxxx | Real-time clock | Increment unique |
| 47-xxxx | All other clocks | Increment unique |
| 48-xxxx | Fasteners | First number is diameter (0 = [0 mm, 1mm), 1 = [1 mm, 2 mm), ..., A = [10 mm, 11 mm)). Second is length (0 = [0 mm, 1mm), 1 = [1 mm, 2 mm), ..., A = [10 mm, 11 mm)). Third is type: B (button head), C (counter sink head), H (hex head) S (socket head), T (thumb head), N (plain hex nut), L (locknut), P (PCB nut), R (rivet). Fourth is increment unique. 48-23B0 is an M2 x 3mm button head.
| 49-xxxx | Electromechanical | Increment unique |
| 50-xxxx | Diode generic | Increment unique |
| 51-xxxx | Diode Schottky | Increment unique |
| 52-xxxx | Diode Zener | Increment unique |
| 53-xxxx | Diode other | Increment unique |
| 54-xxxx | Thyristor | Increment unique |
| 55-xxxx | Transistor BJT | Increment unique |
| 56-xxxx | Transistor FET | Increment unique |
| 57-xxxx | Transistor IGBT | Increment unique |
| 58-xxxx | Optoisolator | Increment unique |
| 59-xxxx | All other discrete semiconductors (excluding LEDs) | Increment unique |
| 60-xxxx | Power ICs | Increment unique |
| 61-xxxx | µControllers (and CLPD, FPGA, etc.) | Increment unique |
| 62-xxxx | All other ICs | Increment unique |
| 63-xxxx | LEDs | Increment unique |
| 65-xxxx | RF | Increment unique |
| 66-xxxx | Sensors | Increment unique |
| 67-xxxx | All other hardware | Increment unique |