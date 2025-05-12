# Transient Heat Conduction in a Rocket Nozzle Wall

This project numerically simulates transient heat conduction through a rocket nozzle wall during engine firing using the Finite Element Method (FEM) in space and the trapezoid method in time. The analysis includes convergence studies and real-world validation using published NASA data.

## Methods Used

- 1D FEM for spatial discretization using linear hat functions  
- Trapezoid method (implicit, second-order) for time integration  
- Error convergence analysis in both space and time  
- Real-world comparison with NASA technical reports and experimental data  

## Repository Structure

- `AE370_Project_2.ipynb` — Main notebook with full simulation, analysis, and results
- `AE370_Project_2.pdf` - Full technical report containing all simulation data, analysis, and results
- `figures` — Folder containing saved figures:   
- `README.md` — This file  

## Questions Explored

1. How quickly does the inner wall heat up under combustion conditions?  
2. What is the temperature at the coolant side after 5 seconds?  
3. How does thermal diffusivity affect peak temperature inside the wall?  

## Key Outputs

Each simulation result is visualized and saved as downloadable PNG figures:
- Inner wall temperature vs. time  
- Coolant-side temperature evolution  
- Midpoint temperature vs. thermal diffusivity  
- Coolant-side heat flux vs. time (with experimental data overlay)  
- Average wall temperature growth  

## References

- Sutton, G. P., and Sherman, A., *Engineering Thermodynamics of Propulsion Systems*, McGraw-Hill, 1965.  
- Bartlett, M. H., and Peterson, J. T., “Convective Heat Transfer to the Wall of a Rocket Nozzle Expansion Section,” NASA TN D-5945, 1970. [PDF](https://ntrs.nasa.gov/api/citations/19710011726/downloads/19710011726.pdf)  
- Levine, S. R., Cunnington, G. R., and Reardon, J. D., “Thermal Response of Advanced Rocket Nozzle Materials,” NASA TM-106422, 1994. [PDF](https://ntrs.nasa.gov/api/citations/19950002497/downloads/19950002497.pdf)  
- Cunnington, G. R., “Measured and Predicted Transient Temperature Distributions in Rocket Nozzles,” NASA TM-110145, 1996. [PDF](https://ntrs.nasa.gov/api/citations/19970019627/downloads/19970019627.pdf)  

## Authors

Bradley Wassef  
Hamza Rimawi  
Riyad Babayev  
Gregor McKenzie  

University of Illinois Urbana-Champaign  
AE 370 — Numerical Methods in Aerospace Engineering

## License

This project is for academic use. NASA data is public domain per [NASA Public Access Plan](https://www.nasa.gov/wp-content/uploads/2021/12/nasa-ocs-public-access-plan-may-2023.pdf).
