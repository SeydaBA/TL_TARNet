This repository provides codes for the paper titled with "Advantages and limitation in the use of transfer learning for individual treatment effects in causal machine learning" from Aydin & Brandt.

**Repository Structure**

The repository is organized as follows:

**Data**

*Simulation*: Functions for simulation datasets are under Data_generation/Simulation.R

*Empirical example*: The way of subsetting [IHDS-II dataset](https://ihds.umd.edu/data/ihds-2) is under Data_generation/IHDS.R 



**Functions**

*TARNet*: The architecture of the model is under TARNet.py

*Optimize_IPM*: Aligning distributions function is under Optimize_IPM.py

*Optimize_Loss*: After aligning distributions, optimizing loss functions is under Optimize_Loss.py



**Distance**

Functions to find the distance between distributions of the datasets are under Distances/Distance.py.

