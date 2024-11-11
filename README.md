# Car Price Prediction

Project link: [Car Price Prediction App](https://car-price-predictor-xh7j.onrender.com/)

## Aim

This project aims to predict the price of a used car based on various input parameters such as the car's company name, model name, year of purchase, fuel type and Number of Kilometres that the car has travelled:. It provides users with a reliable estimate of a car's selling price to aid in decision-making.

## Project Overview
First of all the data was scraped from Quikr.com (https://quikr.com) Link for data:https://github.com/Satyabrata-DS/car-price-predictor/blob/master/quikr_car.csv
then cleaned and anlysed the data
After cleaning the data, I performed EDA
I built a **Linear Regression** model to predict car prices based on various features,The model achived **R² score of 0.89**, indicating that it explains 89% of the 
The Flask application was deployed on **Render**, making it accessible via the web
The Car Price Prediction model uses several car attributes, including company, model,year,fuel type,no of kilometer car has travelled The app is useful for both sellers and buyers in determining a fair price for a vehicle.

## How It Works

1. **Data Input**: Users input the car's specifications (e.g., brand, model year, mileage, fuel type, transmission).
2. **Prediction**: The model processes these inputs and predicts the expected price of the car.
3. **Output**: The estimated price is displayed, helping users make informed pricing decisions.

## Requirements

The following libraries are needed to run this project:

- **Flask**: For web development and serving the app.
- **Scikit-Learn**: For the machine learning model.
- **NumPy** and **Pandas**: For data manipulation and preprocessing.
- **Gunicorn**: For running the Flask app in a production environment.
 

