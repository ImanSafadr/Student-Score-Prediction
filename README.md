📘 Description

The Student Score Prediction project uses a simple linear regression model and Polynomial regression to predict a student’s exam score based on the number of study hours.
This project demonstrates the basic steps of building a machine learning model — from data exploration to model evaluation — using Python and popular data science libraries.

📂 Dataset

The dataset contains two columns:

Hours – Number of hours a student studies

Scores – Marks obtained by the student

The dataset shows a strong linear relationship between study hours and exam scores, making it ideal for regression analysis.

⚙️ What the Code Does

Import Libraries – Load required Python libraries like pandas, numpy, matplotlib, and scikit-learn.

Load Dataset – Read the dataset into a DataFrame for analysis.

Data Visualization – Plot a scatter graph to observe the relationship between study hours and scores.

Data Preprocessing – Split data into independent (Hours) and dependent (Scores) variables.

Train-Test Split – Divide the dataset into training and testing sets.

Model Training – Train a Linear Regression model using the training data.

Prediction – Predict the student’s score based on the number of study hours.

Model Evaluation – Evaluate performance using metrics like Mean Absolute Error (MAE) and Root Mean Square Error (RMSE).

Visualization – Plot the regression line to visualize the model’s predictions.

🧾 Outcome

After training, the model can accurately predict a student’s score when given the number of hours they studied.
