**Sales Prediction Using Machine Learning**

Project Overview

This project focuses on predicting sales using machine learning regression algorithms. It compares Linear Regression and Gradient Boosting Regression to identify which model performs better on the Superstore sales dataset.

Objectives

- To analyze the Superstore sales dataset.
- To prepare the data for machine learning.
- To build regression models for sales prediction.
- To evaluate and compare model performance.

Dataset

- Dataset: Superstore Sales Dataset
- Records: 9,994
- Target Variable: Sales
- Problem Type: Regression

Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn

Data Preprocessing

- Removed rows with missing target values.
- Separated numerical and categorical features.
- Handled missing numerical values using median imputation.
- Handled missing categorical values using most-frequent imputation.
- Applied One-Hot Encoding to categorical features.
- Split the dataset into 80% training data and 20% testing data.

Machine Learning Models

1. Linear Regression – Used as the baseline regression model.
2. Gradient Boosting Regression – Used to improve prediction performance.

Model Evaluation

The models were evaluated using MAE, MSE, RMSE and R² score.

Metric | Linear Regression| Gradient Boosting
 MAE   |    242.4177      |     200.5197
 MSE   |    486525.3473   |     470681.8153
 RMSE  |    697.5137      |     686.0625
R² 
Score  |     0.1764       |      0.2032

Result

Gradient Boosting Regression performed better than Linear Regression across the evaluation metrics used in this project. However, the R² score indicates that the models have limitations in explaining the variation in sales.

Project Files

- "Sales_prediction.ipynb" – Jupyter Notebook containing the implementation.
- "Sales_Prediction_Corrected_Report-1.pdf" – Project report.

Conclusion

This project demonstrates how machine learning regression algorithms can be used for sales prediction. Gradient Boosting Regression achieved better performance than Linear Regression on the test dataset.

Future Scope

- Improve model performance through hyperparameter tuning.
- Compare additional regression algorithms.
- Perform feature engineering.
- Explore time-based validation and additional datasets.
