# msld-prep
  - __Vilseck, J. Z.; Cervantes, L. F.; Hayes, R. L.; Brooks, C. L., III. Optimizing Multisite lambda-Dynamics Throughput with Charge Renormalization. *J Chem Inf Model* 2022, 62 (6), 1479-1488. DOI: 10.1021/acs.jcim.2c00047__

### A collection of python scripts and procedures to enable the building of ligands for Multisite λ-Dynamics (MSλD) simulations using CHARMM/pyCHARMM

### `msld-prep` was developed within the Brooks Research Group at the University of Michigan and is currently overseen by [Jonah Vilseck at Indiana Univerity School of Medicine]((https://github.com/Vilseck-Lab)).
### To download the `msld-prep` GitHub repository (housed on Jonah's site) execute the command: `git clone git@github.com:Vilseck-Lab/msld-py-prep.git`.
### `msld-prep` is an integral component of running MSλD in [CHARMM/pyCHARMM](https://charmm.chemistry.harvard.edu/main.php), software availble free of charge for academic and government laboratories.

### `msld-py-prep` scripts assist in creating a multiple topology model for Multisite λ-Dynamics (MSλD) in CHARMM and pyCHARMM. 

### These scripts identify common atoms (similar partial atomic charge and identical atom types) across different compounds of interest with a maximum common substructure search. A charge renormalization algorithm is then implemented to generate a set of partial atomic charges suitable for multisite sampling of many chemical functional groups with MSλD. 

### The output is a directory of CHARMM (and pyCHARMM) compatible files to use for MSλD simulations, including an example CHARMM input script. 
