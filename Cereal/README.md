# Cereal Analysis

## Prerequisites

##### Software
R with ability to read RMD files, Python, Jupyter

##### Packages
pandas, numpy, matplotlib, sklearn, mpl_toolkits, seaborn, 
factoextra, tidyverse, dplyr, ggplot, ggpubr

## Code Description
Several PDFs contain Python code that was originally in a IPYNB file and converted for readers viewing convience.
The original file can be found in the "original code" folder.

##### Cereal_cleaning - Jupyter Notebook
This section cleans the data by checking for null values and changing labeling/organization of the data.
##### Cereal_EDA
Here we create several visualizations that will be used in the presentation.
##### Cereal_PCA
In this document we conduct Principal Component Analysis to find which features impact the disinction between healthy and unhealthy cereal.
##### Cereal Clustering - Jupyter Notebook
Now we use unsupervised KMeans clustering to separate the data into two clusters. We then create visualizations based on the cluster to identify trends which separate the clusters.
##### Cereal Linear Regression - Jupyter Notebook
This code is used for feature selection and linear regression to find the impacts of cereal features on the score given by consumers.