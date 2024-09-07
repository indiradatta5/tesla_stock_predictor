# Tesla Stock Price Forecasting with Facebook Prophet

This project demonstrates how to build a Facebook Prophet machine learning model to forecast the price of Tesla (TSLA) for 30 days into the future. We visualize the historical performance of Tesla using Plotly Express and evaluate the model's performance against real data using Google Finance in Google Sheets. The project also includes a brief stock analysis of Tesla, discussing key financial metrics.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Usage](#usage)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Google Sheets Performance Evaluation](#google-sheets-performance-evaluation)

## Introduction

This project uses a Facebook Prophet model to forecast the stock price of Tesla (TSLA) for the next 30 days. We visualize the historical performance of Tesla, train the model, and evaluate its performance. Additionally, we automate the forecasting process to allow quick predictions for any stock with the necessary visualizations.

## Dataset

The dataset used in this project consists of historical stock price data for Tesla (TSLA). This data can be fetched using an API or by uploading a CSV file.

## Model Architecture

The model is built using the Facebook Prophet library. The architecture involves:
- Training on historical stock price data
- Forecasting the stock price for the next 30 days
- Visualizing the forecast

## Training

The model is trained on historical stock price data. The training process is carried out in a Google Colab environment for faster computation.

## Evaluation

The model's performance is evaluated by comparing the forecasted prices with real data from Google Finance. The evaluation is performed using Google Sheets.

## Results

The results show the forecasted prices for the next 30 days and the model's accuracy. The training and evaluation process provides insights into the model's performance.

## Usage

To run this project, follow these steps:

1. Open the Google Colab notebook:
    - Upload the `Tesla_Forecasting.ipynb` notebook to your Google Drive.
    - Open it in Google Colab.

2. Install required packages:
    Run the following commands in the Colab notebook:
    ```python
    !pip install prophet plotly gspread pandas
    ```

3. Authorize Google Sheets access:
    Follow the instructions in the notebook to authorize access to your Google Sheets.

4. Run all cells in the notebook to execute the code.

## Requirements

- Facebook Prophet
- Plotly Express
- gspread
- pandas

These packages can be installed in the Google Colab environment.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, please contact [Indira Datta](mailto:indiradatta5@gmail.com).

## Google Sheets Performance Evaluation

Use the provided Google Sheets template to evaluate the performance of your forecast against real data from Google Finance. Follow the instructions in the sheet to input your forecasted and actual stock prices.

---

