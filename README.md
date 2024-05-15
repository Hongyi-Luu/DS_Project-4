# DS_Project-4 Bertelsmann/Arvato Customer Segmentation

### Table of Contents

1. [Installation](#installation)
2. [Project Descriptions](#descriptions)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There are no specific libraries required to run the code beyond the Anaconda distribution of Python. The code is compatible with Python version 3 and should run without issues.

## Project Descriptions <a name="descriptions"></a>

This project consists of two major steps: the Customer Segmentation and the Supervised Learning predictive model, aimed at enhancing marketing strategies for Arvato Financial Services.

1. Customer Segmentation Report: 

    In the first half, unsupervised learning techniques were employed to analyse and segment the demographics of established customers in comparison to the general population in Germany. It helps identify key clusters within the general population that closely align with the core customer base of the mail-order company.

2. Supervised Learning Model

    Building on the insights from part 1, the second half involves developing a supervised learning model to predict the likelihood of individuals responding to a mail-order campaign. The predictions could suggest the potential of converting targeted individuals into customers, providing a valuable tool for optimising marketing efforts.

## File Descriptions <a name="files"></a>

A single notebook, titled 'Arvato Project Workbook.ipynb', showcases the work related to the project.

The documents "DIAS Information Levels - Attributes 2017.xlsx" and "DIAS Attributes - Values 2017.xlsx" were used to understand and pre-process the data. The datasets "Udacity_AZDIAS_052018.csv" and "Udacity_CUSTOMERS_052018.csv" were key sources for customer segmentation, while "Udacity_MAILOUT_052018_TEST.csv" and "Udacity_MAILOUT_052018_TRAIN.csv" were used for supervised learning.

Due to data privacy concerns, the author was not permitted to share the data provided by Arvato Financial Services.

## Summary of Results<a name="results"></a>

The customer segmentation analysis divided the population into 16 clusters, with some clusters being more or less likely to be in the customer base. 

In the supervised learning predictive analysis, a Random Forest model was adopted, achieving a Recall Score of 91%. The model predicted 1,035 out of 42,833 individuals as potential responders to the mail-order campaign. 

The detailed analysis can be found at the post available [here](https://medium.com/@hongyiluu/customer-segmentation-bertelsmann-arvato-marketing-modelling-2ce2347637e4). 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Hongyi Lu is the author of this analysis. The datasets were obtained from [Udacity](https://www.udacity.com/), provided by Arvato Financial Solutions. This study is a part of Hongyi's projects on Udacity Data Science Nanodegree. Apart from the source data, feel free to use the code here as you wish! 