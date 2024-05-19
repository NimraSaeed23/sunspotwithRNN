# Sunspot Activity Prediction using RNN

This repository contains a Jupyter notebook that demonstrates the prediction of sunspot activity using Recurrent Neural Networks (RNN), specifically LSTM (Long Short-Term Memory) units, implemented in TensorFlow and Keras.

## Project Overview

Sunspots are temporary phenomena on the Sun's photosphere that appear as spots darker than the surrounding areas. They are indicators of magnetic activity on the Sun and correlate with solar flares. Predicting sunspot activity can be crucial for understanding solar cycles and potentially predicting space weather impacts on Earth.

## Repository Contents

- `SUNSPOT,RNN.ipynb`: The main Jupyter notebook containing the data preparation, model building, training, and evaluation.

## Data
The data used in this project is sourced from the SILSO data center, detailing monthly sunspot numbers. The data preprocessing involves normalization and transformation into a sequence format suitable for time series forecasting.

## Model
The model uses LSTM layers, which are well-suited for time series data due to their ability to capture long-term dependencies. The network architecture, training process, and evaluation metrics (like RMSE) are detailed in the notebook.
