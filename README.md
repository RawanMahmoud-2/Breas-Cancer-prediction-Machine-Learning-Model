# Breas-Cancer-prediction-Machine-Learning-Model
This machine learning model is designed using python to detect and classify breast cancer as either benign or malignant based on the dataset from the Breast Cancer Wisconsin dataset. The model performs several key steps from data processing to evaluation algorithms.

Steps
1. Exploratory Data Analysis (EDA)
Load the dataset and perform basic checks such as:

info(), describe(), shape()

Check for missing values using isna().sum()

Visualize correlations and relationships between features:

Use pair plots and heatmaps.

2. Data Preprocessing
Standardize numerical features using StandardScaler.

Encode the target variable (diagnosis) from categorical labels to numerical values using LabelEncoder.

Separate features (X) from the target variable (y).

3. Dataset Splitting
Split the dataset into training and testing sets using train_test_split from sklearn.model_selection.

4. Machine Learning Model Initialization and Training
Train multiple machine learning models:

Logistic Regression

K-Nearest Neighbors (KNN)

Naive Bayes

Decision Tree

Random Forest

Kernel SVM

Support Vector Machine (SVM)

5. Prediction
Use each trained model to make predictions on the test set (x_test).

6. Model Evaluation
Evaluate each model using:

Classification reports: Calculate accuracy, recall, precision, F1-score, mean absolute error, and R2 score.

7. Confusion Matrix
For each model, display the confusion matrix using confusion_matrix() from sklearn.metrics and visualize with seaborn.heatmap.

8. ROC Curves
Plot the ROC curves for each model using roc_curve() from sklearn.metrics and visualize them.
