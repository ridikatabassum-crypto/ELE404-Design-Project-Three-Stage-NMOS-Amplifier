# Three-Stage NMOS Amplifier Design

**Course:** ELE404 – Electronic Circuits  
**University:** Toronto Metropolitan University  
**Project Type:** Analog Circuit Design  
**Semester:** W2026

## Overview

This project involved the design and SPICE simulation of a three-stage cascaded NMOS amplifier. The objective was to develop an amplifier that provides high voltage gain while maintaining low power consumption and sufficient bandwidth.

The design consists of two common-source amplification stages followed by a common-drain (source follower) output buffer.

## Design Architecture

The amplifier consists of three stages:

- **Stage 1 – Common Source:** Provides initial voltage amplification.
- **Stage 2 – Common Source:** Provides additional voltage gain through cascaded amplification.
- **Stage 3 – Common Drain:** Acts as an output buffer to improve load-driving capability.

## Project Specifications

| Parameter | Design Requirement |
|---|---:|
| Voltage Gain | ≥ 60 dB |
| Power Consumption | ≤ 1 mW |
| Bandwidth | ≥ 500 kHz |
| Output Swing | ≥ 1.5 Vpp |
| Input Resistance | ≥ 100 kΩ |
| Gain Reduction with Load | ≤ 10% |
| Maximum Branch Current | ≤ 200 µA |

## Tools & Technologies

- KiCad / SPICE Simulation
- Analog Circuit Design
- NMOS Transistors
- Circuit Analysis
- DC Operating Point Analysis
- AC Frequency Response Analysis
- Transient Analysis

## Simulation Results

The initial simulation produced the following results:

| Parameter | Simulated Result |
|---|---:|
| Voltage Gain | 12.1 dB |
| Bandwidth | 7.95 MHz |
| Power Consumption | 0.996 mW |
| Output Swing | 7.8 mVpp |
| Input Resistance | 150 kΩ |
| Gain Reduction | 3.8% |
| Maximum Branch Current | 139.74 µA |

The initial design met the bandwidth, power consumption, input resistance, gain reduction and maximum branch current requirements. However, it did not achieve the required voltage gain or output swing.

## Engineering Challenges & Design Limitations

One of the main challenges was achieving sufficient voltage gain while maintaining the power consumption limit.

The output buffer also exhibited low transconductance due to its low operating current, limiting its ability to drive the output load effectively.

These results highlighted the importance of MOSFET biasing, stage-to-stage coupling and gain optimization in multistage amplifier design.

## Future Improvements

Potential improvements include:

- Optimizing MOSFET bias currents and operating points.
- Recalculating transistor transconductance and stage gains.
- Improving the output buffer design.
- Re-evaluating resistor and capacitor values.
- Optimizing overall voltage gain while maintaining the power budget.

## Key Learning Outcomes

- Designed a cascaded three-stage NMOS amplifier.
- Applied common-source and common-drain amplifier configurations.
- Performed MOSFET biasing and operating-point calculations.
- Analyzed voltage gain and frequency response.
- Evaluated transient response and output signal distortion.
- Compared simulation results against engineering design specifications.

**Project Status:** Initial design and simulation completed. Further optimization is required to meet all design specifications.
