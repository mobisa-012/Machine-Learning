## Project Overview
This project implements a K-Nearest Neighbors (KNN) classifier to detect fraudulent credit card transactions. 
The model is trained on a dataset from Kaggle containing credit card transactions, where the goal is to classify transactions as either legitimate (0) or fraudulent (1).

## Dataset
The dataset used is the "Credit Card Fraud Detection" dataset from Kaggle:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Note: The dataset is too large to include in the repository directly.

# Dependencies
1. Python 3.x
2. pandas
3. numpy
4. scikit-learn
5. seaborn

Install requirements with:

# pip install pandas numpy scikit-learn seaborn 

# Data Preprocessing
Removed the 'Time' column as it was deemed irrelevant

Normalized the 'Amount' column using StandardScaler

Split the data into training (70%) and testing (30%) sets

# Model Implementation
Implemented KNN classifier with 5 neighbors

Evaluated using confusion matrix and classification report

Visualized results with a heatmap

# How to Run
Download the dataset from Kaggle

Update the file path in the code to point to your local copy

Run the script

Results
The script outputs:

1. The processed dataframe

2. Confusion matrix

3. Classification report (precision, recall, f1-score)

4. Heatmap visualization of the confusion matrix