# task-6
AI & ML Internship – Task 6
Linear Regression – House Price Prediction
1. Introduction

House Price Prediction is a regression problem where the goal is to predict a continuous numeric value (house price) based on multiple features such as location, income, and house characteristics.

In this task, Linear Regression is used because it models the linear relationship between input features and the target variable.

2. Tools Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

3. Dataset

Dataset: House Prices / California Housing Dataset

Target Variable: House price (continuous numeric value)

4. Problem Statement

To predict house prices using a Linear Regression model and evaluate its performance using appropriate regression metrics.

5. Data Loading

California housing dataset is loaded

Converted into a Pandas DataFrame

Dataset is inspected using:

.head()

.info()

.describe()

6. Feature and Target Separation

Input features are stored in X

Target variable (house price) is stored in y

Confirmed that y is continuous

7. Train–Test Split

Dataset is split into:

Training set

Testing set

train_test_split is used with a fixed random_state

Reason:
To evaluate model performance on unseen data.

8. Model Training

Linear Regression model is created using LinearRegression()

Model is trained using training data

9. Prediction

Predictions are generated on test data

A small comparison table is created showing:

Actual values

Predicted values

10. Model Evaluation Metrics

The model is evaluated using:

1. MAE (Mean Absolute Error)

Average of absolute prediction errors

Lower MAE → Better model

2. RMSE (Root Mean Squared Error)

Penalizes large errors more than MAE

Important for understanding prediction accuracy

11. Predicted vs Actual Plot

Scatter plot is created

X-axis → Actual house prices

Y-axis → Predicted house prices

Closer points to diagonal line → Better performance

12. Model Interpretation

Model coefficients are analyzed

Higher coefficient value → Feature has greater impact on house price

13. Deliverables

Jupyter Notebook (.ipynb)

MAE and RMSE report

Predicted vs Actual plot

14. Final Outcome

Built a complete regression model

Understood evaluation metrics for regression

Learned how to interpret model coefficients
