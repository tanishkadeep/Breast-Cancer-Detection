# Breast Cancer Detection Using Machine Learning

This project aims to predict whether a breast cancer is benign or malignant based on various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features describe characteristics of the cell nuclei present in the image.

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set. The dataset is described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

Link for the dataset: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data 

## Project Overview

The project uses Python for data analysis and machine learning. The libraries used include pandas, numpy, seaborn, matplotlib, and scikit-learn. The code includes data preprocessing, exploratory data analysis, feature selection, data scaling, model training, and model evaluation.

The machine learning models used in this project include Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree, Random Forest, Gradient Boosting and XGBoost.

## Setup

1. Clone the repository.
2. Install the required libraries.
3. Run the Python script.

## Results and Visualizations

1. ROC Curve: The ROC curve is plotted for each model to visualize its performance in terms of sensitivity and specificity.
- The ROC curve is saved as "roc_breast_cancer.jpeg."
2. Performance Evaluation: A bar chart is created to compare the accuracy and ROC values of different models.
- The chart is saved as "PE_breast_cancer.jpeg."

## Conclusion

The project aims to demonstrate the application of machine learning models in breast cancer detection. The results and visualizations provide insights into the performance of different algorithms, helping in choosing the most suitable model for this classification task.
