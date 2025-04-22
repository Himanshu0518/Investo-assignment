<!-- Badges -->
<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img alt="License" src="https://img.shields.io/badge/License-MIT-green" />
</p>

## 📈 Stock Price Forecasting

Predict future Apple Inc. (AAPL) closing prices using ARIMA and XGBoost.

---

## 🚀 Quick Start
```bash
# 1. Clone repo
git clone https://github.com/yourusername/ts-forecasting.git
cd ts-forecasting

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run analysis
python stock_price_forecasting.py
🔧 Tech Stack
Data & Models:

📊 yfinance • statsmodels (SARIMAX) • XGBoost

Utilities:

🐼 pandas • 🔢 numpy • 📈 matplotlib

🤖 scikit‑learn (RandomizedSearchCV, metrics)

⚙️ Workflow

Step	Stock Forecasting
1. Fetch Data	yfinance (Close/Volume)
2. Feature Eng.	Lag, MA7, MA30, %Change
3. Modeling	SARIMAX + XGBRegressor
4. Tuning	RandomizedSearchCV
5. Metrics	MAE • RMSE • MAPE
6. Visualize	Actual vs Forecast
📈 Key Results

Model	MAE	RMSE	MAPE
ARIMA (AAPL)	16.18	18.69	10.25%
XGBoost (AAPL)	3.95	6.74	2.29%
Tuned XGBoost	3.54	6.39	1.97%
📜 License
This project is MIT‑licensed. See LICENSE for details.

✨ Happy forecasting! ✨
