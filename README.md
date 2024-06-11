# Nutritional Geometry Analysis

## Overview

This repository contains scripts for analyzing nutritional geometry using topological data analysis and high-order network structures. The approach is inspired by the paper titled "Application of Topological Data Analysis and High Order Network Structures in Nutritional Status of Children: Surpassing Body Mass Index With Topological Signatures" by André Luiz de Góes Pacheco.

## Prerequisites

To use the scripts in this repository, you need to have Python installed along with the following packages:

- `pandas`: Data analysis and manipulation library.
- `numpy`: Fundamental package for scientific computing with Python.
- `matplotlib`: Comprehensive library for creating static, animated, and interactive visualizations in Python.

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib


Scripts
1. BMI Calculation and Classification
File: bmi_classification.py

Description:
This script contains functions for calculating and classifying BMI, as well as analyzing body composition based on body fat percentage and gender.

Functions:

calculate_bmi(weight, height): Calculates BMI.
classify_bmi(bmi): Classifies BMI into categories.
analyze_person(weight, height, muscle_mass, fat_mass, body_fat, waist_circumference, gender): Analyzes and classifies a person based on various metrics.
2. Polar Plot Visualization
File: polar_plots.py

Description:
This script provides functions for creating polar plots to compare body metrics between individuals.

Functions:

plot_polar_triplets_comparison(vars1, vars2, custom_plot_names): Creates polar plots for comparing two sets of body metrics.
3. Comprehensive Analysis and Visualization
File: comprehensive_analysis.py

Description:
This script integrates analysis and visualization functions for a comprehensive evaluation of body metrics.

Functions:

analyze_and_plot(person1, gender1): Analyzes and plots body metrics for comparison between two individuals.

Citation
If you use this code, please cite the following article once it is published:

Pacheco, A. L. G. (2024). Application of Topological Data Analysis and High Order Network Structures in Nutritional Status of Children: Surpassing Body Mass Index With Topological Signatures.

Contact
For any questions or issues, please contact André Luiz de Góes Pacheco at algp@cin.ufpe.br .
