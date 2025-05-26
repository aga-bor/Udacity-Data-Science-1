Predicting Gini Index with Machine Learning

This repository contains a machine learning project aimed at predicting the Gini Index, a widely used measure of income inequality, using socioeconomic and demographic indicators from countries around the world.

Motivation
Income inequality is a pressing global issue. The Gini Index offers a numeric representation of how wealth is distributed within a population. Understanding which factors drive inequality can help inform public policies and development strategies. This project investigates whether it's possible to predict a country's Gini Index based on other publicly available indicators.

What is the Gini Index?

The Gini Index ranges from 0 to 100:
0 means perfect equality (everyone has the same income)
100 means perfect inequality (one person has all the income)
The index is calculated by the World Bank and other statistical bodies to assess economic disparity within countries.

Repository Contents

Gini Index classification.ipynb – Final classification notebook with cleaned output and visualizations.
data/ – Folder for raw and processed datasets (not included in this repository).
README.md – This file.

Analysis Summary
Goal: Predict categorical bins of Gini Index using a classification model.
Model Used: Random Forest Classifier
Test Accuracy: 97.2%
Train Accuracy: 93.2%
No signs of overfitting were observed.

Top Predictive Feature

Category	Key Features
Poverty Measures	Poverty thresholds ($2.15, $3.65, $6.85), national poverty line
Health	HIV prevalence, surgical access, suicide rate
Basic Access	Drinking water, sanitation, financial inclusion
Demographics	Age structure, migrant stock, population density
Economy	GDP, tax structure, income-related health issues

Key Insight

Income inequality is strongly associated with poverty depth, health accessibility, and infrastructure services.

Libraries Used
The project was implemented using Python in a Jupyter Notebook environment.
pandas – for data loading, manipulation, and exploration
numpy – for numerical operations
matplotlib – for visualizations
seaborn – for enhanced statistical plots
scikit-learn – for building and evaluating the classification model (Random Forest)

Acknowledgments
World Bank Open Data
World Health Organization Indicators
Jupyter Notebook for analysis and visualization

