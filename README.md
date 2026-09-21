# BJT Multistage Amplifier

Design and simulation of a multistage BJT amplifier using LTspice
for the Electronics I course.

## Project Description

The objective of this project is to design a multistage BJT amplifier
that satisfies the given electrical specifications.

The amplifier is designed to operate from a 5 V supply and drive
a 100 Ω load.

## Specifications

| Parameter | Requirement |
|-----------|-------------|
| Supply Voltage (VCC) | 5 V |
| Load Resistance (RL) | 100 Ω |
| VBE | 0.7 ± 0.1 V |
| Output Voltage Swing | ≥ 1 V |
| Voltage Gain | |Av| ≥ 20 |
| Input Resistance | Ri ≥ 1 kΩ |
| Maximum Frequency | 5 kHz |
| THD | ≤ 5% |

## Circuit

The amplifier consists of multiple BJT stages designed to achieve
the required voltage gain while maintaining the required output swing,
input resistance, and linearity.

![Circuit Schematic](Schematics/amplifier.png)

## Simulation

The circuit was designed and simulated using LTspice.

The following analyses were performed:

- DC operating point analysis
- AC frequency response
- Transient analysis
- Output voltage swing
- Input resistance
- Voltage gain
- Total Harmonic Distortion (THD)

Results

The complete simulation results, measurements, and analysis are provided in the project report.

## How to Run

1. Install LTspice.
2. Open the project file located in `LTspice/`.
3. Run the required simulations.
4. Compare the simulation results with the project specifications.

## Files

- `LTspice/` — LTspice circuit files
- `Schematics/` — Circuit schematic image
- `Report/` — Project report

## Course

**Electronics I**

University: Sharif University of Technology

Semester: Fall 2025 (1404)