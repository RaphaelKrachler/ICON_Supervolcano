# ICON slab-ocean volcanic aerosol experiment, Data Modeling Lab, Summer Semester 2026

Git repository for the project on the atmospheric and climate response to an idealized strong volcanic aerosol forcing using the ICON climate model in a slab-ocean setup.
This repository contains scripts and notebooks used to modify volcanic aerosol input files, run the ICON experiment, and analyse the model output. 

Authors: Raphael Krachler, Kevin Llanaj, Simon Benke, Bagas Briliano,
Institute of Meteorology and Geophysics/ University of Vienna

## Repository contents

The repository contains the following files:

- `9exp_slabctr_10pinatubo_rampup_decay.run`: Example for the runscripts used for the ICON slab-ocean experiment, here with a 10× Pinatubo aerosol forcing, including ramp-up and decay.
- `input_file_modification.ipynb`: Notebook used to modify the volcanic aerosol input files. The notebook scales the relevant aerosol optical properties and constructs the forcing files used in the experiment.
- `input_file_analysis.ipynb`: Notebook used to inspect and visualize the volcanic aerosol input fields, namely figure 1 of the report.
- `data_analysis_notebook.ipynb`: Notebook used for visualizing figures 2 and 4 of the report.
- `data_analysis_report_figure_3_and_specific_values...`: Notebook used for visualizing figure 3, as well as calculating further numerical results used in the report.

## Data

Large ICON model output files and original forcing files are not included in this repository due to their file size. 
The scripts assume that the required input and output files are available locally and that the paths are adapted to the user’s own directory structure.
