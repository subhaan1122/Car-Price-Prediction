🚗 Car Price Prediction:

This project aims to predict the price of cars based on their features such as horsepower, car dimensions, and other specifications. The analysis uses Linear Regression for predicting car prices after preprocessing the dataset.

📌 Overview:

- Dataset: CarPrice_Assignment.csv
- Objective: Predict car prices based on various car features using machine learning.
- Tools: pandas, numpy, matplotlib, sklearn
- Model: Linear Regression
- Evaluation Metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared Score

⚙️ How It Works:

1- Data Loading & Preprocessing:

- The dataset is loaded using pandas.
- We remove the non-predictive car_ID column and scale numeric features using Min-Max scaling.
- Categorical features are one-hot encoded to create binary variables.

2- Feature and Target Variable Separation:

- The target variable price is separated from the features.
- The data is split into training and testing sets (80% training and 20% testing).

3- Model Training:

- A Linear Regression model is trained on the training data.
- The model is used to predict the price of cars in the test set.

4- Model Evaluation:

- Evaluation is done using Mean Absolute Error (MAE), Mean Squared Error (MSE), and the R-squared score.
- These metrics help determine the model's accuracy in predicting car prices.

5- Example Prediction:

A new car’s features are provided (such as symboling, wheelbase, horsepower, etc.), and the trained model predicts the car’s price.

📊 Model Evaluation:

- Metrics:
Mean Absolute Error (MAE): Indicates the average magnitude of errors in predictions.
Mean Squared Error (MSE): Indicates the average of the squared differences between actual and predicted values.
R-squared Score: Measures how well the model explains the variance in the target variable.

- Example:
For the example car (with specific features such as wheelbase, car length, etc.), the predicted price will be printed as a result of the model’s prediction.

🌟 Show some ❤️ by starring this project!

