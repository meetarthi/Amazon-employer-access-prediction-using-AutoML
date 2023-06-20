# Amazon-employer-access-prediction-using-AutoML

Problem Link: https://www.kaggle.com/competitions/amazon-employee-access-challenge

**Objective**
-----------------------------------------------------------
Predict an employee's access needs, given his/her job role.
Models that automatically identify access privileges as employees enter and exit roles within a company can be built using data linked to current employees and their granted access. 
These automatic access models aim to reduce the amount of human interaction necessary to facilitate employee access. The model will take an employee's role information and a resource code and return whether or not access should be granted.


**Workflow**
-----------------------------------------------------------
1. Initialize the H2O environment and import the necessary libraries.
2. Load the training and test datasets from the Amazon dataset.
3. Convert the datasets from Pandas dataframes to H2O dataframes.
4. Set up the H2O AutoML configuration, including the maximum number of models and random seed.
5. Train the AutoML models using the training dataset.
6. Evaluate the leaderboard to identify the best-performing model.
7. Make predictions on the test dataset using the best model.
8. Combine the predicted column with the test dataset.
9. Submit the predicted output to Kaggle for scoring and comparison.

**Results**
----------------------------------------------------------
Based on the competition leaderboard, the model achieved a score of 50%.
