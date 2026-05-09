# LTspice Circuit Simulations

This repository contains various digital logic gate simulations designed and tested using **LTspice**. The goal is to demonstrate the fundamental behavior of CMOS and TTL logic circuits through transient analysis.

## Repository Structure

The project is organized into folders based on the logic gate type:

* **AND/**: Contains schematic files (`.asc`) and symbol files (`.asy`) for AND gate implementations.
* **Inv/**: Inverter (NOT gate) simulations, including voltage transfer characteristic (VTC) analysis.
* **NAND/**: NAND gate designs, often used as the universal building block for other logic.

## Getting Started

1.  **Prerequisites**: Ensure you have [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) installed on your machine.
2.  **Cloning**: Clone this repository using:
    ```bash
    git clone [https://github.com/satyam22463/Lt_Spice.git](https://github.com/satyam22463/Lt_Spice.git)
    ```
3.  **Running Simulations**:
    * Open any `.asc` file in LTspice.
    * Click the **Run** (man running icon) to start the simulation.
    * Use the probe tool to view input/output waveforms.

## Simulation Details

Each gate includes:
* **Transient Analysis**: To observe timing and logic levels.
* **DC Sweep**: (Where applicable) To analyze switching thresholds.

---
*Created by [satyam22463](https://github.com/satyam22463)*
