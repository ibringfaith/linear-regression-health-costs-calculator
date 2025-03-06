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
Run the script to train the model and make predictions:
```bash
python health_costs.py
```

## Example Usage
After running the script, the model will prompt for user input to predict health costs. Example input:
```
Enter age: 45
Enter BMI: 28.3
Number of children: 2
Smoker? (yes/no): no
Region (north/south/east/west): east
```
Example output:
```
Predicted Health Insurance Cost: $12,450.75
```

## Testing
Run the test script to validate model accuracy:
```bash
pytest test_health_costs.py
```
This ensures that the model is working correctly and meets expected performance benchmarks.

