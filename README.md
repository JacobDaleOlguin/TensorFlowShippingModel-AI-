# TensorFlowShippingModel-AI-
Please reach out (really, feel free) if you have any questions!

# Shipping Calculator

This project is a Shipping Calculator that provides visualizations and information on anticipated price and availability for certain shipping configurations.

## Features

- Anticipates shipping price and availability of different configurations
- Will provide price outputs for reefer and non reffer as well as different size containers based on inputs such as POL, destination, carrier, etc.
- Provides data visualizations
- Uses machine learning models for prediction

## Installation

To run this project, you need to have Python installed. You can install the required packages using pip:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## Usage (if you really want to refactor everything to fit your data)
- Data Preparation: Load your data into a pandas DataFrame and perform necessary preprocessing.
- Model Training: Split the data into training and testing sets, then train the models using the RandomForestRegressor for price prediction and RandomForestClassifier for availability prediction.
- Visualization: Use matplotlib and seaborn for data visualization to understand the trends and insights from the data.
- Prediction: Use the trained models to make predictions on new shipping configurations.
