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
   ```bash
   git clone https://github.com/your-username/california-housing-price-prediction.git
