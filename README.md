
---

## 🔧 Tools & Technologies Used

- **Python** 🐍
- **Pandas**, **NumPy**
- **Matplotlib**
- **scikit-learn** for preprocessing & evaluation
- **TensorFlow/Keras** for building LSTM
- **yfinance** to fetch stock data

---

## 🧠 Model Workflow

1. Fetch historical NIFTY 50 data using `yfinance`
2. Prepare features & targets
3. Scale features using `MinMaxScaler`
4. Split into training and test sets
5. Build and train LSTM model
6. Evaluate using R², RMSE, MAE
7. Visualize predictions vs actual values

---

## 📊 Results (Sample)

| Metric        | Value           |
|---------------|-----------------|
| R² Score      | **0.88**        |
| RMSE          | ₹973,945.56     |
| MAE           | ₹852.17         |

---

## 📉 Plot

> Prediction vs Actual Close Prices

*(See the `nifty-github.png`  chart)*

---

## 🚀 Future Enhancements

- Add more technical indicators (RSI, MACD, Bollinger Bands)
- Hyperparameter tuning for better accuracy
- Use GRU or Transformer models
- Integrate real-time news sentiment analysis

---

## 🙌 Acknowledgements

- [Yahoo Finance](https://finance.yahoo.com/) via `yfinance` API
- TensorFlow & Keras community
- Scikit-learn documentation

---

## 📎 License

This project is licensed under the MIT License - feel free to use and modify.

---

## 👤 Author

**Manish Gahlot**  
_Data Science & Machine Learning Enthusiast_  

