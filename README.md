# PstKB
Genome scale metabolic modeling of Solanum tuberosum.

This repository holds the Genome Scale Metabolic Reconstruction of Solanum tuberosum, as first obtained
by means of KBase automatic model generation and following manually refinement and testing.

# ABOUT RECONSTRUCTION
This reconstruction was started using the complete Solanum tuberosum genome sequencing.


# ABOUT FILES
## PstKB.mat
Basic Matlab session for the analysis of this reconstruction

## PstKB.ori.xls and PstKB.ori.xml
Original XLS and SBML (xml) files as obtained from KBase.

## modelData.xls
Holds the media used for the initial reconstruction: "Plant Heterotrophic Media" as provided by KBase, [in this narrative](https://narrative.kbase.us/#dataview/KBaseMedia/PlantHeterotrophicMedia).
This file holds the media components as downloaded from KBase. 
Please note that the media components could differ when inspected online and when downloaded from KBase website.

Also holds detailed information on the components of Biomass objective function, in this models as well a comparative with other models.

## fluxvector.ori
Holds the metabolic phenotype of original reconstruction. Used mainly to inspect for infinite fluxes (-1000/1000) that could
be indicative of Type III loops.


