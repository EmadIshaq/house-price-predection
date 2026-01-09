# House Price Prediction 🏠

A simple Machine Learning project that predicts house prices based on **Area** and **Number of Rooms** using the **Random Forest Regressor** algorithm.

## 📋 Project Overview
This project demonstrates the fundamental steps of a supervised learning regression task. It takes physical attributes of a house as input and outputs an estimated market price.

## 🚀 How it Works
The project follows these four main steps:
1. **Data Preparation**: Creating a structured dataset using Pandas.
2. **Data Splitting**: Dividing the data into training (80%) and testing (20%) sets.
3. **Model Training**: Using `RandomForestRegressor` to learn patterns between area, rooms, and price.
4. **Evaluation**: Measuring accuracy using **Mean Absolute Error (MAE)**.

## 🛠️ Technologies Used
* **Python**
* **Pandas** (Data Manipulation)
* **Scikit-Learn** (Machine Learning Library)

## 📊 Dataset Example
The model trained on features like:
| Area (sqm) | Rooms | Price (Thousands) |
|------------|-------|-------------------|
| 100        | 2     | 1100              |
| 150        | 3     | 1600              |
| 200        | 4     | 2100              |

## 📉 Results
The performance is evaluated using **Mean Absolute Error (MAE)**, which indicates how much the predicted price deviates from the actual price on average.

## 📝 How to Run
1. Clone this repository.
2. Ensure you have `scikit-learn` and `pandas` installed.
3. Run the Python script to see the predictions.
