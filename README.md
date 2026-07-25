# BasketBall-Salary-Prediction
This project provides a web application for predicting basketball player salaries using a linear regression model. The application is built with Streamlit, a popular framework for creating interactive web apps for data science and machine learning.

![Basketball](basketball.jpg)

# Overview
The app allows users to input various features related to basketball players, such as rating, jersey number, team, position, country, draft year, draft round, and draft peak. The application then uses a pre-trained linear regression model to predict the player's salary based on these inputs.

# Features
 - Interactive User Input: Users can adjust sliders to input player characteristics.
 - Real-time Prediction: The app provides an estimated salary prediction based on user inputs.
 - Model Integration: Utilizes a pre-trained linear regression model for salary prediction.

# Project Structure
- app.py: The main Streamlit application script that creates the web interface and handles user input.
- model.sav: The serialized machine learning model (linear regression) used for predictions.
- basketball-salary-prediction.ipynb: It contains the code of the pre-trained linear regression model.
- basketball.jpg : Contains the picture used in the application.