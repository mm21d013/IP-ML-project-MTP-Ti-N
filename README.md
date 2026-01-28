This project combine DFT and Machine Learning Interatomic Potential to develop and analyze interatomic potentials developed for Ti-N system

# IP-ML Project: Ti-N Interatomic Potential Development

This repository contains raw data, Jupyter notebooks, and scripts related to the development and analysis of machine learning interatomic potentials (MLIPs) for Ti-N system. Training data 

## 📁 About the Repository

The content here is provided **as raw reference material** for researchers, students, and developers.  
It is **not a ready-to-run package** — instead, the notebooks, scripts, and data are intended to be:

- Downloaded locally
- Studied and understood
- Modified or extended according to specific research needs

## 📂 Repository Structure
- 'Statistical Analysis'-- contains molecular dynamics plot using lammps and file energy.xlsx file. The file energy file contains strain information with which KDE plot and swarmplot has been plotted. Bash script for insertion/removal of Nitrogen in different Ti-N system for creation of hull plot is also present.
- 'Potentials' -- Contains the different potentials developed with MTP.
- 'Elastic Constant Calculations' -- Code for calculation of elastic constants using MTP-0.75-0.25-0.25 for different structures used in the paper.

## 📂 Active Learning Strategy
Relevant bulk calculations, as described in the literature, can be performed for additional crystal structures and incorporated into the existing CFG dataset to enhance its diversity and robustness. The trained model can then be employed to predict mechanical properties, with its reliability and transferability validated through appropriate statistical analyses such as parity plots, kernel density estimation (KDE), and related error metrics.

