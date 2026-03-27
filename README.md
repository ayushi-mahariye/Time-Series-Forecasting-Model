# 📈 Time Series Forecasting

> A comprehensive, hands-on Jupyter notebook series covering time series analysis and forecasting — from exploratory data analysis to deep learning models including LSTMs, CNNs, MLPs, and Facebook Prophet.

---

## 📌 Overview

This repository is a **structured learning path for time series forecasting**, progressing from foundational EDA and visualization through traditional statistical methods to modern deep learning approaches. Each notebook is self-contained and progressively builds on the previous one.

---

## 🗂️ Notebooks

| # | Notebook | Description |
|---|---|---|
| 1 | `Time_Series_Data_EDA.ipynb` | Exploratory Data Analysis — trends, seasonality, stationarity, autocorrelation |
| 2 | `Time_Series_Data_Visualization_Basics.ipynb` | Plotting time series — line charts, rolling averages, decomposition plots |
| 3 | `Time_Series_Forecasting_Traditional_Methods.ipynb` | ARIMA, SARIMA, Exponential Smoothing — classical statistical forecasting |
| 4 | `Time_Series_Forecasting_With_MLPs.ipynb` | Multi-Layer Perceptrons for sequence forecasting |
| 5 | `Time_Series_Forecasting_With_CNNs.ipynb` | 1D Convolutional Neural Networks for temporal pattern extraction |
| 6 | `Time_Series_Forecasting_With_LSTMs.ipynb` | Long Short-Term Memory networks for sequential dependency learning |
| 7 | `Time_Series_Forecasting_With_Prophet.ipynb` | Facebook Prophet for trend + seasonality + holiday forecasting |

---

## 🧭 Learning Path

```
📊 EDA
  └─► 📉 Visualization Basics
          └─► 📐 Traditional Methods (ARIMA / SARIMA)
                  └─► 🧱 MLPs
                          └─► 🌊 CNNs
                                  └─► 🔁 LSTMs
                                          └─► 🔮 Prophet
```

Start at the top and work your way down — each step introduces new complexity while building on prior concepts.

---

## ✨ What You'll Learn

- 🔍 **EDA** — Identify trends, seasonality, noise, stationarity, and autocorrelation in time series data
- 📉 **Visualization** — Plot rolling statistics, seasonal decomposition, lag plots, and ACF/PACF
- 📐 **Traditional Methods** — Build and tune ARIMA, SARIMA, and Exponential Smoothing models
- 🧱 **MLPs** — Frame time series as supervised learning; train feedforward networks on lag features
- 🌊 **CNNs** — Use 1D convolutions to extract local temporal patterns and features
- 🔁 **LSTMs** — Model long-range sequential dependencies with recurrent neural networks
- 🔮 **Prophet** — Decompose and forecast time series with trend, seasonality, and holiday effects

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ayushi-mahariye/Time-Series-Forecasting.git
   cd Time-Series-Forecasting
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   Or install key packages directly:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn statsmodels tensorflow keras prophet jupyter
   ```

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

4. **Open any notebook** and run cells sequentially

---

## 🛠️ Tech Stack

| Category | Libraries |
|---|---|
| Data Manipulation | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn`, `plotly` |
| Statistical Models | `statsmodels` (ARIMA, SARIMA, Exponential Smoothing) |
| Machine Learning | `scikit-learn` |
| Deep Learning | `tensorflow`, `keras` |
| Prophet Forecasting | `prophet` (by Meta) |
| Notebooks | `jupyter` |

---

## 📊 Models Covered

### 📐 Traditional Methods
- **ARIMA** — AutoRegressive Integrated Moving Average
- **SARIMA** — Seasonal ARIMA with seasonal differencing
- **Exponential Smoothing** — Holt-Winters method for trend + seasonality

### 🤖 Deep Learning
- **MLP** — Lag-feature regression with fully connected layers
- **CNN** — 1D convolutions for local pattern detection
- **LSTM** — Recurrent network for long-term sequence memory

### 🔮 Facebook Prophet
- Additive model with trend, weekly/yearly seasonality
- Holiday effects and changepoint detection
- Uncertainty interval forecasting

---

## 📁 Recommended Dataset Sources

- [Kaggle Time Series Datasets](https://www.kaggle.com/datasets?search=time+series)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/)
- [Yahoo Finance](https://finance.yahoo.com/) via `yfinance`

---

## 🤝 Contributing

Contributions are welcome! Ideas for new notebooks:
- Transformer-based forecasting (Temporal Fusion Transformer)
- N-BEATS / N-HiTS models
- Multivariate time series forecasting
- Real-time streaming forecasts

1. Fork the repo
2. Create a branch: `git checkout -b feature/add-transformer-notebook`
3. Commit: `git commit -m "Add Transformer forecasting notebook"`
4. Push & open a Pull Request

---

## 📄 License

This project is open-source. See [LICENSE](LICENSE) for details.

---

## 👩‍💻 Author

**Ayushi Mahariye** — [@ayushi-mahariye](https://github.com/ayushi-mahariye)

---

> ⭐ Star this repo if it helped you learn time series forecasting!
