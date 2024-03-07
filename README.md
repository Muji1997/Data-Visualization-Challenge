# Cancer Treatment Experiment Analysis: Insights Through Data Exploration

## Introduction

This repository presents an in-depth analysis of a cancer treatment experiment conducted on laboratory mice. The experiment aimed to evaluate the efficacy of various drug regimens in reducing tumor volume. This document offers a comprehensive overview of the project's structure, methodologies, and significant discoveries.

## Data Sources

The analysis draws insights from two primary datasets:

1. **Mouse Metadata:** This dataset encompasses crucial information about the mice involved in the experiment, including unique Mouse IDs, drug regimens, age, weight, and additional attributes. The corresponding file is labeled as `Mouse_metadata.csv`.

2. **Study Results:** This dataset provides detailed insights into the outcomes of the experiment, including Mouse ID, timepoint, tumor volume, and the number of metastatic sites. This data is stored in the file named `Study_results.csv`.

## Data Processing

Prior to analysis, the data underwent meticulous preprocessing steps:

- Integration of the two datasets to form a unified DataFrame.
- Identification and resolution of duplicate data entries.
- Exclusion of data pertaining to mice with duplicate IDs.
- Computation of summary statistics for each drug regimen, encompassing mean, median, variance, standard deviation, and SEM of tumor volume.

## Exploratory Analysis

The analysis encompasses several pivotal components:

1. **Statistical Summary:** Calculation of summary statistics for each drug regimen to unravel insights into the efficacy of different treatments.

2. **Visual Representation:** Generation of diverse plots to visualize the data, including bar plots, pie charts, box plots, and scatter plots.

3. **Correlation Assessment:** Estimation of the correlation coefficient and formulation of a linear regression model to explore the relationship between mouse weight and the average observed tumor volume for the Capomulin regimen.

## Key Insights

The analysis unveils significant insights:

1. A discernible positive linear correlation is observed between mouse weight and tumor volume within the Capomulin regimen, suggesting a tendency for tumor volume to increase with mouse weight.

2. The Capomulin and Ramicane regimens demonstrate higher efficacy in reducing tumor volume compared to Infubinol and Ceftamin, as evidenced by lower mean and median tumor volumes and smaller variances.

3. No outliers are evident within the Capomulin regimen dataset, indicating the absence of extreme values or anomalous observations regarding tumor volume.
