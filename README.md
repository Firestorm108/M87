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

<h2>Multi-Mini Capacitorr</h2>
<img width="1548" height="271" alt="Screenshot 2026-09-07 at 6 37 50 PM" src="https://github.com/user-attachments/assets/1671a579-0f45-461a-a016-99af3e9b20d2" />

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
