# Diabetes-Prediction-Analysis
# Report on Diabetes Prediction Analysis
https://www.linkedin.com/posts/mercy-okebiorun_report-on-diabetes-prediction-analysis-introduction-activity-7129026279994998784-DpNR?utm_source=share&utm_medium=member_ios

## Introduction

This report presents an analysis of a diabetes prediction model implemented in Python. The analysis involves data preprocessing, exploratory data analysis (EDA), 
model training using Support Vector Machines (SVM), and the creation of a user-friendly interface for predicting diabetes.

## 1. Data Exploration

The dataset used in this analysis is a diabetes dataset with 768 instances and 9 features, including information such as pregnancies, glucose level,
blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, age, and outcome (0 or 1 indicating non-diabetic or diabetic). 
The initial exploration of the dataset provides insights into its structure and summary statistics.

- *Summary Statistics:*
  - The dataset contains 768 rows and 9 columns.
  - Descriptive statistics reveal information about the central tendency, dispersion, and shape of the distribution for each feature.

- *Missing Values and Duplicates:*
  - No missing values are found in the dataset.
  - No duplicate values are present.

- *Outcome Distribution:*
  - The outcome distribution shows that 500 instances are labeled as non-diabetic (Outcome=0), and 268 instances are labeled as diabetic (Outcome=1).

- *Outcome Statistics:*
  - Mean values for various features are provided based on the outcome.
  - This gives insights into potential differences in feature values between diabetic and non-diabetic groups.

## 2. Data Preprocessing

- *Feature Scaling:*
  - StandardScaler is applied to standardize the feature values. This ensures that all features contribute equally to the model.

- *Train-Test Split:*
  - The dataset is split into training and testing sets (80% training, 20% testing) using stratified sampling to maintain the distribution of outcomes in both sets.

## 3. Model Training

- *Support Vector Machine (SVM):*
  - A linear Support Vector Machine (SVM) classifier is chosen for the model. SVMs are effective for binary classification tasks, making them suitable for predicting diabetes.

- *Model Accuracy:*
  - The model achieves an accuracy score of approximately 78.7% on the training data and 77.3% on the test data.

## 4. User Interface

- *Tkinter Interface:*
  - A user-friendly Tkinter interface is created to facilitate input of new data for diabetes prediction.
  - Entry fields are provided for each feature, and a "Predict Diabetes" button triggers the prediction.
  - The prediction result is displayed, indicating whether the person is diabetic or not.

## Conclusion

The diabetes prediction model demonstrates satisfactory accuracy on both training and test data. The Tkinter interface provides a convenient means for users 
to input data and obtain predictions. Continuous monitoring and potential updates to the model can further enhance its accuracy and usability. This analysis showcases 
the integration of machine learning models with user interfaces,
promoting practical applications in healthcare and data-driven decision-making.
