# M87
<h3>A dual-resonant solid state Tesla coil, hitting 170kW peaks</h3>
<img width="859" height="1033" alt="Screenshot 2026-09-07 at 5 58 11 PM" src="https://github.com/user-attachments/assets/6aa76440-cb64-40c3-8c84-8dd448bbca0f" />
<img width="2160" height="1091" alt="Assembly_2026-Sep-08_12-16-06AM-000_CustomizedView9614355404" src="https://github.com/user-attachments/assets/0cbec0ed-1a0b-4bd1-9eae-d8d42652f97b" />

<h1>High Voltage Safety</h1>

** I do not advise anyone to replicate this and do not take any responsibility if you choose to do so. **

** This is an advanced high voltage project, DO NOT REPLICATE! **

** I am not responsible for any damage caused from irresponsibly playing with high voltage. ** 

# PCBs
<h4>There are four custom PCBs in this build. </h4>
<h2>Universal Driver "M87"</h2>
<img width="516" height="486" alt="Screenshot 2026-09-06 at 10 52 54 PM" src="https://github.com/user-attachments/assets/2bbe581c-9fb4-4f2e-946c-80427f9f50e3" />
<h2>Optical Interrupter</h2>
<img width="368" height="594" alt="Screenshot 2026-09-06 at 11 14 16 PM" src="https://github.com/user-attachments/assets/81c6449b-7013-48b2-b239-009fe07e5df4" />
<H2>Multi-Mini Capacitor</H2>
<img width="1006" height="457" alt="Screenshot 2026-09-07 at 6 00 40 PM" src="https://github.com/user-attachments/assets/4fd822bc-17aa-4f86-b2a9-087271e01273" />
<h2>Current Transformers</h2>
<img width="588" height="1013" alt="Screenshot 2026-09-06 at 10 58 16 PM" src="https://github.com/user-attachments/assets/06957a56-98c0-4886-a6f2-5b513a8865ab" />

# Schematics
<h4>The schematics to each PCB</h4>
<h2>Universal Driver "M87"</h2>
<img width="1127" height="1120" alt="Screenshot 2026-09-07 at 6 30 48 PM" src="https://github.com/user-attachments/assets/0a56ae57-2d1f-46be-9221-284cecedd98c" />

<h2>Optical Interrupter</h2>
<img width="948" height="978" alt="Screenshot 2026-09-07 at 6 35 54 PM" src="https://github.com/user-attachments/assets/75db0752-af8d-4b60-8576-452423d634c2" />

<h2>Multi-Mini Capacitor & Current Transformers</h2>
<img width="1548" height="271" alt="Screenshot 2026-09-07 at 6 37 50 PM" src="https://github.com/user-attachments/assets/1671a579-0f45-461a-a016-99af3e9b20d2" />
<img width="684" height="587" alt="Screenshot 2026-09-07 at 6 39 29 PM" src="https://github.com/user-attachments/assets/ab4d3afc-62e0-4b9a-9c98-f28a9772e89d" />

# The Bridge
<h3>This is the main switching part of the coil, if you put aside all the logic, isolation, coils, etc.</h4>
<img width="1183" height="739" alt="Screenshot 2026-09-07 at 6 04 10 PM" src="https://github.com/user-attachments/assets/ba30cf70-7a0c-468b-b890-548c7d53952e" />
<h4>Mainly, it uses two SKM300GB IGBT half-bridges and four 5000uF 450V capacitors. 
These half-bridges are put together to create a full bridge, while the capacitors are both in series and parallel in a voltage doubler configuration.
This results in a total capacitance of 5000uF and a voltage rating of 900V, with a bus voltage of 340V.</h4>

# Specifications

## Power Supply 
* 0 – 120 VAC through a variac
* 30A Full Bridge Rectifier
* 4x 5000uF 450V capacitors in voltage doubling configuration, and in parallel.
  
## Primary Coil
* 320 mm diameter
* 3/8" diameter copper tubing
* 11 total windings, subject to tuning using a scope.

## MMC (Multi-Mini Capacitor)
* 9 strings in parallel of 2 in series 0.1uF 2kV film capacitors.
* Total Rating: 0.45 µF @ 4000 VDC

## Secondary Circuit
* 6.5" diameter x 2' length
* 2200 turns of 30AWG
* 127 x 620 mm aluminum ducting topload

## Parameters

* **Resonant Frequency:** ~65 – 80 kHz
* **Input Power:** 1800W at 120 VAC @ 15 A (500 A OCD)

# Bill of Materials
<h2>For a more detailed look, check out https://docs.google.com/spreadsheets/d/1DjRxDST9gP6VWVaGONw40nzyh7GYetqo9sDGphOBDtU/edit?usp=sharing</h2>

