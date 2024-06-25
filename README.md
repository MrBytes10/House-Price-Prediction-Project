# House Price Prediction with CatBoost

This project aims to predict house prices using the CatBoost machine learning algorithm, focusing on the California housing dataset. The project is ideal for stakeholders in the real estate industry, including homebuyers, sellers, and investors.

## Key Features

1. CatBoost Integration: Utilizes CatBoost for its superior handling of categorical features, strong performance without extensive hyperparameter tuning, and effective handling of missing data.
2. California Housing Dataset: Employs a well-known dataset that includes features such as median income, house age, room and bedroom averages, population, and geographical coordinates.
3. Exploratory Data Analysis (EDA): Provides insights into the dataset through summary statistics, correlation matrix, and visualizations.
4. Model Training and Evaluation: Includes steps to train a CatBoost regression model and evaluate its performance using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²).
5. House Price Estimation Function: Defines a function to estimate house prices based on input features.

## Installation

Ensure you have Python installed, then install the necessary libraries using pip: pip install catboost pandas numpy matplotlib seaborn scikit-learn
The best version of numpy for this is any version below 2.00, as catboost works with that.

## Usage

### Step 1: Import Necessary Libraries

### Step 2: Load Dataset

### Step 3: Exploratory Data Analysis

### Step 4: Data Preprocessing

### Step 5: Train CatBoost Model

### Step 6: Make Predictions

# Evaluation metrics

mse = mean_squared_error(y_test, y_pred)
mae = mean_absolute_error(y_test, y_pred)
rsquared = r2_score(y_test, y_pred)

print("Mean Squared Error:", mse)
print("Mean Absolute Error:", mae)
print("R-squared:", rsquared)

# Plot actual vs predicted prices

### Step 7: Estimate House Prices

## Results

The model achieved the following performance on the test set:

- **Mean Squared Error**: 0.1913
- **Mean Absolute Error**: 0.2869
- **R-squared**: 0.854

These metrics indicate a strong performance in predicting house prices, with an R-squared value suggesting that the model explains approximately 85.4% of the variance in the target variable.

## Contact

For any questions or further information, please contact me at mulu.bytes@gmail.com, or visii my portfolio to check more of my work https://augastine-s-portfolio.vercel.app/.
