# LTspice Digital Logic Library

This repository contains a collection of digital logic circuit simulations designed and verified using LTspice. The project covers a range of components from basic gates to sequential logic and combinational circuits.

## Project Contents

### 1. Basic Logic Gates
* **AND**: Standard AND gate implementations including schematic (.asc) and symbol (.asy) files.
* **Inverter (Inv)**: CMOS inverter circuits used to study switching characteristics and VTC.
* **NAND**: Universal NAND gate designs.

### 2. Sequential Logic
* **D-Flip-Flop**: DFF implementations including gate-level designs (DFF_W_GATES.asc) and standard configurations.

### 3. Combinational Circuits
* **3x8 Decoder**: A 3-to-8 line decoder simulation (decoder3x8.asc) complete with a custom symbol for modular use.
* **CMOS Designs**: Various CMOS-level logic implementations (CMOS.asc, CMOS2.asc, CMOS3.asc).

### 4. Technical Drafts
* Includes several iteration drafts (Draft1 through Draft5) used for testing transient analysis and troubleshooting waveform timing.

## Getting Started

### Prerequisites
* You must have LTspice installed. It is available for free from Analog Devices.

### Usage
1. Clone the repository:
   git clone https://github.com/satyam22463/Lt_Spice.git
2. Open LTspice.
3. Load any .asc file from the root directory or specific folders.
4. Press the Run button to execute the transient analysis (.tran).

## File Extensions
* .asc: Circuit schematic file.
* .asy: Component symbol file.
* .plt: Plot settings for viewing specific waveforms.
* .raw / .log: Simulation output and data logs (generated after running).

---
Maintainer: satyam22463
