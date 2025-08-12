# Flat Plate Boundary Layer Analysis

## Overview
This project implements a computational and analytical approach for studying boundary layer development over a flat plate. It estimates key aerodynamic parameters such as local Reynolds number, boundary layer thickness, skin friction coefficient, and drag force under laminar and turbulent flow conditions.

## Features
- Calculates local and average Reynolds numbers.
- Determines boundary layer thickness (laminar/turbulent).
- Estimates skin friction coefficient and drag force.
- Supports various fluid property inputs.
- Visualizes flow parameter distributions along the plate.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- Jupyter Notebook (optional, for interactive use)

Install dependencies:
pip install numpy matplotlib

## Usage
1. Clone or download this repository.
2. Open `FLAT PLATE.ipynb` in Jupyter Notebook.
3. Run the notebook cells in order.
4. Input plate length, velocity, and fluid properties.
5. View calculated parameters and generated plots.

## Theory Background
Based on classical boundary layer theory for incompressible flow over a flat plate:
- Laminar: δ(x) ≈ 5x / √Re_x
- Turbulent: δ(x) ≈ 0.37x / Re_x^(1/5)
- Skin friction and drag are estimated using standard empirical correlations.

## Applications
- Aerodynamic drag estimation.
- Educational demonstrations of boundary layer concepts.
- CFD validation and benchmark cases.

## License
This project is open-source and available under the MIT License.
