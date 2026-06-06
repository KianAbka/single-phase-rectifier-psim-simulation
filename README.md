# Single-Phase Rectifier PSIM Simulation

This repository contains the PSIM simulation of single-phase rectifier circuits for an Industrial Electronics laboratory assignment.

## Project Overview

The purpose of this project is to simulate and analyze single-phase half-wave and full-wave bridge rectifier circuits. The effect of a capacitor filter on the output voltage waveform, average output voltage, and ripple is also investigated.

## Simulated Circuits

* Single-phase half-wave rectifier with resistive load
* Single-phase full-wave bridge rectifier with resistive load
* Half-wave rectifier with capacitor filter
* Full-wave bridge rectifier with capacitor filter

## Simulation Parameters

* Input voltage: 220 V RMS
* Frequency: 50 Hz
* Load resistance: 100 ohm
* Filter capacitor: 1000 µF
* Compared capacitor values: 470 µF, 1000 µF, and 4700 µF
* Simulation software: PSIM

## Objectives

* Plot the output voltage waveform for each circuit
* Measure the average output voltage
* Measure and compare the output voltage ripple
* Study the effect of different capacitor values on the output waveform
* Compare half-wave and full-wave rectifier performance

## Results Summary

The simulation results show that the full-wave bridge rectifier provides a smoother output voltage compared to the half-wave rectifier. The full-wave rectifier also has a higher average output voltage and lower ripple. Adding a capacitor filter reduces the output voltage ripple and makes the waveform closer to a DC voltage. Increasing the capacitor value further decreases the ripple.

## Repository Structure

```text
report/        Final project report
psim-files/    PSIM schematic files
waveforms/     Output voltage waveform images
```

## Software Used

* PSIM

## Author

Prepared as part of an Industrial Electronics laboratory assignment.
