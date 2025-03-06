# Linear Regression Health Costs Calculator

## Overview
This project implements a **Linear Regression Health Costs Calculator**, which predicts individual medical costs based on various health-related factors. The model is trained using a dataset containing information such as age, BMI, number of children, smoking status, and region. To pass the challenge, `model.evaluate` must return a Mean Absolute Error of under 3500. This means it predicts health care costs correctly within $3500.

## Features
- **Linear Regression Model**: Uses Scikit-learn to train and evaluate a linear regression model.
- **Data Preprocessing**: Handles categorical and numerical variables efficiently.
- **Prediction Functionality**: Allows users to input new data and receive cost predictions.
- **Performance Evaluation**: Provides metrics such as R-squared and Mean Absolute Error (MAE) to assess model accuracy.
- **Visualization**: Displays data distributions and model predictions using Matplotlib and Seaborn.

## Installation & Setup
### Prerequisites
Ensure you have **Python 3.7+** installed along with the required dependencies.

### Clone the Repository
```bash
git clone https://github.com/ibringfaith/linear-regression-health-costs-calculator.git
cd linear-regression-health-costs-calculator
```

### Install Dependencies
Using `pip`, install the necessary libraries:
```bash
pip install -r requirements.txt
```

## Running the Project
Open the Jupyter Notebook and execute the cells:
```bash
jupyter notebook fcc_predict_health_costs_with_regression.ipynb
```

## Example Usage
The notebook includes step-by-step execution for training the model and making predictions. Modify the input values in the provided cells to predict health costs.

## Testing
Since this project is implemented in a Jupyter Notebook, testing can be done by running all the cells and verifying the outputs. 



