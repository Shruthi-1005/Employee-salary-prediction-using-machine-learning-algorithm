# Employee-salary-prediction-using-linear-regression
Employee Salary Prediction
This project focuses on predicting whether an individual's income is greater than $50K or less than or equal to $50K based on census data. The repository contains a Jupyter Notebook that details the end-to-end process of data cleaning, preprocessing, model training, and evaluation.
Dataset
The model is trained on the "Adult" dataset, also known as the "Census Income" dataset, which includes demographic and employment-related features for individuals.
-->Project Workflow
-Data Cleaning & Preprocessing:
Loaded the dataset and handled missing values, which were denoted by ?.
Removed outliers from numerical columns like age and educational-num to improve model performance.
Dropped redundant features such as the original education column in favor of the numerical educational-num.
-Feature Engineering:
Applied LabelEncoder to convert categorical features (e.g., workclass, occupation, gender) into a numerical format suitable for machine learning models.
Utilized MinMaxScaler to scale all numerical features, ensuring that the model gives equal importance to all variables.
-Model Training & Evaluation:
The dataset was split into training (80%) and testing (20%) sets.
Multiple classification algorithms were trained and evaluated to find the best-performing model.
-Model Comparison:
-->The following models were compared based on their accuracy scores:
Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Random Forest
Gradient Boosting
The Gradient Boosting Classifier achieved the highest accuracy of 85.62%, making it the best model for this task.
