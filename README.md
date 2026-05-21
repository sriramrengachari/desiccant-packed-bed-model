# desiccant-packed-bed-model
Python-based transient adsorption, heat transfer, and exergy analysis model for desiccant packed bed systems developed using Jupyter Notebook and Anaconda.

Overview
This project presents a one-dimensional transient desiccant packed bed model for analysing coupled heat and mass transfer during adsorption and dehumidification processes. The model incorporates:

Transient adsorption dynamics
Moisture transport and humidity evolution
Energy conservation within the packed bed
Mass Transfer Zone (MTZ) tracking
Experimental validation against MAPB systems
Exergy analysis of humidification/dehumidification rigs
Correlation analysis for MTZ velocity and width
The implementation is developed in Python using scientific computing libraries and executed through Jupyter Notebook.

Features
1. Data Validation
Experimental data consistency checks
Humidity and temperature validation
Moisture ratio verification
Detection of missing or inconsistent measurements
2. 1D Packed Bed Model
One-dimensional transient adsorption model
Method of Lines numerical solution
Dynamic adsorption term q(t)
Coupled heat and mass transfer equations
Packed bed thermal response simulation
3. Experimental Validation
Comparison between model predictions and experimental thermocouple data
Outlet temperature and humidity trajectory validation
Error metrics:
RMSE
NRMSE
R²
4. MTZ Analysis
Mass Transfer Zone velocity tracking
MTZ width estimation
Front propagation analysis
Comparison between standard MAPB and OHP-integrated MAPB systems
5. Correlation Development
Correlations for MTZ velocity and width
Reynolds number dependence
Humidity step influence
Geometry scaling analysis
6. Exergy Analysis
Moist-air property calculations
Exergy efficiency evaluation
Cumulative exergy calculations
Comparison across different packed bed configurations
Governing Concepts

The model is based on:
Conservation of mass
Conservation of energy
Adsorption kinetics
Moist-air thermodynamics
Exergy analysis

Key calculated quantities include:
Temperature profiles
Humidity ratio
Moisture uptake
MTZ velocity and width
Reynolds number
Exergy efficiency
Dehumidification performance
Requirements

Install dependencies using:

pip install -r requirements.txt

Recommended Python version:
Python 3.10+
Main Libraries
numpy
pandas
matplotlib
scipy
scikit-learn
CoolProp
openpyxl
jupyter

Model Capabilities
The notebook performs:
Experimental data preprocessing
Numerical packed bed simulation
Temperature profile prediction
Humidity ratio calculations
MTZ analysis
Validation against experimental data
Exergy analysis
Correlation development
Plot generation and comparison

Sample Outputs
The model can generate:
Temperature evolution plots
Humidity ratio trajectories
MTZ progression graphs
Experimental vs model comparison plots
Exergy efficiency curves
Correlation plots for MTZ velocity and width

Applications

This project can be applied to:
Desiccant dehumidification systems
HVAC analysis
Thermal energy systems
Packed bed adsorption systems
Exergy optimisation studies
Heat and mass transfer research
Sustainable cooling technologies
