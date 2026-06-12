# High-Frequency Buck-Boost Converter Design and Simulation

**[Click here to view the Report](https://github.com/user-attachments/files/28900365/Buck.Boost.Converter.Design.pdf)**

## Project Overview
This repository contains the design, mathematical modeling, and software simulation of a high-frequency switch-mode power supply. The specific topology is a Buck-Boost DC-DC converter engineered to accept a variable input voltage and regulate it to a highly stable output under fluctuating load conditions. 

The core of this project involves establishing the precise critical inductance boundaries required to maintain both Continuous Conduction Mode and Discontinuous Conduction Mode.

## Design Specifications

| Parameter | Value |
| :--- | :--- |
| **Input Voltage Range** | 200 V – 250 V |
| **Target Output Voltage** | 100 V |
| **Load Current Range** | 4 A – 8 A |
| **Switching Frequency** | 100 kHz |
| **Output Capacitance** | 1000 µF |

## Circuit Topology
<img width="1550" height="578" alt="Schematic" src="https://github.com/user-attachments/assets/a31aba67-455c-4653-a330-16b970dfcf72" />


## Key Engineering Methodologies
* **Mathematical Modeling:** Calculated maximum and minimum duty cycles based on extreme input variations.
* **Boundary Condition Analysis:** Derived the critical inductance thresholds for extreme load and voltage scenarios to ensure mode stability.
* **Software Validation:** Utilized PSIM to empirically validate theoretical calculations through rigorous stress testing. Waveform analysis confirms the converter remains strictly within intended conduction states during maximum load and minimum input constraints.

---
*Designed and simulated by Ahmadrza Ahmadli - Yıldız Teknik Üniversitesi*
