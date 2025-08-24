# Measurement Model Validation of Second-Harmonic Nonlinear Electrochemical Impedance Spectroscopy

This repository contains the essential code and data for the paper "Measurement Model Validation of Second-Harmonic Nonlinear Electrochemical Impedance Spectroscopy"

This repository can be cited with: 


For further information or if this code is used, please go to or cite the following paper:

-------------
### Abstract
-------------

Harmonic distortion is a measurable feature of nearly all EIS experiments; linearity is generally assumed when total harmonic distortion is below a few percent threshold. A workflow is presented for optimally extracting and using 2nd-harmonic data while ensuring adequate linearity for sound EIS analysis. We prove mathematically that frequency dispersion functions for second-harmonic nonlinear EIS (2nd-NLEIS) satisfy Kramers–Kronig (KK) relations, providing a basis for constructing a measurement model (MM) test of stationarity and causality in both EIS and 2nd-NLEIS data. The performances of cost and confidence interval algorithms for automating MM fitting are evaluated. We illustrate this workflow by analyzing three different batteries to identify optimal current modulations and frequency ranges for analysis. For example, an optimal balance between 2nd-NLEIS signal quality and EIS linearity in a 1.5 Ah NMC||C Samsung cell occurs with a current modulation of ∆I = 0.5 amp. Experiments with commercial pouch and in-house coin cells show these MM tests can distinguish between intrinsic cell-to-cell 2nd-NLEIS variance versus measurements that fail to meet stationarity and causality criteria. Robust optimization and validation of simultaneous EIS and 2nd-NLEIS data opens the door for more reliable frequency-domain model identification, parameterization, and error analysis.



### Software Dependencies
----------------------------------------------------------------
This repository was developed using the following versions of the subsequent softwares:

* Python 3.11.10
* Conda 23.1.0
* Git Bash for MacOS

The conda environment used for this work can be recreated with the following commands:

```conda env create -f environment.yml```

```conda activate mm_test```

----------------------------------------------------------------
### Folders
----------------------------------------------------------------
**nleis**: This folder contains unreleased version of nleis.py that has MM test functionality built in. 

**jupyter**: This folder contains essential data and Supplementary Jupyter Notebook used to generate figures for this work

**MATLAB**: This folder contains the MATLAB code used to perform numerical KK integration.



