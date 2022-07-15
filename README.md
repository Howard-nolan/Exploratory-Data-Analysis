# Exploratory Data Analysis

**Objectives:**
Exploratory Data Analysis is a standard process in the early stages of digital biomarker development. EDA allows us to explore relationships between variables in the data, examine trends, analyze missingness of data, and begin the process of understanding the link between the data and the physiological state we are studying.

**Input:**
.csv file with entire dataset. 

**Output:**
Figures for EDA (after filtering all the NULL data)

**Functions:**
This repository currently contains the following functions.

| Function | README |
| ------ | ------ |
| makehist | Plot histograms of all variables in data |
| makebox | Plot boxplot of all variables in data |
| makeleaf | Plot leafplot of all variables in data |
| makebubble | Plot bubble chart of all variables in data |
| makerun | Plot run chart of all variables in data |
| makemultivariate | Plot multivariate chart of all variables in data |
| makescatter | Plot scatterplot of all variables in data |


**Publications:**



#### Code Available Now:
***
* MissingDataAnalysis/ - a collection of analyses for exploring missingness of data
* ExploratoryDataAnalysis.ipynb - a general, all purpose EDA notebook for analyzing longitudinal wearable data with outcomes
***

**Sources:**
we use STEP Data (link: https://physionet.org/content/bigideaslab-step-hr-smartwatch/1.0/) for the EDA analysis
