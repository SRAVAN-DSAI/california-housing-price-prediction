# California Housing Price Prediction

This project aims to predict housing prices in California using machine learning techniques, specifically **Linear Regression**. The dataset used is the **California Housing dataset** from scikit-learn, which includes various features like average income, house age, and the median house value for different California districts.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Model Evaluation](#model-evaluation)
5. [License](#license)

## Project Overview

The objective of this project is to develop a model to predict the **median house value** based on various input features such as:
- Average income
- House age
- Total rooms
- Total bedrooms
- Population
- and more...

### Technologies Used:
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

### The Machine Learning Approach:
- **Linear Regression** model is used for prediction.
- Data preprocessing steps include:
  - Handling missing values
  - Outlier detection and removal using Z-scores
  - Feature scaling using `StandardScaler`
  - Data splitting into training and testing sets

## Installation

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

       https://github.com/SRAVAN-DSAI/california-housing-price-prediction.git
   
2. Navigate to the project directory:
   
       cd california-housing-price-prediction
   
3.Install the required dependencies:

      pip install numpy pandas matplotlib seaborn scikit-learn

Usage
Once everything is set up, you can run the project by executing the Python script(s). Here’s an example:

Run the california_housing_prediction.py script to train the model and predict house prices:

      python california_housing_prediction.py
      
The script will:

Load and preprocess the California Housing dataset.

Remove outliers based on Z-scores.

Split the data into training and testing sets.

Train a Linear Regression model.

Evaluate the model’s performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

Model Evaluation

After training the model, the following metrics are calculated to evaluate the model's performance:

Mean Absolute Error (MAE): The average of the absolute errors between predicted and actual values.

Mean Squared Error (MSE): The average of the squared differences between predicted and actual values.

R² Score: Measures how well the model fits the data (higher values indicate better performance).


      

