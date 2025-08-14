# Traffic Simulation - Time Headway Curve Fitting (PTV VISSIM)

## Overview
This project simulates road traffic flow using **PTV VISSIM** to analyze the relationship between vehicle flow, speed, and density. Time headway data is used to perform **curve fitting** for traffic flow modeling, enabling the estimation of free flow speed, jam density, and roadway capacity. The results help in understanding how traffic parameters interact under varying conditions.

## Objectives
- Simulate real-world traffic scenarios in **PTV VISSIM**.
- Collect data for flow, speed, density, and time headway.
- Perform curve fitting to develop mathematical relationships.
- Estimate **free flow speed**, **jam density**, and **capacity**.
- Visualize speed–flow and speed–density relationships.

## Methodology
1. **Traffic Simulation** – Road network modeled in VISSIM with predefined vehicle compositions.
2. **Data Collection** – Output of speed, density, and flow at various traffic volumes.
3. **Curve Fitting** – Apply regression techniques to develop equations for:
   - Speed vs. Density
   - Speed vs. Flow
4. **Parameter Estimation** – Derive:
   - Free Flow Speed
   - Jam Density
   - Roadway Capacity

## Key Findings
- Minimum flow → Maximum speed & minimum density.
- Speed decreases as density increases, following a near-linear trend.
- Estimated jam density: **581.83 veh/km**
- Estimated free flow speed: **48.75 km/hr**
- Capacity ≈ **7091 veh/hr**

## Files in Repository
- `22CEB0A58 VISSIM.inpx` – VISSIM simulation file.
- `22CEB0A58 VISSIM.pdf` – Simulation output and analysis.
- `README.md` – Project documentation.

## Software Requirements
- **PTV VISSIM** (any version supporting .inpx format)
- **Microsoft Excel** (for curve fitting and plotting)

## Usage
1. Open `.inpx` file in PTV VISSIM.
2. Run the simulation for defined traffic scenarios.
3. Export data to Excel or Python for analysis.
4. Apply curve fitting and interpret results.

## License
This project is for **academic and research purposes** only.
