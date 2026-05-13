# HDO Unit Optimization: Cost vs Yield Analysis

## Overview
3D optimization analysis of Hydrodeoxygenation (HDO) unit using Python and Aspen HYS simulation data. 
Goal: Minimize **Cost per Unit ($/Yield)** while maximizing **HDO Yield (%)**.

## Key Results
- **Optimal Operating Point**: 80 Bar, 300°C
- **Maximum Yield**: 83.89%
- **Minimum Cost per Unit**: $X.XX /%Yield  <- ganti X dengan nilai dari `opt_cost_unit` lu

## Visualizations
![HDO 3D Optimization](HDO_Cost_Yield_Optimization.png)
*Surface plot showing Cost per Unit vs Pressure & Temperature. Color indicates HDO Yield (%).*

## Tools & Skills Demonstrated
- **Python**: NumPy, Pandas, Matplotlib 3D
- **Process Engineering**: Mass & Energy Balance, Cost Analysis  
- **Optimization**: Grid search for optimal operating conditions

## Data Source
Aspen HYS simulation data for UCO Hydrodeoxygenation process.
