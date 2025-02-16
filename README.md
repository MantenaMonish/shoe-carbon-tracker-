# Carbon Footprint Prediction for Shoes

This repository contains the code and documentation for my project on predicting the carbon footprint of different types of shoes based on their features using a RandomForestRegressor model.

## Project Overview

The project aims to predict the carbon footprint (measured in CO2e) of shoes using features such as shoe type, materials used, and recyclability. The dataset used in this project consists of 200 entries with detailed information about each shoe.

## Data Preprocessing

- Handled categorical data using OneHotEncoder.
- Performed feature scaling and transformation.
- Visualized data distribution using histograms and box plots.

## Model Building

- Used RandomForestRegressor for prediction.
- Performed hyperparameter tuning using GridSearchCV to optimize the model.
- Evaluated model performance with Mean Squared Error (MSE) and R-squared score.

## Results

- Achieved an R-squared score of 0.95 and a Mean Squared Error of 0.159.
- Visualized the actual vs predicted carbon footprint values.

## Conclusion

This project demonstrates the application of machine learning techniques to predict environmental impact metrics, providing insights for sustainable product development.
I would like to give special thanks to the authors of "Carbon Footprint of Different Kinds of Footwear – a Comparative Study" for providing the foundation for the dataset used in this project.
Feel free to explore the code and provide any feedback or suggestions.
