# COMP ANALY HIGH-TP BIOMED DATA

# Programmer: Tejaswini Kakumanu

# Date: 02/21/2026

# Programming Language: Python

# Python Version: Python 3.11.11

# Description:

This project contains a Python script developed to calculate transcript half-lives for yeast genes using 60-minute time-course decay data provided in the file DecayTimecourse.txt.

## The script processes the dataset in a structured manner by:

- Cleaning and preparing the input data

- Separating three biological replicates

- Estimating transcript decay rates using a log-linear regression model

- Computing half-life values. 

## For each transcript:

- Half-life is calculated across three replicates

- The average half-life is computed

- Genes are ranked based on stability

## The script further identifies:

- Top 10% transcripts (most stable genes)

- Bottom 10% transcripts (least stable genes)

This provides insight into transcript stability and gene expression regulation dynamics in Saccharomyces cerevisiae.

# Files Needed:

DecayTimecourse.txt (input file)

# Packages Required:

The following Python libraries are required:

numpy

pandas

scipy

matplotlib

# Output Files Generated:

The script generates the following output files:

- All_HalfLives.csv
Contains computed half-life values for all valid yeast transcripts.

- high_half_life_genes_detailed_results.csv
Contains detailed results for transcripts in the top 10%.

- low_half_life_genes_detailed_results.csv
Contains detailed results for transcripts in the bottom 10%.

- high_half_life_genes.txt
Lists transcript identifiers for high half-life genes (top 10%).

- low_half_life_genes.txt
Lists transcript identifiers for low half-life genes (bottom 10%).

- half_life_overview_statistics.csv
Summary statistics of calculated half-life values.

- half_life_distribution_overview.png
Histogram visualization of transcript half-life distribution.

# How to Run the Program
Using Google Colab:

- Open the provided .ipynb file in Google Colab.

- Upload DecayTimecourse.txt when prompted.

- Run all cells sequentially.

- Download generated output files from the left file panel.
