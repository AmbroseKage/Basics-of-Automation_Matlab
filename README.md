# Basics-of-Automation - Matlab – Laboratory Reports

---

## Overview

This repository contains selected exercises from the **Fundamentals of Control Engineering** course. The focus of the labs was on the analysis and modeling of dynamic systems in both time and frequency domains, as well as the identification of process models based on real system data.

The experiments were conducted using MATLAB and Simulink.

---

## Covered Topics

### ✅ Time-Domain Analysis

- Step response and impulse response of first- and second-order systems
- System dynamics: time constant, settling time, overshoot, and steady-state error
- Comparison between theoretical and simulated responses

### ✅ Frequency-Domain Analysis

- Bode plots and Nyquist diagrams
- Gain and phase margin analysis
- Frequency response of systems with different dynamic orders
- Filtering and resonance effects

### ✅ System Identification

- Experimental identification of control plant parameters
- Models used:
  - First-order with delay (Kupfmüller model)
  - Second-order with delay
  - Strejc model (multiple-order without delay)
- Parameter estimation using optimization (e.g., `fminsearch`)
- Evaluation metrics:
  - MSE (Mean Squared Error)
  - FIT (goodness of fit)

---

## Tools and Environment

- **MATLAB R2023b**
- **Simulink** – simulation and block modeling
- Scripts: `.m` files and Live Scripts (`.mlx`)
- Tested on Windows 11

---

## Repository Structure

- `time_response_analysis/` – scripts and plots for time-domain simulations  
- `frequency_response_analysis/` – Bode/Nyquist plot generation and analysis  
- `system_identification/` – parameter estimation and model validation  
- `figures/` – exported plots and figures used in reports  
- `README.md` – this file

---

## Learning Outcomes

The labs provided hands-on experience with the analysis and modeling of control systems. Key skills developed:

- Interpreting dynamic behavior of systems
- Simulating system response to standard inputs
- Estimating model parameters from experimental data
- Using graphical methods to assess system stability and performance

---

> The repository includes working code, simulation files, plots, and supporting documentation for educational and reference purposes.
