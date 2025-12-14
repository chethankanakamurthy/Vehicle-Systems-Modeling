# Project 01 – EV Road Load Modeling & Coast-Down Validation

## Objective
Develop and validate a road load model for the Mahindra BE6 electric vehicle
in the absence of published EPA/ARAI coast-down data and benchmark it against
Tesla Model Y and Kia EV6.

## Methodology
- Physics-based rolling resistance and aerodynamic modeling
- Longitudinal coast-down simulation (zero drive torque)
- Road load identification using F = F0 + F1·v + F2·v²
- Cross-vehicle comparison using EPA road load coefficients

## Key Results
- Coast-down validated road load within <1% error
- Identified coefficients:
  - F0 = 295.84 N
  - F1 = 0.1155 N/(m/s)
  - F2 = 0.4567 N/(m/s²)
- BE6 exhibits higher road load than Tesla Model Y and Kia EV6 due to mass and CdA

## Tools
MATLAB, Simulink
