## Fear Conditioning Task: Visualisation and Analysis

Author: Gergana Moskova  
Date: 14.12.2024  
Source: https://neurosynth.org/analyses/terms/fear/ 

### Description:
This project focuses on visualising and analysing fMRI data to explore brain activation patterns. It involves locating and loading the data files, creating activation maps that overlay functional data onto anatomical scans, and creating a histogram of positive activation values. The data was collected during a fear conditioning task.

### Table of Contents:
Two data files were used:
- Anatomical MRI data file:
    - Containins a high-resolution scan of the human brain. 
    - File name: anatomical.nii.gz
- Functional MRI data file:
    - Containins activation data from the fear conditioning task.
    - File name: fear_uniformity-test_z_FDR_0.01.nii.gz 

Notebook: Assignment.ipynb

### Pyhton Packages:
- Glob
- NiBabel
- Nilearn
- Matplotlib
- NumPy