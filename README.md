This project focuses on predicting car prices based on their features using a Linear Regression model. It demonstrates the use of data preprocessing, feature engineering, and machine learning techniques to build a regression model capable of estimating car prices accurately.

-> Features:

1. Data Preprocessing:
- Handles missing values, scales numerical features, and one-hot encodes categorical variables for machine learning compatibility.
  
2. Model Training and Evaluation:
- Trains a Linear Regression model and evaluates its performance using:
1. Mean Absolute Error (MAE)
2. Mean Squared Error (MSE)
3. R² Score
   
3. Prediction Functionality:
- Predicts the price of a car based on its features, allowing for real-world applicability.

4. Practical Insights:
- Provides an example of using a trained model to estimate the price of a new car with specific attributes.

-> Technologies Used:

- Python: Programming language.
- Pandas: Data manipulation and analysis.
- NumPy: Numerical computations.
- Matplotlib: Visualization of data insights.
- Scikit-learn: Machine learning model training, evaluation, and preprocessing.

-> How It Works:

1. Data Loading and Exploration:
- Loads and explores the dataset, identifying patterns, distributions, and missing values.

2. Data Preprocessing:
- Scales numerical features using Min-Max Scaling.
- Encodes categorical variables with one-hot encoding for compatibility with the regression model.

3. Model Training:
- Splits the dataset into training and testing sets.
- Trains a Linear Regression model using the training set.
  
4. Model Evaluation:
- Evaluates the model’s performance on unseen test data using various metrics.

5. Car Price Prediction:
-Predicts the price of a car based on user-provided feature values.