| **Item**                                                         | **Price** | **Link**                                                                                                   |
| ---------------------------------------------------------------- | --------: | ---------------------------------------------------------------------------------------------------------- |
| **LOGIC & DRIVING**                                              |           |                                                                                                            |
| 20VAC Signal Transformer                                         |        $1 | [eBay](https://www.ebay.com/itm/156355734533)                                                              |
| 14 Pin IC Sockets x3                                             |        $6 | [AliExpress](https://www.aliexpress.us/item/3256805529241851.html)                                         |
| 8 Pin IC Sockets x3                                              |        $6 | [AliExpress](https://www.aliexpress.us/item/3256805529241851.html)                                         |
| SN74HC14 x2                                                      |        $4 | [AliExpress](https://www.aliexpress.us/item/3256806000467098.html)                                         |
| LM311 x2                                                         |        $4 | [AliExpress](https://www.aliexpress.us/item/2251832814445271.html)                                         |
| SN74HC74 x2                                                      |        $6 | [AliExpress](https://www.aliexpress.us/item/3256807843061608.html)                                         |
| SN74HC08 x2                                                      |        $4 | [AliExpress](https://www.aliexpress.us/item/3256806000467098.html)                                         |
| UCC27423 x10 (Gate Driver IC)                                    |       $25 | [DigiKey](https://www.digikey.com/en/products/detail/texas-instruments/UCC27423P/603260)                   |
| TO 263 Heatsinks (w/ Pad)                                        |        $8 | [AliExpress](https://www.aliexpress.us/item/3256810406260405.html)                                         |
| Thermal Pad                                                      |        $2 | [AliExpress](https://www.aliexpress.us/item/3256802090742663.html)                                         |
| UD 1.3 Driver                                                    |       $35 | [eBay](https://www.ebay.com/itm/126296053530)                                                              |
| UD M87 Custom Designed Driver PCB                                |       $80 | JLCPCB                                                                                                     |
| 200kHz Oscilloscope (SELF-FUNDED)                                |       N/A | [Amazon](https://www.amazon.com/FNIRSI-DSO152-Handheld-Oscilloscope-Bandwidth/dp/B0FDPYNQBC/)              |
| **CURRENT TRANSFORMERS**                                         |           |                                                                                                            |
| Dual Current Transformer Custom PCB                              |        $4 | JLCPCB                                                                                                     |
| Ferrite 77 Cores x4                                              |        $9 | [DigiKey](https://www.digikey.com/en/products/detail/fair-rite-products-corp/5977001401/8599655)           |
| 24AWG Solid Core                                                 |        $8 | [Amazon](https://www.amazon.com/DKARDU-Electrical-Stranded-Color%EF%BC%88Black-Assortment/dp/B09PH2ZDLC/r) |
| KF9500 Screw Terminals 2P                                        |        $4 | [AliExpress](https://www.aliexpress.us/item/3256806674476213.html)                                         |
| **GATE DRIVE TRANSFORMER**                                       |           |                                                                                                            |
| Ferrite 77 (a few)                                               |        $2 | [DigiKey](https://www.digikey.com/en/products/detail/fair-rite-products-corp/5977001401/8599655)           |
| CAT5 Cable                                                       |       $10 | [Amazon](https://www.amazon.com/Ethernet-Snagless-Computer-Network-Internet/dp/B0BJNZ71K3/)                |
| **INTERRUPTER**                                                  |           |                                                                                                            |
| Custom Optical Interrupter PCB                                   |       $70 | JLCPCB                                                                                                     |
| 5m Fiber Optic Cable HFBR-RNS005Z                                |       $13 | [DigiKey](https://www.digikey.com/en/products/detail/broadcom-limited/HFBR-RNS005Z/1990489)                |
| 9V Batteries                                                     |        $5 | [Amazon](https://www.amazon.com/XUNIUZERO-9V-Batteries-Detector-Long-Lasting/dp/B0F5HLZMH4)                |
| 9V Battery Connector                                             |        $3 | [AliExpress](https://www.aliexpress.us/item/3256810332396131.html)                                         |
| 50K Potentiometers                                               |        $2 | [AliExpress](https://www.aliexpress.us/item/3256806841285775.html)                                         |
| 10K Potentiometers                                               |        $2 | [AliExpress](https://www.aliexpress.us/item/3256806841285775.html)                                         |
| 5K Potentiometers                                                |        $2 | [AliExpress](https://www.aliexpress.us/item/3256806841285775.html)                                         |
| ON-OFF-ON Toggle Switches x5                                     |        $3 | [AliExpress](https://www.aliexpress.us/item/3256807979121643.html)                                         |
| **FULL BRIDGE**                                                  |           |                                                                                                            |
| 4.7 Ohm 5W Resistors (Cement)                                    |        $3 | [AliExpress](https://www.aliexpress.us/item/3256807607955844.html)                                         |
| 4.7 Ohm 5W Resistors (Wirewound) x2                              |        $4 | [AliExpress](https://www.aliexpress.us/item/3256806563516146.html)                                         |
| 1.5KE220CA x3                                                    |        $7 | [AliExpress](https://www.aliexpress.us/item/3256809640787649.html)                                         |
| 1N5364B 33V Zener Diodes x3                                      |        $6 | [AliExpress](https://www.aliexpress.us/item/3256806214186575.html)                                         |
| 400V 10uF Snubber Film Capacitors x2                             |        $8 | [AliExpress](https://www.aliexpress.us/item/3256808070998741.html)                                         |
| KBPC3510 FBRs x2                                                 |        $4 | [AliExpress](https://www.aliexpress.us/item/3256806258995719.html)                                         |
| 5000uF 450V Capacitors x4                                        |       $55 | [eBay](https://www.ebay.com/itm/327028788973)                                                              |
| 25K 100W Wirewound Bleeder Resistors x2                          |        $4 | [AliExpress](https://www.aliexpress.us/item/3256805970781782.html)                                         |
| SKM300GB Brick Half Bridge IGBTs x2                              |       $60 | [eBay](https://www.ebay.com/itm/267516067582)                                                              |
| Copper Busbars x2                                                |       $37 | [Amazon](https://www.amazon.com/Copper-Thickness-Suitable-Battery-Connection/dp/B0BZCRHCHR)                |
| Shorting Clips                                                   |        $6 | [Amazon](https://www.amazon.com/Insulated-Alligator-Durable-Battery-Electric/dp/B0773JXZT9/)               |
| Kapton Tape                                                      |       $10 | [Amazon](https://www.amazon.com/ELEGOO-Polyimide-Temperature-Resistant-Multi-Sized/dp/B072Z92QZ2/)         |
| Large Aluminum Heatsink x2                                       |       $26 | [Amazon](https://www.amazon.com/dp/B07TJY3GKP)                                                             |
| **MMC (Multi-Mini-Capacitor)**                                   |           |                                                                                                            |
| Custom Bleeder PCB                                               |        $9 | JLCPCB                                                                                                     |
| 0.1uF 2kV Capacitors x4 (2 per string, 9 in parallel) 0.45uF 4kV |       $16 | [AliExpress](https://www.aliexpress.us/item/3256802900888178.html)                                         |
| MMC Bleeder Resistor: 1M, 2W x2                                  |        $4 | [AliExpress](https://www.aliexpress.us/item/3256802900888178.html)                                         |
| **Primary Coil**                                                 |           |                                                                                                            |
| 3/8 Inch 25 Feet Copper Tubing                                   |       $50 | [Amazon](https://www.amazon.com/BELLA-BAYS-Refrigeration-Seamless-Refrigerators/dp/B0BCQYFXLF)             |
| **Secondary Coil**                                               |           |                                                                                                            |
| 6" x 2' PVC Pipe                                                 |       $24 | [Amazon](https://www.amazon.com/FT-PVC-DWV-SCH-PIPE/dp/B0FFCNLJLH/)                                        |
| 3lbs 30AWG Magnet Wire                                           |       $55 | [Amazon](https://www.amazon.com/MECCANIXITY-Enameled-Magnetic-Transformer-Fahrenheit/dp/B0FK92B2VT/r)      |
| **Topload**                                                      |           |                                                                                                            |
| 8" x 25' Aluminum Flex Tube                                      |       $35 | [Amazon](https://www.amazon.com/VIVOSUN-Non-Insulated-Aluminum-Ventilation-Stainless/dp/B010UCCR3A/)       |
| **Strike Ring**                                                  |           |                                                                                                            |
| 9AWG Aluminum Wire                                               |       $10 | [Amazon](https://www.amazon.com/Tenn-Well-Aluminum-Bendable-Sculpting/dp/B095Y8N92C)                       |
| **Frame / Misc.**                                                |           |                                                                                                            |
| 500mm Extrusions x4                                              |       N/A | Already Owned                                                                                              |
| 300mm Extrusions x8                                              |       N/A | Already Owned                                                                                              |
| 2020 Corner Brackets x24                                         |       N/A | Already Owned                                                                                              |
| 500mmx300mmx3mm ABS Sheet                                        |       $34 | [Amazon](https://www.amazon.com/Plastic-Styrene-Sheets-Building-Crafts/dp/B0GS4NB2Y3)                      |
| Tin Snips                                                        |       N/A | Already Owned                                                                                              |
| **SHIPPING & TAX (KMS)**                                         |           |                                                                                                            |
| JLCPCB Shipping                                                  |      $105 | Sob                                                                                                        |
| Tax                                                              |      $100 |                                                                                                            |
| **Total**                                                        |  **$992** |                                                                                                            |

