# Solar-Energy-Power-Generation
Phase 1: Model Training and Evaluation with XGBoost

In this phase, the machine learning model was developed using XGBoost, a powerful gradient boosting algorithm suitable for regression tasks. The dataset, consisting of various meteorological and geographical features, was used to predict the generated power (in kW). Key steps in this phase included:

Data Preparation: The dataset was loaded and explored, with the features and target variable (generated_power_kw) identified. No missing values were found, and the data was split into training and testing sets (80% for training and 20% for testing).

Model Training: An XGBRegressor was trained using selected hyperparameters, including a learning rate of 0.1, 300 estimators, and a maximum depth of 6. The model was fitted on the training data.

Model Evaluation: The model's performance was evaluated using three key metrics:

Root Mean Squared Error (RMSE): 399.83, indicating the average magnitude of error between the predicted and actual values.
Mean Absolute Error (MAE): 253.31, showing the average absolute difference between predictions and actual values.
R² Score: 0.82, suggesting that the model explains 82% of the variance in the target variable, indicating a good fit.
Feature Importance Visualization: A bar chart was generated to visualize the importance of each feature in predicting the target variable. This helps in understanding which meteorological factors are most influential in solar energy power generation.

This phase establishes a solid foundation for further optimization and refinement of the model in subsequent stages.
