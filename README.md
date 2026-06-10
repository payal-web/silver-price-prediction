
# 🥈 Silver Price Prediction 

A machine learning project that predicts silver prices using historical data.
Multiple models are compared to find the best-performing approach for 
time-series forecasting.

---

## 📌 Project Overview

- Silver price prediction using supervised ML and time-series forecasting
- Comparison of three different models: Linear Regression, Random Forest, 
  and Facebook Prophet
- Evaluation based on standard regression metrics
- Visualizations to understand trends and model performance

---

## 🧠 Models Used

| Model | Type |
|---|---|
| Linear Regression | Supervised ML (Baseline) |
| Random Forest Regressor | Ensemble ML |
| Facebook Prophet | Time-Series Forecasting |

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:**
  - `pandas` — Data manipulation
  - `numpy` — Numerical computation
  - `scikit-learn` — ML models and metrics
  - `prophet` — Time-series forecasting
  - `matplotlib` / `seaborn` / `plotly` — Visualizations
  - `Google Colab` — Development environment

---

## 📂 Project Structure
silver-price-prediction/
│
├── silver_price_prediction.ipynb   # Main Colab notebook
├── dataset/
│   └── silver_price_data.csv       # Historical silver price data
├── outputs/
│   └── plots/                      # Generated visualizations
└── README.md

---

## 📊 Dataset

- **Source:** Historical silver price dataset (daily/monthly closing prices)
- **Features used:** Date, Open, High, Low, Close, Volume
- **Target variable:** Closing Price

---

## ⚙️ How to Run

1. **Clone the repository**
```bash
   git clone https://github.com/your-username/silver-price-prediction.git
   cd silver-price-prediction
```

2. **Open in Google Colab**
   - Upload the `.ipynb` file to Google Colab, OR
   - Click the Colab badge in the notebook directly

3. **Install dependencies**
```bash
   pip install prophet scikit-learn pandas numpy matplotlib seaborn plotly
```

4. **Run all cells** in order from top to bottom

---

## 📈 Evaluation Metrics

- **MAE** — Mean Absolute Error
- **RMSE** — Root Mean Squared Error
- **R² Score** — Coefficient of Determination

---

## 🔍 Key Findings

- Random Forest outperformed Linear Regression on non-linear price patterns
- Facebook Prophet effectively captured seasonal trends in silver prices
- Feature engineering on date components improved model accuracy

---

