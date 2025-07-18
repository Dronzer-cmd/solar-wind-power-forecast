# 🌞🌬️ Solar and Wind Power Forecasting using Machine Learning

This project analyzes and forecasts daily electricity production from solar and wind energy sources using machine learning algorithms. The data is sourced from the French grid and visualized in a Jupyter Notebook.

---

## 📊 Dataset

- **Source**: [Kaggle - Wind & Solar Electricity Production](https://www.kaggle.com/datasets/henriupton/wind-solar-electricity-production)
- **Type**: Time-series data (hourly measurements)
- **Fields**:
  - `Date and Hour`
  - `Source` (Solar/Wind)
  - `Production` (in MW)
  - Temporal columns (created): day name, month, season, etc.

---

## 🎯 Objectives

- Aggregate hourly data into daily production
- Explore seasonal & temporal patterns
- Train predictive models for daily production
- Compare model performance
- Visualize actual vs predicted results

---

## 🧠 Machine Learning Algorithms Used

| Algorithm               | Purpose                                        |
|-------------------------|------------------------------------------------|
| Linear Regression       | Baseline prediction model                      |
| Random Forest Regressor | Capture non-linear relationships & seasonality|

---

## 🛠️ Tech Stack

- Python (Jupyter Notebook)
- Libraries:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn` (ML models)
  - `datetime`, `os`, `warnings`

---

## 📈 Sample Visualizations

| Actual vs Predicted | Feature Importance | Seasonal Trend |
|---------------------|--------------------|----------------|
| ![graph1](images/pred_vs_actual.png) | ![graph2](images/feature_importance.png) | ![graph3](images/seasonal_trend.png) |

> *(Note: Replace these with your actual image paths)*

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/solar-wind-power-forecast.git
   cd solar-wind-power-forecast
