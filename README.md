# Simulation and PSD Analysis of TLS-Induced Noise in Superconducting Resonators

This project uses Monte Carlo simulations to model frequency noise in superconducting resonators arising from two-level systems (TLS) and white noise, and analyzes the resulting signals using power spectral density (PSD).

Superconducting resonators are widely used in quantum technologies and sensing applications. 
While these devices are designed to have very low loss, their performance is often limited by frequency noise. 
At low temperatures, two-level systems (TLS) are a dominant source of this noise.

This project focuses on simulating TLS-induced noise and understanding its signatures in the power spectral density.

## What this project does

- Simulates stochastic switching of individual TLS using a Monte Carlo approach  
- Models frequency fluctuations as a sum of many TLS contributions  
- Includes white (thermal/readout) noise  
- Generates synthetic time-domain signals  
- Computes power spectral density (PSD) to analyze noise behavior

## Key results

- A single TLS produces random telegraph noise  
- Identical TLS → single-timescale fluctuations  
- Distributed switching rates → multi-timescale behavior  
- Emergence of 1/f noise from many TLS  
- White noise sets the high-frequency noise floor

## Repository structure

- `TLS_noise_simulation.ipynb` — main simulation and analysis code  
- `Noise_Simulation_SC_Resonators.pdf` — slides explaining background, model, and results

## How to run

1. Clone the repository  
2. Open the Jupyter notebook  
3. Run all cells to reproduce simulations and plots  

Dependencies:
- numpy  
- matplotlib  
- scipy

## Future work

- Include distributed coupling strengths  
- Extend to generalized tunneling model (GTM)  
- Add Allan deviation analysis   
