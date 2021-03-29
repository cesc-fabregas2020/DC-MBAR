# DC-MBAR data
The testing system include the intramolecular proton transfer reaction of the glycine and the Diels-Alder reactions between cyclopentadiene and acrylonitrile in explicit solvent. The simulation details could be found in our previous studies[1]. The reaction coordinates sampled by Umbrella Sampling are stored in the data folder.

# MBAR calculations
In this study, the pymbar package is used to solve the MBAR equations[2](https://github.com/choderalab/pymbar). Two things to be noted: the task should be limited to one CPU core for CPU time comparison and the adaptive strategy is used to solve the MBAR equations. 

# UWHAM and SWHAM calculations 
The UWHAM and SWHAM software packages are also used for comparison. 
