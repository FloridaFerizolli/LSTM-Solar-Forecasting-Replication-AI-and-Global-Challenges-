# LSTM-Solar-Forecasting-Replication-AI-and-Global-Challenges-

This repository contains the code and data for my project in the AI for Global Challenges module at the University of Birmingham. I replicated the study by Qing and Niu (2018), titled "Hourly day-ahead solar irradiance prediction using weather forecasts by LSTM", reproducing its LSTM-based forecasting method using the provided NREL dataset.

## About the Study

The original paper developed an LSTM deep learning model to forecast hourly solar irradiance one day in advance using multivariate weather features. My replication follows the same approach, maintaining the architecture and RMSE scaling method from the study to ensure consistency with the original results.

Minor adjustments were made to improve code clarity, variable naming, and cross-platform compatibility, while keeping the methodology faithful to the original research.

## Project Summary

- **Environment**: Jupyter Notebook (local machine)
- **Language**: Python
- **Libraries**: NumPy, Keras (TensorFlow backend), matplotlib, scikit-learn
- **Data**: Publicly available weather and irradiance datasets from NREL
- **Model**: CNN-LSTM (50 units, trained for 100 epochs)
- **Evaluation Metric**: Root Mean Squared Error (RMSE)
- **Result**: Test RMSE = 77.265 (scaled as in the original paper)

Training and validation loss decreased steadily, and the model’s predictions closely matched the actual observed values.

## Files Included

- `solar_irradiance_lstm_rep.ipynb` – Final Jupyter Notebook with code and output
- `train_solar_data.csv` – Training dataset
- `validate_solar_data.csv` – Validation dataset
- `test_solar_data.csv` – Test dataset
- `README.md` – This file

## How to Run

1. Download this repository.
2. Open `solar_irradiance_lstm_rep.ipynb` in Jupyter Notebook or Google Colab.
3. Ensure the three CSV data files are located in the same directory.
4. Run all cells from top to bottom.

## Ethical and Societal Context

I developed this project using free, open-source tools to make deep learning for solar energy forecasting more accessible. The NumPy-based pipeline ensures the replication can be run on most systems with minimal setup. I used the same input features and solar irradiance targets as in the original Qing & Niu (2018) study, enabling a faithful reproduction of their results. I also emphasise the importance of model transparency and reproducibility.

## Reference

Qing, X. and Niu, Y., 2018. *Hourly day-ahead solar irradiance prediction using weather forecasts by LSTM*. Energy, 148, pp.461–468. https://doi.org/10.1016/j.energy.2018.01.177

## Authors

- Florida Ferizolli
