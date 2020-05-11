# Pumpt it up! 
## Ensure availability of clean water by predicting the functionality of water points in Tanzania

This Repository presents my Capstone project of the neuefische Data Science Bootcamp in Hamburg at which I participated from February to May 2020. It is based on a data competition, held by [drivendata.org](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/), named Pump it up!

![](figures/WATER_TZA.jpg)


##  Content of this repository

The repository contains mainly the following three notebooks:

* **PumpItUp_Cleaning_EDA_FE**
In the first notebook you will get an overview of the given data, the features and the target variable. This notebook contains the cleaning of the data (handling of missing values, eliminating features without information etc.) and the Data Exploration of the depencies between the features and the target variable. In the last section of this notebook

* **PumpItUp_Predictive_Modeling**
The second notebook the setup of machine learning models takes places. Therefore preprocessing pipelines are built and algorithms are trained to predict whether a water point is functional, broken or is still in function but needs to be maintened.

* **PumpItUp_PumpItUp_Maps_Visualization**
In the third and last notebook maps generated with folium for visualization purposes are stored. Finally this notebook contains a Future work section as well as some conclusions gained from this project.

additional contents:

* **README.md**
This file
* **LICENSE**
* **data**
folder to store the relevant data 
* **figures**
folder to store the figures produced within the project
* **maps_folium**
folder to store html-files of created folium maps