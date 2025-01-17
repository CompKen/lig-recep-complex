# Molecular Simulation of Ligand-Protein Complex

## Background
This project is an example of learning to use openMM in Jupyter NB to run a Molecular Dynamics simulations of a solvated protein ligand complex. Much of this follows the tools introduced in the OpenFF tutorial (https://github.com/openforcefield/openff-toolkit/tree/stable/examples/toolkit_showcase) although modifications have been made and the specific receptor and ligand have been subbed out for learning purposes. 

The ligand-protein complex is from data provided by Merck (https://github.com/MCompChem/fep-benchmark). The example I am working through here uses the ligand SHP099 (an allosteric inhibitor) and the receptor tyrosine phosphate SHP2 (5ehr). The suppression of SHP2 is a potential target of cancer therapy. 

## Project Outline
- Preparation and visualization of the SHP099 ligand (from SHP099_1.sdf)
  ![Ligand image from NGLview](ligand.png)
- Preparation and visualization of the receptor (5ehr_prepared.pdb)
  ![Receptor image from NGLview](receptor.png)
- Insertion of ligand into complex and solvating to generate an initial configuration
  ![Solvated Complex image from NGLview](solvated_complex.png)
- Using openMM to perform energy minimization, equilibration, and production runs
- Analyses using MDAnalysis packages
  ![bfactor image from NGLview](complex_eqb_bfactor.png)

## Project to-do list
- Calculation of potential scoring functions for protein-ligand complex interactions
