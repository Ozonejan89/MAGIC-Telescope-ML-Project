# MAGIC-Telescope-ML-Project
A machine learning project using Scikit-learn to classify particles from the MAGIC Gamma Telescope dataset.
# Classification of Cosmic Particles using Machine Learning

## Project Overview
This project uses the MAGIC Gamma Telescope dataset to build and evaluate four different machine learning models for classifying high-energy particles. The goal was to apply an end-to-end machine learning workflow, from data preparation to model comparison, to identify the most accurate classification model.

## Workflow
1.  **Data Preparation:** The data was loaded using Pandas, separated into features (X) and a target (y), and then split into an 80% training set and a 20% testing set.
2.  **Feature Scaling:** Scikit-learn's `StandardScaler` was used to scale all features. This is a crucial step for distance-based algorithms like KNN and a best practice for many other models.
3.  **Model Training & Comparison:** Four different classification models were trained on the scaled data and evaluated for accuracy:
    * Logistic Regression
    * Decision Tree
    * Random Forest
    * K-Nearest Neighbors (KNN)

## Results
The models were evaluated based on their accuracy scores on the unseen test data. The Random Forest Classifier was the top-performing model.

| Model                 | Accuracy  |
| --------------------- | --------- |
| Random Forest         | 88.41%    |
| K-Nearest Neighbors   | 83.44%    |
| Decision Tree         | 81.26%    |
| Logistic Regression   | 79.31%    |

## Conclusion
The Random Forest model proved to be the most effective for this classification task. This project successfully demonstrates a complete and reproducible machine learning workflow.
