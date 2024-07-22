# Customer-Churn-Prediction
Predict customer churn using various classification models, including Logistic Regression, Naive Bayes, K-Nearest Neighbors, Support Vector Machine, and Decision Tree Classifier on the Telco Customer Churn dataset.
## Introduction
This project aims to predict customer churn using multiple classification models. It involves data preprocessing, feature engineering, model training, and evaluation to determine the best performing model for predicting customer churn.

## Technology Stack
Python: For data analysis and modeling.
Pandas, NumPy: Data manipulation and numerical operations.
Matplotlib, Seaborn: Data visualization.
Scikit-Learn: Machine learning algorithms and metrics.
Imbalanced-Learn: For handling imbalanced datasets with SMOTE.
## Methodology
Data Cleaning: Handle missing values and convert data types.
Exploratory Data Analysis (EDA): Analyze and visualize data distributions and relationships.
Feature Engineering: Encode categorical variables and handle imbalances using SMOTE.
Model Training: Train and evaluate Logistic Regression, Naive Bayes, K-Nearest Neighbors, Support Vector Machine, and Decision Tree Classifier models.
Model Evaluation: Assess model performance using accuracy, precision, recall, and F1-score metrics.
## Results

The following table summarizes the performance metrics for different classification models:

| Model Name              | Accuracy | Precision | Recall   | F1-Score |
|-------------------------|----------|-----------|----------|----------|
| Logistic Regression     | 0.823814 | 0.823822  | 0.823814 | 0.823815 |
| Naive Bayes             | 0.762827 | 0.774108  | 0.762827 | 0.760493 |
| K-Nearest Neighbors      | 0.782672 | 0.785823  | 0.782672 | 0.782131 |
| Support Vector Machine  | 0.650532 | 0.652933  | 0.650532 | 0.648967 |
| Decision Tree Classifier| 0.811229 | 0.811244  | 0.811229 | 0.811230 |

*Note: Metrics are based on test data and evaluated using accuracy, precision, recall, and F1-score.*

* Logistic Regression and Decision Tree Classifier have the best performance overall, showing high accuracy, precision, recall, and F1-score.
* Both models demonstrate consistency across all metrics, indicating balanced performance and robustness in predictions.
## Visualizations
Count Plots: Visualize the distribution of categorical variables.
Tenure vs Churn KDE Plot: Display the relationship between customer tenure and churn status.
Churn Frequency by Tenure: Line plot showing the number of customers by churn status over tenure.
Correlation Matrix Heatmap: Correlation of features with the target variable.
Conclusion
Logistic Regression and Decision Tree Classifier emerged as the top performers in predicting customer churn, offering a balanced and reliable approach for classification. The results indicate that these models are well-suited for handling the dataset and providing accurate predictions.
