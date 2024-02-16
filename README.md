# AJNIFM
## Price Prediction using Hybridized LSTM-GRU-Catboost Model
This repository contains the implementation of a price prediction system for GeM Procurement Portal data using a hybridized LSTM-GRU-Catboost model.

## Table of Contents
- Introduction
- Requirements
- Installation
- Usage
- Dataset
- Model Architecture
- Evaluation Metrics
- Results
- Contributions
- License

## Introduction
GeM is a government platform for procurement of goods for Indian Government entities.

## Requirements
- Python 3.x
- TensorFlow
- Pandas
- NumPy
- Pytorch

## Installation
Clone this repository: git clone https://github.com/emekss/ethereum-price-prediction.git
Navigate to the project directory
Install the required packages

## Usage
Prepare your GeM price dataset (Xlsx format).
Update the dataset path and hyperparameters in the relevant scripts.
Train the LSTM-GRU-Catboost model
Evaluate the model's performance
Make predictions using the trained model

## Dataset
Training Dataset is GeM19_20.ipynb which is for 2019-2020. Model built with specified architecture is trained on this dataset and tested on Unseen dataset from 2022-2023 dataset.

## Model Architecture
The hybridized LSTM-GRU-Catboost model combines the strengths of both architectures to capture both long-term and short-term dependencies and make regression the values.

## Evaluation Metrics
The model's performance is assessed using common evaluation metrics: R2 Score, Root Mean Squared Error (RMSE), Mean Squared Error (MSE), Mean Absolute Error (MAE), and Explained Variance Score (EVS)

## Results
The LSTM-GRU-Catboost model showed the best real-time prediction capabilities, demonstrating the effectiveness of the hybrid approach. Despite its computational cost, the model's accuracy and performance make it a promising choice for GeM price prediction. Other techniques used are Adversarial attack.

Contributions
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
