# Data-Visualization-Challenge: Cancer Treatment Experiment Analysis

## Overview

This repository contains the analysis of a cancer treatment experiment conducted on laboratory mice. The experiment involved testing different drug regimens to determine their effectiveness in reducing tumor volume. This README file provides an overview of the project, its structure, and key findings.

## Data Sources

The analysis is based on two main data sources:

1. **Mouse Metadata:** This dataset contains information about the mice used in the experiment, including unique Mouse IDs, drug regimen, age, weight, and more. The file is named `Mouse_metadata.csv`.

2. **Study Results:** This dataset includes detailed information about the experiment's results, including the Mouse ID, timepoint, tumor volume, and the number of metastatic sites. The file is named `Study_results.csv`.

## Data Preprocessing

Before conducting the analysis, the following data preprocessing steps were performed:

- Merging the two datasets to create a single DataFrame for analysis.
- Identifying and handling duplicate data points.
- Removing any data for mice with duplicate IDs.
- Calculating summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.

## Data Analysis

The analysis included the following key components:

1. **Data Summary Statistics:** Calculation of summary statistics for each drug regimen, providing insights into the effectiveness of different treatments.

2. **Data Visualizations:** Generation of various plots to visualize the data, including bar plots, pie charts, box plots, and scatter plots.

3. **Correlation Analysis:** Calculation of the correlation coefficient and linear regression model for mouse weight and average observed tumor volume for the Capomulin regimen.

## Key Findings

Based on the analysis, the following key findings were made:

1. There is a strong positive linear relationship between mouse weight and tumor volume in the Capomulin regimen, indicating that as mouse weight increases, tumor volume tends to increase as well.

2. The Capomulin and Ramicane regimens appear to be more effective in reducing tumor volume compared to Infubinol and Ceftamin, as evidenced by lower mean and median tumor volumes and smaller variances.

3. No outliers were identified in the Capomulin regimen, suggesting that the data points do not exhibit extreme values or unusual observations in terms of tumor volume.

## Conclusion

This analysis provides valuable insights into the outcomes of the cancer treatment experiment and the effectiveness of different drug regimens. The findings can be used to inform further research and decision-making in the context of cancer treatment.

For more details and specific analysis results, please refer to the Jupyter Notebook file provided in this repository.


