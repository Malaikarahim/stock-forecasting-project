📊 Time Series Forecasting of Reliance Stock Prices

This project applies multiple time series forecasting techniques to predict Reliance Industries stock prices using Python. It covers data collection, preprocessing, visualization, and prediction using ARIMA, SARIMA, Prophet, and LSTM models.

> 📁 Colab Notebook: [Open in Colab](https://colab.research.google.com/drive/1OmhhSdFyFq8TAFrwDUVGZKVm-ved-6xF?usp=sharing)

---
 📌 Objective

* Collect stock market data using yfinance
* Visualize and understand trends in Reliance stock
* Forecast future stock prices using four models:

  * ARIMA
  * SARIMA
  * Prophet
  * LSTM
* Evaluate performance using RMSE


🛠️ Technologies Used

* Python 3
* Pandas, NumPy, Matplotlib, Seaborn
* yfinance
* statsmodels (ARIMA, SARIMA)
* prophet (Facebook Prophet)
* TensorFlow + Keras (LSTM)
* scikit-learn

 📁 Folder Structure

stock-forecasting-project/
│
├── stock_forecasting_project.ipynb   # Main Colab notebook
├── stock_data.csv                    # Stock market data
├── README.md                         # This file
├── report.pdf                        # Final report (optional)
└── forecast_results.csv              # Predicted stock prices (optional)



 📊 Results

| Model   | RMSE |
| ------- | ---- |
| ARIMA   | 21.5 |
| SARIMA  | 19.4 |
| Prophet | 22.7 |
| LSTM    | 15.9 |

📌 The LSTM model performed best on RMSE and captured long-term trends more accurately.


📈 Visuals

* Line chart of closing prices (2015–2024)
* Volume vs price scatter plot
* Forecast charts for each model
* Prophet trend and seasonality analysis


 🔮 Future Scope

* Add news sentiment analysis
* Use more features (moving average, RSI)
* Deploy as web dashboard using Streamlit


 📄 License

This project is for educational purposes only.



