# Sales-Prediction
# Overview

This project predicts sales based on advertising expenditures using machine learning techniques in Python. It utilizes the Advertising Dataset, which contains advertising costs across TV, Radio, and Newspaper platforms to forecast sales performance.

# Dataset

The dataset consists of 200 entries with the following columns:

TV: Advertising budget spent on TV (in thousands of dollars)

Radio: Advertising budget spent on Radio (in thousands of dollars)

Newspaper: Advertising budget spent on Newspapers (in thousands of dollars)

Sales: Sales generated (in thousands of units)

# Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

# Clone this repository:

git clone https://github.com/Pavithra412/Sales-Prediction.git
cd Sales-Prediction

# Install required dependencies:

pip install -r requirements.txt

Run the following script to train and evaluate the model:

python src/train_model.py

# Model Training

A Linear Regression model is used to predict sales based on the advertising expenditures. The dataset is split into training and testing sets, and the model is evaluated using the following metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared (R²)

# Results

After training, the model provides insights into how advertising investments impact sales, helping businesses optimize their marketing budgets.




