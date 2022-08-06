# Exploratory Data Analysis

**Objectives:**
Exploratory data analysis (EDA) is the first step in the data analysis process. It involves using a number of tools to get a picture of what’s happening within a dataset. When done right, exploratory data analysis can highlight new aspects of a dataset, inform researchers where to focus their effort, and lead to new conclusions.

**Input:**
.csv file with entire dataset. 

**Output:**
Figures for EDA (after filtering all the NULL data)

**Functions:**
The EDA has seven main categories of functions:

- Preliminary EDA
- Covariance matrices
- Missing value analysis
- Distribution visualization
- Data visualizations
- Clustering
- Principal Components Analysis

**Overview:**

**Preliminary EDA**

Preliminary Exploratory Data Analysis is the most basic overview of the data. Methods like len() and .describe() can allow a researcher to see how large their dataset is and get different statistical descriptions of their dataset. When you’re first reading in a data file to your jupyter notebook, this is a good place to start. 

**Covariance matrices**

Covariance is a measure of how much two random variables vary together. It’s similar to variance, but where variance tells you how a single variable varies, covariance tells you how two variables vary together. This can give you a sense of what interesting relationships may exist in your data that you can explore further.

**Missing Value Analysis**

The missing value analysis section of the repository utilizes the ‘missingno’ package that can be run to see where missing values exist in the data. This is useful if you want to see where potential gaps exist in your dataset.

**Plot Distribution**

Plot distribution can give a researcher a sense of the spread of their dataset and the balance of different variables. The EDA Module has methods that allow a researcher to determine the balance of the outcome variable, plot distributions by the outcome class, and outlier analysis.

**Data Visualizations**

Data visualization is the largest part of the EDA module. They allow a researcher to understand their data in many ways by providing different views of the dataset. The data visualizations can be manipulated to better fit a particular dataset and create the most useful visualizations. The visualizations in the EDA module utilize the matplotlib library. We have seven different visualizations that a researcher can use to understand their data.

**Clustering**

There are various methods for clustering data in the EDA Module. This allows for data to be grouped based on shared attributes using machine learning. The two types of data clustering that the EDA module contains are K-means clustering and hierarchical clustering. 

**Principal Component Analysis (PCA)**

PCA allows researchers to get a sense of the variables that explain the greatest variance in their data. This can be useful when researchers are deciding what variables they want to focus their effort on. The EDA module provides code for PCA that utilizes methods from the sklearn library and visualizations from matplotlib.


#### Code Available Now:
***
* MissingDataAnalysis/ - a collection of analyses for exploring missingness of data
* ExploratoryDataAnalysis.ipynb - a general, all purpose EDA notebook for analyzing longitudinal wearable data with outcomes
***

**Sources:**
we use STEP Data (link: https://physionet.org/content/bigideaslab-step-hr-smartwatch/1.0/) for the EDA analysis
