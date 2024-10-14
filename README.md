# Housing Price Prediction Model

## Overview
This project aims to develop a machine learning model to predict housing prices based on various features such as area, number of bedrooms, bathrooms, and more. The model utilizes data preprocessing techniques, feature engineering, and machine learning algorithms to provide accurate price predictions.

## Dataset
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset). It includes information about housing prices and various attributes that affect those prices.

## Features
- **Price**: The target variable representing the price of the house.
- **Area**: Total area of the house in square feet.
- **Bedrooms**: Number of bedrooms in the house.
- **Bathrooms**: Number of bathrooms in the house.
- **Stories**: Number of stories in the house.
- **Mainroad**: Proximity to the main road (yes/no).
- **Guestroom**: Availability of a guestroom (yes/no).
- **Basement**: Availability of a basement (yes/no).
- **Hotwaterheating**: Availability of hot water heating (yes/no).
- **Airconditioning**: Availability of air conditioning (yes/no).
- **Parking**: Number of parking spaces.
- **Prefarea**: Proximity to preferred area (yes/no).
- **Furnishingstatus**: Furnishing status (furnished/semi-furnished/unfurnished).

## Installation
To set up the project environment, you need to install the required packages. You can do this by running the following command:

```bash
pip install -r requirements.txt
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/doreenasiimwe/housing_price_prediction_model.git
Navigate to the project directory:

bash
Copy code
cd housing-price-prediction-model
Open a Jupyter Notebook or run the Python scripts to start the model training and prediction processes.

Follow the instructions in the Jupyter Notebook for data preprocessing, model training, and evaluation.

Evaluation Metrics
The model is evaluated using the following metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
