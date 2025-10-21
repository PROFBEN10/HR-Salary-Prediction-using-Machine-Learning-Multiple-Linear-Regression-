# HR-Salary-Prediction-using-Machine-Learning-Multiple-Linear-Regression-
This project helps the HR department automatically predict salary for job candidates based on their experience, written test score, and interview score — using a Machine Learning model (Multiple Linear Regression).
# Business Problem
HR teams often struggle with manual and inconsistent salary decisions during hiring. This can lead to:

. Salary bias or human guesswork

. Slow hiring process

. Difficulty justifying offers to management

This project solves that by providing an intelligent, data-driven salary prediction system.
# Project Objectives
✔ Build a machine learning model to predict salary in USD
✔ Assist HR in making fair, consistent, instant salary decisions
✔ Provide explainable insights — which factor affects salary the most
# Dataset Features
| Feature         | Description                            |
| --------------- | -------------------------------------- |
| experience      | Years of professional experience       |
| test_score      | Written exam score (0–10)              |
| interview_score | Personal interview score (0–10)        |
| salary          | Final salary offered (target variable) |

# Tech Stack
Python (Pandas, NumPy)

Scikit-Learn (Multiple Linear Regression)

Matplotlib (Visualizations)

# Model Used

Multiple Linear Regression — a supervised ML algorithm that predicts a continuous value (salary) using multiple input factors.

Salary = b₀ + b₁(Experience) + b₂(Test Score) + b₃(Interview Score)

# Example Predictions
salpred.predict([[2, 9, 6]])    # 2 years exp, test 9, interview 6
salpred.predict([[12, 10, 10]]) # 12 years exp, test 10, interview 10

