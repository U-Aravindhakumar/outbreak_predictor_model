# Outbreak Predictor Model

## Overview
The **Outbreak Predictor Model** is a machine learning project that uses environmental and social factors to predict the likelihood of a disease outbreak in a specific region. The model is built using a **Logistic Regression** algorithm, and users can input data such as temperature, population density, and vaccination rate to get a prediction on whether an outbreak is likely to occur.

## Features
- User-friendly input system where users provide real-time data.
- Predicts the likelihood of an outbreak based on input features.
- Model is trained using Logistic Regression and takes into account key features like **temperature**, **population density**, and **vaccination rate**.
  
## Project Structure
- ├── data.
- │   └── disease_outbreak_data.csv  # Dataset containing training data.
- ├── outbreak_predictor_model.py    # Python file for prediction using user input.
- └── README.md                      # Project description and instructions.

## Files
1. `outbreak_predictor_model.py`: The core Python script where users input the data (temperature, population density, and vaccination rate) and receive a prediction on whether a disease outbreak is likely.
   
2. `disease_outbreak_data.csv`: The dataset used to train the model. You can either use the provided CSV file or generate a new one based on similar features.

## Dataset
The **disease_outbreak_data.csv** file contains historical outbreak data and includes the following columns:
- `temperature`: Temperature in the region (°C)
- `population_density`: Population density per square kilometer
- `vaccination_rate`: Vaccination rate in the region (as a percentage)
- `historical_outbreaks`: Binary label indicating whether an outbreak occurred (1 for outbreak, 0 for no outbreak)

### Prerequisites
Ensure that you have Python installed on your machine. You also need the following libraries:
- `scikit-learn`
- `numpy`
- `joblib`

You can install the necessary dependencies by running:
```bash
pip install scikit-learn numpy joblib

