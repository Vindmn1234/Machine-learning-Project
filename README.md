# Machine-learning-Project
This repository contains a machine learning project focused on predicting housing prices in California using the dataset based on the 1990 California census. The data includes metrics such as population, median income, median housing price, and more for each block group in California.


The project undertakes the following key steps to build and evaluate the predictive models:

Data Preprocessing: The raw dataset is processed to transform features, handle missing values, and encode categorical variables to prepare it for machine learning algorithms.
Feature Engineering: We create additional features like the log transformation of skewed data and feature combinations that could provide more insight to the models.

Model Training and Evaluation: We train Linear Regression, Random Forest Regressor and Adaboost model.
Each model's performance is evaluated using the R-squared metric and Mean Squared Error (MSE) to determine the accuracy and precision of the predictions.
K-Fold Cross-Validation: To ensure the robustness of our models, we implement k-fold cross-validation. This technique helps in assessing how the results of our statistical analysis will generalize to an independent dataset and mitigates overfitting.
Model Interpretation: Tools like SHAP (SHapley Additive exPlanations) are used to interpret the Random Forest model, providing insights into the impact of each feature on the housing price predictions.
Comparison of Models: The results from Linear Regression and Random Forest models are compared to understand their performance relative to each other.




