# 📈 Time Series Forecasting — Stock Price Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Models](https://img.shields.io/badge/Models-ARIMA%20%7C%20RNN-green)

## 📌 Project Overview

This project applies and compares two time series forecasting approaches — 
**ARIMA** (statistical) and **RNN** (deep learning) — to predict stock prices 
for two companies:

- 🛒 **Amazon (AMZN)** — high-volatility tech stock
- 💊 **Johnson & Johnson (JJ)** — stable healthcare stock

The goal is to evaluate which model performs better across different 
types of financial time series data.

---

## 🗂️ Repository Structure

| Notebook | Description |
|---|---|
| `AMZN ARIMA.ipynb` | ARIMA model applied to Amazon stock data |
| `AMZN RNN.ipynb` | RNN/LSTM model applied to Amazon stock data |
| `JJ ARIMA.ipynb` | ARIMA model applied to Johnson & Johnson stock data |
| `JJ RNN.ipynb` | RNN/LSTM model applied to Johnson & Johnson stock data |

---

## 🛠️ Tools & Technologies

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Statsmodels, TensorFlow/Keras
- **Models:** ARIMA, Recurrent Neural Network (RNN/LSTM)
- **Environment:** Jupyter Notebook

---

## 🔍 Methodology

### ARIMA (AutoRegressive Integrated Moving Average)
- Classical statistical model for time series
- Steps: Stationarity check (ADF test) → Differencing → ACF/PACF analysis → Model fitting → Forecasting

### RNN / LSTM (Recurrent Neural Network)
- Deep learning model capturing long-term temporal dependencies
- Steps: Data normalisation → Sequence generation → LSTM architecture → Training → Prediction

---

## 📊 Key Findings

- ARIMA performs well on **stable, linear trends** (Johnson & Johnson)
- RNN/LSTM better captures **non-linear, volatile patterns** (Amazon)
- Both models evaluated using **RMSE** and **MAE** metrics

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/ShaziaNasim606/TimeSeriesCaseStudy.git
cd TimeSeriesCaseStudy

# Install dependencies
pip install pandas numpy matplotlib statsmodels tensorflow scikit-learn

# Open notebooks
jupyter notebook
```

---

## 👩‍💻 Author

**Shazia Nasim**  
MSc Data Science | University of Hertfordshire  
📍 Bristol, UK | 📧 nasim.shazia1@gmail.com  
🔗 [GitHub Profile](https://github.com/ShaziaNasim606)
