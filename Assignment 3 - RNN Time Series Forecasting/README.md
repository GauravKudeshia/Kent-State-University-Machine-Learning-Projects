# Weather Time-Series Forecasting with RNN, GRU and LSTM

**Advanced Machine Learning — Assignment 3**  
**Group:** Gaurav Kudeshia and Anurodh Singh

## Project objective
Develop and compare deep-learning approaches for weather time-series forecasting using the Jena Climate dataset.

## Dataset
- Jena Climate dataset
- 420,451 observations
- 15 recorded variables
- Training, validation and test partitions
- Feature normalization and sequence-based dataset generation

## Models evaluated
- Common-sense forecasting baseline
- Dense neural network
- 1D convolutional network
- Simple RNN
- Stacked RNN
- GRU
- LSTM
- LSTM with dropout
- Stacked LSTM configurations
- Bidirectional LSTM
- 1D ConvNet + LSTM

## Selected results
The project used Mean Absolute Error (MAE) to compare forecasting performance. The simple GRU achieved a test MAE of 2.50, while the stacked LSTM with 8 units achieved validation MAE of 2.33 and test MAE of 2.55. The common-sense baseline had test MAE of 2.62.

## Skills demonstrated
Time-series forecasting, recurrent neural networks, LSTM/GRU architectures, sequence modeling, deep-learning model comparison, TensorFlow/Keras, normalization and MAE-based evaluation.

## Relevance
This project demonstrates experience working with environmental/weather time-series data and comparing deep-learning architectures for forecasting, which is transferable to data-driven natural-hazard and infrastructure-resilience research.

## Source note
This folder documents the original graduate coursework project. The original project files include a Jupyter HTML export, PDF report and summary report.
