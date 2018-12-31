# Landslide-Susceptibility-Assessment-Tool
Landslide-Susceptibility-Assessment-Tool.tbx file was created for ArcGIS software. 
Landslide susceptibility assessment tool includes 10 python script.
Preparing_Data.py is used to prepare data for modelling as .csv format. 
Create_LSM&&Calculate_ROC.py is used to creates Landslide Susceptibility Map and calculates Area Under Curve (AUC) values with data including X-Y coordinate and probability fields. 
Prepared data using this script can be analysed in external software. Then classification results can be processed with Create LSM and Calculate ROC script in GIS and susceptibility map can be created with AUC values.
The other scripts are used to create LSM with the methods of Frequency Ratio (FR), Information Value (IV), Logistic Regression (LR), Random Forest (RF) and Multi Layer Perceptron (MLP).
Also, this tool includes tuning script for the methods of LR, RF and MLP.

Dr.Ali POLAT (2018)
