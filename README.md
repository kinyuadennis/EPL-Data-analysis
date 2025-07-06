# EPL-Data-analysis
i have premier league table for the previous season 2024/2025. i am using machine learning to interact with the data to do some research
# 🧠 Premier League Match Analytics with Machine Learning

This project explores predictive modeling and time-series analysis using historical Premier League data from the 2024/2025 season. It applies **Random Forests**, **XGBoost**, and **LSTMs** to uncover trends and make match-related predictions such as team performance classification, match outcomes, and sequence forecasting.

## ⚽ Project Goals

- Identify **attacking** and **defensive** team strength based on goals, losses, and draws.
- Use **Random Forests** and **XGBoost** to predict match outcomes and final season points.
- Implement **LSTMs** to model team form trends over the season (time-series prediction).
- Evaluate and visualize model performance using SHAP values and metrics like accuracy and RMSE.

---

## 🔍 What This Project Covers

### ✔ Data Analysis & Feature Engineering
- Team-level metrics: Goals For (GF), Goals Against (GA), Win/Draw/Loss rates, Goal Differences
- Derived statistics: Attack/Defense Score per game
- Feature normalization and ranking
- Optional: Integration of `xG`, injuries, and home/away flags (future extension)

### ✔ ML Models Used
| Model        | Purpose                                      |
|--------------|----------------------------------------------|
| Random Forest | Match result classification, team profiling |
| XGBoost       | Final league position regression             |
| LSTM          | Time-series forecasting of team form         |

### ✔ Visualizations
- Attack vs Defense scatter plots
- Time-series graphs of team performance
- SHAP visualizations for model interpretability

---

## 📁 Project Structure

