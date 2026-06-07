# AMESim Relief Valve Simulation

This repository contains the simulation methodology and analytical report from my bachelor's thesis. The project focuses on optimizing the dynamic response of a hydraulic relief valve using AMESim.

## Files Included
- `Relief_Valve_Dynamic_Analysis.pdf`: Full technical report (Methodology, calculations, and conclusions).
- `model.png`: Screenshot of the hydraulic circuit modeled in AMESim.
- `graph.png`: Transient response curves from the simulation.

## Overview
Traditional relief valves have slow response times and pressure overshoot. I used the control variable method to test how four parameters affect system stability:
1. Spool Mass
2. Damping Orifice Diameter
3. Spring Stiffness
4. Oil Bulk Modulus

## Key Result
By increasing the oil bulk modulus to 1900MPa and tuning the damping orifice diameter, the system's response time was reduced by 0.02 seconds, significantly reducing steady-state hydrodynamic forces.

*Note: The original .ame simulation files are archived. The attached PDF contains the complete data plots and analysis.*
