# AJNIFM
## Delivery time Prediction using Hybridized LSTM-GRU-Catboost Model
This repository contains the implementation of a hybridized LSTM-GRU-Catboost model for predicting time taken to deliver for goods procured through GeM Procurement Portal.

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
GeM Procurement portal is a Indian government platform for procurement of goods and services which is used by Indian Government entities.

## Requirements
- Python 3.x
- TensorFlow
- Pandas
- NumPy
- Pytorch

## Installation
+ Clone this repository: git clone https://github.com/Surajbhos/AJNIFM.git or Download Zip 
+ Navigate to the project directory
+ Install the required packages

## Usage
+ Prepare your GeM price dataset (Xlsx format).
+ Update the dataset path and hyperparameters in the relevant scripts.
+ Train the LSTM-GRU-Catboost model
+ Evaluate the model's performance
+ Make predictions using the trained model

## Dataset
Training Dataset is BID_RA_19_20.xlsx which is for 2019-2020. Model built with specified architecture is trained on this dataset and tested on Unseen dataset from 2022-2023 dataset (BID_RA_22_23.xlsx).

## Model Architecture
The hybridized LSTM-GRU-Catboost model combines the strengths of both architectures to capture both long-term and short-term dependencies and make regression the values.
![LSTMgru](https://github.com/Surajbhos/AJNIFM/assets/44914762/719ac7f1-8d01-444a-8c2f-76bd84b0f3d8)


## Evaluation Metrics
The model's performance is assessed using common evaluation metrics: Root Mean Squared Error (RMSE), Mean Squared Error (MSE).

## Results
The LSTM-GRU-Catboost model showed the best real-time prediction capabilities, demonstrating the effectiveness of the hybrid approach. Despite its computational cost, the model's accuracy and performance make it a promising choice for delivery time prediction.

## Contributions
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
