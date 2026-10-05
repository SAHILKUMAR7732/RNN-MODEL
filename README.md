# RNN-MODEL

**Time-Series Forecasting Using Vanilla RNN, LSTM, and GRU: A Comparative Deep Learning Project**

## Overview

This project implements and compares three types of Recurrent Neural Networks for time-series forecasting of household electric power consumption:

- **Vanilla RNN (Simple RNN)**
- **Long Short-Term Memory (LSTM)**
- **Gated Recurrent Unit (GRU)**

## Dataset

- Source: [UCI Machine Learning Repository - Individual Household Electric Power Consumption](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)
- Data is resampled to hourly averages for modeling.

## Features

- Data loading and preprocessing (handling missing values, datetime indexing)
- Exploratory Data Analysis (EDA)
- Sequence preparation for RNN models
- Training and evaluation of SimpleRNN, LSTM, and GRU models
- Performance comparison using RMSE and MAE
- Interactive Gradio GUI for making predictions

## How to Run

1. Open `RNN_Model.ipynb` in Google Colab or Jupyter.
2. Install required packages (pandas, numpy, tensorflow, scikit-learn, gradio, etc.).
3. Run the cells sequentially.
4. The final cells launch a Gradio interface for interactive forecasting.

## Requirements

- TensorFlow / Keras
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- gradio
- joblib

## Author

Sahil Kumar
