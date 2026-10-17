
# 4.25 GHz RF Receiver Front-End Design and Simulation

**Cadence AWR Microwave Office | Balanced LNA | RF Mixer | Receiver Performance**

## Overview

This academic project focuses on the design and circuit-level simulation of a 4.25 GHz RF down-conversion receiver using Cadence AWR Microwave Office (MWO).

The receiver includes a balanced low-noise amplifier (LNA), RF filtering, a balanced mixer, a local oscillator, and IF filtering.

The goal is to evaluate receiver performance in terms of gain, noise figure, linearity, and modulation quality.

## System Specifications

| Parameter | Value |
|---|---|
| RF Frequency | 4.25 GHz |
| LO Frequency | 3.75 GHz |
| IF Frequency | 500 MHz |
| Modulation | 16-QAM |
| Signal Bandwidth | 32 MHz |

## Design and Simulation

- **Balanced LNA:** Simulated a FET-based amplifier with impedance matching and branch-line hybrid couplers. Evaluated gain, noise figure, P1dB, and IP3.
- **Balanced Mixer:** Simulated frequency conversion using a balanced mixer and rat-race hybrid, including IF filtering.
- **Receiver Analysis:** Investigated Error Vector Magnitude (EVM), local oscillator phase noise, and image-frequency interference for a 16-QAM signal.

## Selected Simulation Results

| Parameter | Result |
|---|---|
| LNA Gain | 12.78 dB |
| LNA Noise Figure | 2.99 dB |
| LNA P1dB | 18.83 dBm |
| LNA IP3 | 27.39 dBm |
| Mixer Conversion Gain | -5.34 dB |
| Mixer P1dB | 12.78 dBm |

These values are simulation results, not hardware measurements.

## Tools and Notes

- **Software:** Cadence AWR Microwave Office (MWO)
- The original AWR project files (`.emp`) are not included in this repository.
