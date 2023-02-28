In this Project Developed regressors to predict compressional and shear travel-time logs, DTC and DTS using following regression techniques: Elastic Net; K Nearest Neighbor; Random Forest; Gradient Boosting; Support 
Vector Machines.

Background

Well logs are interpreted/processed to estimate the in-situ petrophysical and geomechanical properties, which is essential for subsurface characterization. Various types of logs exist, and each provides distinct information about subsurface properties. Certain well logs, like gamma ray (GR), resistivity, density, and neutron logs, are considered as “easy-to-acquire” conventional well logs that are run in most of the 
wells. Other well logs, like nuclear magnetic resonance, dielectric dispersion, elemental spectroscopy, and sometimes sonic logs, are only run in limited number of wells.
Sonic travel-time logs contain critical geomechanical information for subsurface characterization around the wellbore. Often, sonic logs are required to complete the well-seismic tie workflow or geomechanical properties prediction. When sonic logs are absent in a well or an interval, a common practice is to 
synthesize them based on its neighboring wells that have sonic logs. This is referred to as sonic log synthesis or pseudo sonic log generation.

Goal Of The Project

Compressional travel-time (DTC) and shear travel-time (DTS) logs are not acquired in all the wells drilled 
in a field due to financial or operational constraints. Under such circumstances, machine learning 
techniques can be used to predict DTC and DTS logs to improve subsurface characterization. The goal of 
the project is to develop data-driven models by processing “easy-to-acquire” conventional logs from 
well1, and use the data-driven models to generate synthetic compressional and shear travel-time logs 
(DTC and DTS, respectively) in Well2.

About The Dataset
The dataset has the following features whihc should be used by data-driven models Caliper (CAL), Neutron (CNC), 
Gamma Ray (GR), Deep Resistivity (HRD), Medium Resistivity (HRM), Photo-electric factor (PEF) and 
density (ZDEN).Utilmately the data-driven model should synthesize two targets: DTC and DTS logs.

Refrences
https://github.com/pddasig/Machine-Learning-Competition-2020
https://onepetro.org/petrophysics/article/62/04/393/466187/Synthetic-Sonic-Log-Generation-With-Machine


