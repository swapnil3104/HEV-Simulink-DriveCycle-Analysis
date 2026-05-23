# HEV-Simulink-DriveCycle-Analysis
 Electric Vehicle simulation using MATLAB Simulink with UDDS and HWFET drive cycles.


## Overview

This project presents a Hybrid Electric Vehicle (HEV) simulation model developed in MATLAB/Simulink.

The vehicle is tested using standard EPA drive cycles:
- UDDS (Urban Dynamometer Driving Schedule)
- HWFET (Highway Fuel Economy Test)

---

## Project Structure

### Model Files
- `model/iHev_Nexon1(2).slx`

### Drive Cycle Data
- `drive_cycles/UDDS(1).mat`
- `drive_cycles/HWFET(1).mat`

### Documentation
- `docs/drive data.pdf`

---

## Features

- HEV Powertrain Simulation
- Battery-Motor Interaction
- Urban Driving Analysis
- Highway Driving Analysis
- Drive Cycle Based Testing

---

## Software Requirements

- MATLAB R2024a
- Simulink

---

## How to Run

1. Open MATLAB
2. Load the drive cycle MAT files
3. Open Simulink model:
   ```matlab
   open('iHev_Nexon1(2).slx')
