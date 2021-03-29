# DC-MBAR data
The testing system include the intramolecular proton transfer reaction of the glycine and the Diels-Alder reactions between cyclopentadiene and acrylonitrile in explicit solvent. The simulation details could be found in our previous studies[1]. The reaction coordinates sampled by Umbrella Sampling are stored in the data folder.

# MBAR calculations
In this study, the pymbar package is used to solve the MBAR equations[2] (https://github.com/choderalab/pymbar). Two things to be noted: the task should be limited to one CPU core for CPU time comparison and the adaptive strategy is used to solve the MBAR equations. 

# UWHAM and SWHAM calculations 
The UWHAM and SWHAM software packages are also used for comparison[3] (https://ronlevygroup.cst.temple.edu/software/UWHAM_and_SWHAM_webpage/index.html). In this work, SWHAM refers to ST-SWHAM with 12 local jump attempts per cycle. For the one-dimensional and two-dimensional cases, 30 million equilibration cycles and 300 million equilibration cycles are used, respectively. 

# Reference
[1]: P. Li, X. Jia, X. Pan, Y. Shao, Y. Mei, J. Chem. Theory Comput. 2018, 14, 5583. https://doi.org/10.1021/acs.jctc.8b00571
[2]: M. R. Shirts, J. D. Chodera, J. Chem. Phys. 2008, 129, 124105. https://doi.org/10.1063/1.2978177
[3]: M. R. Shirts, J. D. Chodera, J. Chem. Phys. 2008, 129, 124105. https://doi.org/10.1038/s41598-019-39420-x
