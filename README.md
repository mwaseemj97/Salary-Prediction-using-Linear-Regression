Salary Prediction using Linear Regression

This is a basic Machine Learning project that predicts the salary of a person based on their years of experience using the Linear Regression algorithm. The project demonstrates the complete workflow of a simple ML model, from data loading and visualization to model training and prediction.

Project Overview

The goal of this project is to:

Understand the working of Linear Regression

Train a model using numerical data

Visualize the relationship between experience and salary

Predict salary for unseen experience values

This project is suitable for beginners who are starting to learn Machine Learning concepts.

Dataset

The dataset contains two columns:

YearsExperience – Number of years a person has worked

Salary – Corresponding salary

The dataset shows a linear relationship between experience and salary, making it appropriate for Linear Regression modeling.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

Project Workflow

Import required libraries

Load and explore the dataset

Visualize data using scatter plot

Split data into training and testing sets

Train the Linear Regression model

Predict salary based on experience

Plot the regression line

Evaluate model performance

Visualization

The project includes:

Scatter plot of actual data

Regression line representing predicted salary trend

How to Run

Clone the repository

git clone <repository_link>

Install required libraries

pip install pandas numpy matplotlib scikit-learn

Run the Jupyter Notebook

jupyter notebook

Open the .ipynb file and execute the cells.

Sample Prediction

You can predict salary for any experience value using:

model.predict([[5]])

This will return the estimated salary for 5 years of experience.

Conclusion

Linear Regression successfully captured the relationship between experience and salary.

The model can estimate salary for new inputs based on experience.

This project helped in understanding fundamental Machine Learning concepts such as model training and prediction.

Contribution

Feel free to fork this repository and improve the project with additional features such as model evaluation metrics or a user interface.
