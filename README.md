# Diabetes Diagnostics Using K-Nearest Neighbors (KNN)
This project utilizes the K-Nearest Neighbors (KNN) algorithm, a popular supervised machine learning model, to perform diabetes diagnostics. The goal is to predict whether a patient has diabetes based on specific medical measurements.

## Project Overview
K-Nearest Neighbors (KNN) is a classification algorithm that assigns a data point to the class most common among its K nearest neighbors. This project applies the KNN algorithm to a diabetes dataset to classify patients as either diabetic or non-diabetic based on features like glucose level, blood pressure, and other relevant medical metrics.

## Project Workflow
### 1. Data Loading
The dataset is loaded into a pandas DataFrame. The dataset includes various medical features and a target variable indicating diabetes diagnosis.
### 2. Data Preparation
The predictor variables (features) and the target variable are separated.
The dataset is split into training and testing sets, with stratification to ensure class distribution consistency.
### 3. Model Building and Training
A KNN model is built using the scikit-learn library.
The model is trained on the training dataset.
### 4. Model Evaluation
The model's performance is evaluated using the test dataset, and metrics such as accuracy, precision, and recall are analyzed to assess its effectiveness.

## Results
The final KNN model is evaluated based on its ability to accurately diagnose diabetes in the test set. This involves comparing the model's predictions to the actual outcomes and calculating performance metrics.

## Dependencies
- Python 3.x
- Pandas
- Scikit-learn

## How to Run
1. Clone the repository.
2. Ensure you have the required dependencies installed.
3. Run the Jupyter Notebook to see the implementation and results.

## Author
Sahngyoon Rhee
