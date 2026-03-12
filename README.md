# fraud-_detecttion_eda_ann
End-to-end fraud detection pipeline using Python, EDA, feature engineering, SMOTE, and an Artificial Neural Network (ANN) to detect fraudulent financial transactions.



## Project Overview
This project analyzes fraudulent transactions using exploratory data analysis, feature engineering, and an Artificial Neural Network (ANN).

## Objective
To identify fraud patterns based on transaction amount, time, customer demographics, merchant behavior, and geographic distance.

## Dataset
- Dataset name: fraudTest.csv
- Target variable: is_fraud

## Steps Performed
- Data cleaning
- Exploratory Data Analysis
- Time-based analysis
- Heatmaps
- Outlier detection
- Feature engineering
- SMOTE for class imbalance
- ANN model building

## Key Features Engineered
- hour
- day_of_week
- age
- transactions_per_customer
- merchant_risk

## Model
- Artificial Neural Network (ANN)
- Activation: ReLU, Sigmoid
- Loss: Binary Crossentropy
- Optimizer: SGD

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Results
Add your confusion matrix, classification report, and ROC-AUC score here.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
