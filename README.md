# Housing_cali
# 🏠 House Price Prediction Web App

This is a Flask-based web application that predicts California housing prices using a pre-trained `RandomForestRegressor` model. Users can input housing-related features to get an estimated price and affordability category.

## 🚀 Features

- Simple and intuitive web interface
- Predicts house prices based on:
  - Median income
  - House age
  - Average rooms
  - Average bedrooms
  - Population
  - Average occupants
- Classifies houses into **Affordable**, **Mid-range**, or **Expensive**
- Clean styling with HTML/CSS

## 🧠 Model

The app uses a pre-trained `RandomForestRegressor` model, serialized using `pickle`. Make sure the `random_forest_model.pkl` file is in the project directory.
