# Predicting-Electric-Vehicle-Charging-Loads


This project uses PyTorch to build a neural network model to predict residential electric vehicle (EV) charging loads based on real-world data from apartment buildings in Norway. The goal is to forecast the actual energy consumption (in kilowatt hours) during a charging session, which could be useful for predicting energy costs and planning EV charging infrastructure.

The data can be accessed from this [Link Text]: https://data.mendeley.com/datasets/jbks2rcwyj/1

Note:

The project was a  challenge problem as part of the PyTorch and Neural Networks course on codecademy.

## Input Features:

Plug-in Duration: The total time the vehicle remains plugged in.

Location Type: Whether the charging point is in a private or public setting.

Month: The month in which the charging session takes place.

Day of the Week: The specific day the charging session occurs.

Traffic Density: A measure of the traffic around the location during the session.

### The target variable: 
Charging Load (kWh): The amount of energy consumed during the charging session.

## Objective:

This project aims to accurately predict the energy consumption for EV charging sessions. Such a model can help in optimizing EV infrastructure planning by forecasting energy requirements, which could aid in managing energy costs effectively.

## Model Overview:

Framework: PyTorch
Model Type: Feedforward Neural Network (Regression)
Loss Function: Mean Squared Error (MSE)
Evaluation Metrics: Root Mean Squared Error (RMSE), Mean Absolute Error (MAE)

## Potential Applications:

If the model performs well, it can be applied to:

Predict energy consumption for residential EV charging.
Help in cost estimation for developing charging infrastructure.
Assist in energy grid planning and optimization.

