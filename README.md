# msld-prep
  - __Vilseck, J. Z.; Cervantes, L. F.; Hayes, R. L.; Brooks, C. L., III. Optimizing Multisite lambda-Dynamics Throughput with Charge Renormalization. *J Chem Inf Model* 2022, 62 (6), 1479-1488. DOI: 10.1021/acs.jcim.2c00047__

### A collection of python scripts and procedures to enable the building of ligands for Multi-site lambda Dynamics simulations using CHARMM/pyCHARMM

*msld-py-prep* scripts for creating a multiple topology model for Multisite λ-Dynamics (MSλD) in CHARMM and pyCHARMM. 

These scripts identify common atoms (similar partial atomic charge and identical atom types) across different compounds of interest with a maximum common substructure search. A charge renormalization algorithm is then implemented to generate a set of partial atomic charges suitable for multisite sampling of many chemical functional groups with MSλD. 

The output is a directory of CHARMM compatible files to use for MSλD simulations, including an example CHARMM input script. 
