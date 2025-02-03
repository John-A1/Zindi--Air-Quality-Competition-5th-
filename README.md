# Zindi--Air-Quality-Competition-5th-

Project Overview
Main/
|--README.md/                          #It contains necessary documentation about the code
|--SampleSubmission.csv/               #Sample submission file from the hackathon, and was used for making my prediction submission
|--Train (2).csv/                      #Training datasets provided for the hackathon
|--Variable Description.csv/           #Descriptions to each variables in the datasets
|--WINNING CODE 5TH.ipynb/             #Jupyter notebook file code that won the 5th place
|--requirements.txt/                   #Necessary libraries to install
|--submissionSOFT.csv/                 #Submission file that ranked 5th on the Zindi Competition - [(public score - 4.4.898868936, Private Score-4.845152084])
|--test (2).csv/                       #Test datasets provided for the hackathon.


ORDER OF EXECUTION
1. Installing Libraries
2. Loading of datasets (training datasets, test dataset & submission sample)
3. Reading of the datasets(training datasets & test dataset)
4. Feature engineering - Creating new columns
5. EDA - Checking the info of train set
6. Visualizing Distribution of Target variable
7. Feature Selection - Selecting my feature variables and taget variable
8. Dependent & Independent Selection - splitting my train dependent and independent variabel via feature selection
9. train_test_split - Spitting my dependent and independent variable into train and test split
10. Preprocessing pipeline - Creating a pipeline to transform columns
11. Hyperparameter tuning with Optuna - creating some hyperparameters with optuna to Create a RandomForestRegressor model
12. Best Model Training - Using best_params method to get best Model training
13. Evaluating Model (Evaluation) - predicted for both train and validation, and got their rmse
14. Predicting on test dataset
15. Using the Sample submission convert the CO2 to the prediction from test data
16. Submission file.

FEATURES USED
Numerical Features: Scaled using StandardScaler.
Categorical Features: Encoded using One-Hot Encoding for 'device_name' column.
Feature Selection: Selecting feature variable in the datasets and target variables.
Hyperparameter Optimization: Used Optuna for hyperparameter tuning.
Model used- RandomForestRegressor

Environment
This project runs on an Anaconda environment (Jupyter notebook file).

Hardware Needed
Jupyter notebook
PC-Hp Elitebook intel core i7

Expected Run Time
Every aspect of the code (Except Hyperparameter tuning) should take about ~2 minutes
Hyperparameter tuning should be about ~20 minutes


