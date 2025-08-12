# Supersonic Expansion Fan Analysis (Prandtl–Meyer Flow)

## Overview
This project implements numerical and analytical calculations for supersonic expansion fans using the Prandtl–Meyer function. It computes flow properties across an expansion wave and visualizes variations in Mach number, pressure, temperature, and density.

## Features
- Computes Prandtl–Meyer angle for given Mach numbers.
- Calculates downstream Mach number for a given deflection angle.
- Determines pressure, temperature, and density ratios across the expansion.
- Plots variation of flow properties with deflection angle.
- Supports customizable specific heat ratio (γ).

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- Jupyter Notebook (optional, for interactive use)

Install dependencies:
pip install numpy matplotlib

## Usage
1. Clone or download this repository.
2. Open `NSW-EXPANSION FAN.ipynb` in Jupyter Notebook.
3. Run the notebook cells in order.
4. Provide upstream Mach number, deflection angle, and γ.
5. View calculated properties and generated plots.

## Theory Background
Based on Prandtl–Meyer expansion theory for supersonic flows:
ν(M) = sqrt((γ+1)/(γ-1)) * atan( sqrt((γ-1)/(γ+1) * (M^2 - 1)) ) - atan( sqrt(M^2 - 1) )
Expansion fans turn the flow isentropically and accelerate it to higher Mach numbers while reducing pressure and temperature.

## Applications
- Supersonic nozzle design.
- Wind tunnel testing and analysis.
- Educational demonstrations of compressible flow theory.

## License
This project is open-source and available under the MIT License.
