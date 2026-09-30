# Assignment 3: Time-Series Data — Project Summary

**Group 03**  
**Gaurav Kudeshia & Anurodh Singh**

## Overview
This project implemented and evaluated recurrent and sequence-modeling approaches for weather forecasting using the Jena Climate dataset. The dataset contains more than 420,000 observations with 15 weather-related variables.

## Data preparation
The workflow included:
- Parsing the weather dataset into numerical form
- Normalizing variables
- Splitting the data into training, validation and test sets
- Creating sequence-based datasets for forecasting

## Models explored
The project compared:
- Non-machine-learning baseline
- Dense neural network
- 1D convolutional network
- Simple RNN
- Stacked RNN
- GRU
- LSTM
- LSTM with dropout regularization
- Stacked LSTM models with different unit sizes
- Bidirectional LSTM
- Hybrid 1D ConvNet + LSTM

## Main observations
The project found that simple RNNs were limited by their ability to handle long-term dependencies. LSTM- and GRU-based models provided better forecasting behavior, and the project compared their performance using Mean Absolute Error (MAE).

## Selected model results

| Model | Validation MAE | Test MAE | Loss |
|---|---:|---:|---:|
| Common-sense baseline | 2.44 | 2.62 | — |
| Basic ML model | 2.80 | 2.65 | 11.37 |
| 1D convolutional model | 3.26 | 3.21 | 16.51 |
| Simple RNN | 143.54 | 9.92 | 151.28 |
| Stacked RNN | 9.84 | 9.91 | 151.16 |
| GRU | 2.55 | 2.50 | 10.09 |
| LSTM | 2.63 | 2.58 | 11.06 |
| LSTM + dropout | 2.37 | 2.60 | 10.87 |
| Stacked LSTM, 16 units | 2.70 | 2.65 | 11.24 |
| Stacked LSTM, 32 units | 2.68 | 2.63 | 11.16 |
| Stacked LSTM, 8 units | 2.33 | 2.55 | 10.61 |
| Bidirectional LSTM | 2.52 | 2.62 | 11.05 |
| 1D ConvNet + LSTM | 4.03 | 4.05 | 25.48 |

## Takeaway
The project demonstrates practical experience with environmental time-series data, sequence modeling, recurrent neural networks, model comparison, and forecasting evaluation.
