# Employee-salary-prediction-using-machine-learning-algorithm
Employee Salary Prediction
This project uses machine learning to predict whether an employee's salary is above or below $50,000 per year based on demographic and employment data. The entire data analysis, model training, and evaluation process is detailed in the accompanying Jupyter notebook. The best-performing model is deployed in a user-friendly Streamlit web application.
Key Features:
->Data Cleaning & Preprocessing: Handles missing values, removes outliers, and eliminates redundant features to ensure a high-quality dataset.
->Feature Engineering: Applies label encoding to categorical variables and scales numerical features for optimal model performance.
->Model Training & Comparison: Trains and evaluates a variety of classification models, including Logistic Regression, K-Nearest Neighbors, SVM, Random Forest, and Gradient Boosting.
->Top Performance: The Gradient Boosting Classifier was identified as the best model, achieving an accuracy of approximately 85.62% on the test set.
->Interactive Application: A web app built with Streamlit allows for easy, real-time salary predictions.
File Structure:
Employment_salary_prediction.ipynb: The Jupyter notebook containing all data analysis, preprocessing, and model training steps.
app.py: The Python script for the Streamlit web application.
best_model.pkl: The saved, trained Gradient Boosting model, ready for predictions.
adult 3.csv: The raw dataset used for this project.
