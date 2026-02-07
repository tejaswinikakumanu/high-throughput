# Assignment 1: Pearson Correlation Analysis of miRNA Expression

**Author:** Tejaswini Kakumanu
**Date:** 02/06/2026


### Language
- Python 

### Packages
- pandas 
- numpy 
- seaborn 
- matplotlib 
- scipy 

### Tools
- Google Colab 

## Program Overview

This program analyzes miRNA expression data across multiple cancer types using Pearson correlation analysis. The goal is to quantify and visualize similarity patterns between cancers within each dataset and to compare the overall correlation structure between two patient groups.

The workflow consists of:
1. Loading miRNA expression data from two input matrices.
2. Computing 12 × 12 Pearson correlation matrices representing pairwise correlations between cancer types.
3. Visualizing each correlation matrix using heatmaps to highlight similarity patterns.
4. Computing a final Pearson correlation between Matrix 1 and Matrix 2 to assess overall similarity between the two datasets.

This analysis follows the requirements specified in Assignment 1.

## Inputs

### Files
- `matrix1.txt`  
  Tab-separated file containing miRNA expression (RPKM values) across 12 cancer types for patient group 1.

- `matrix2.txt`  
  Tab-separated file containing miRNA expression (RPKM values) across 12 cancer types for patient group 2.

### Parameters
- No user-defined parameters are required.
- Pearson correlation is computed using default settings.


## Outputs

### Tabular Outputs
- `correlation_matrix1.csv`  
  12 × 12 Pearson correlation matrix derived from Matrix 1.

- `correlation_matrix2.csv`  
  12 × 12 Pearson correlation matrix derived from Matrix 2.

- `matrix1_matrix2_correlation.csv`  
  CSV file containing the Pearson correlation coefficient and p-value comparing Matrix 1 and Matrix 2.

### Visual Outputs
- `heatmap - Matrix 1.png`  
  Heatmap visualization of the Pearson correlation matrix for Matrix 1.

- `heatmap - Matrix 2.png`  
  Heatmap visualization of the Pearson correlation matrix for Matrix 2.

All results are also displayed directly within the Jupyter notebook (`main.ipynb`).



## Generative AI Disclosure

Generative AI tools were used for clarification of assignment requirements and assistance for documentation. All analysis logic, results, and interpretations were independently reviewed, validated, and executed by me.



