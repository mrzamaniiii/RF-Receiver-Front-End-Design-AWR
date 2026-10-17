4.25 GHz RF Receiver Front-End Design and Simulation
Cadence AWR Microwave Office | Balanced LNA | RF Mixer | Receiver Performance
Overview
This academic project focuses on the design and circuit-level simulation of a 4.25 GHz RF down-conversion receiver using Cadence AWR Microwave Office (MWO). The receiver includes a balanced low-noise amplifier (LNA), RF filtering, a balanced mixer, a local oscillator, and IF filtering.
The goal is to study receiver performance in terms of gain, noise figure, linearity, and modulation quality, including the effects of phase noise and image-frequency interference.
System Specifications
Parameter	Value
RF frequency	4.25 GHz
LO frequency	3.75 GHz
IF frequency	500 MHz
Modulation	16-QAM
Signal bandwidth	32 MHz


The receiver down-converts the RF signal to a 500 MHz intermediate frequency.
Design and Simulation
- Balanced LNA: Simulated a FET-based amplifier with impedance matching and branch-line hybrid couplers. Evaluated gain, noise figure, P1dB, and IP3.
- Balanced mixer: Simulated frequency conversion using a balanced mixer and rat-race hybrid, including IF filtering.
- Receiver analysis: Investigated Error Vector Magnitude (EVM), local oscillator phase noise, and image-frequency interference for a 16-QAM signal.
Selected Simulation Results
Metric	Reported value
LNA gain	12.78 dB
LNA noise figure	2.99 dB
LNA P1dB	18.83 dBm
LNA IP3	27.39 dBm
Mixer conversion gain	-5.34 dB
Mixer P1dB	12.78 dBm


These values come from the project report and represent simulation results, not hardware measurements.
Project Report
The full report contains the circuit schematics, simulation plots, and detailed performance analysis.

Tools and Notes
- Software: Cadence AWR Microwave Office (MWO)
- This repository documents a simulation-based academic project. The original AWR project files (.emp) are not included, so the simulations cannot be rerun directly from this repository.
