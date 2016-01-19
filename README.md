# 20MW-wind-turbine-model
This repository contanis the 20 MW common research wind turbine model data. Please cite this work as:

Turaj Ashuri, Joaquim R.R.A. Martins, Michiel B. Zaaijer, Gijs A.M. van Kuik, Gerard J.W. van Bussel. "Aeroservoelastic Design Definition of a
20 MW Common Research Wind Turbine Model". Wind energy (In press). 2016.

To run the model follow these steps:

1- Download (or clone) FAST and TurbSim folders to you computer.

2- Open a terminal and set the working directory to TurbSim folder. Then type in:

$ TurbSim.exe Wind_7u.inp

Press enter. This will generate a turbulent wind flow field at 7 m/s. Copy the corresponding output files (the *.wnd and *.sum) to FAST folder.

3- Direct the working directory to FAST folder. Then type in:

$ FAST_V601_EC.exe FAST_7u.fst

Press enter. This will generate an output file (*.out) that has aeroelastic time series of the 20 MW common wind turbine research model at 7 m/s wind speed.

To modify the files for different input conditions, please consult TurbSim, AeroDyn and FAST user manuals downloadable at NREL website.



