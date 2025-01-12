# MRIContrastAnalysis

## Overview
MRIContrastAnalysis is a Python project designed to analyze T1 and T2 relaxation times of MRI contrast agents, such as Dotarem, using non-linear curve fitting techniques. This project calculates relaxivity values (\(r_1\) and \(r_2\)) from experimental data obtained through inversion recovery and spin echo techniques. The results aim to provide insights into the efficacy of contrast agents and their behavior under varying concentrations.

## Submission Details
- **University**: Eberhard Karls University of Tübingen
- **Course**: Contrast in MRI
- **Specialization Module**: Bioimaging
- **Supervisor**: Dr. Gisela Hagberg
- **Course Date**: 12.11.2024
- **Submission Date**: 12.01.2025
- **Students**: Ahmed Eldably, Myriam Philippos, Jan Schöttke

## Key Features
- **Relaxivity Analysis**: Calculates T1 and T2 relaxivity values using linear regression and non-linear fitting.
- **Visualization**: Generates plots for MR intensity curves, linear relaxivity fits, and concentration dependence.
- **Customizable Code**: Modular functions for curve fitting, data visualization, and parameter extraction.

## Methods Used
- **Levenberg-Marquardt Algorithm**: Non-linear curve fitting for relaxation models.
- **Linear Regression**: Relaxivity calculation based on the relationship between \(1/T\) and concentration.
- **Matplotlib**: Visualization of experimental data and fits.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/aeldably/MRIContrastAnalysis.git
   ```
2. Install required libraries:
   ```bash
   pip3 install -r requirements.txt
   ```
3. Run the analysis script with your experimental data.

## Example Workflow
- Input experimental data (e.g., T1 and T2 measurements).
- Fit the data to the respective models.
- Generate plots for MR intensity and relaxivity relationships.
- Interpret relaxivity results to evaluate contrast agent performance.

## Results
This project has been used to analyze the T1 and T2 relaxation times of Dotarem at varying concentrations. The calculated relaxivities align with theoretical expectations and reported values in the literature, demonstrating the efficacy of the analysis methods.

## Future Work
- Extend analysis to in vivo conditions.
- Incorporate additional contrast agents for comparative studies.
- Automate data preprocessing and parameter estimation.