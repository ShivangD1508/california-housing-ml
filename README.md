# 🏠 California Housing Price Prediction - ML Project

This project uses the California Housing dataset to predict median house prices using Machine Learning models including Linear Regression and Random Forest. It includes data preprocessing, feature exploration, model training, evaluation, and visualization.

---

## 📚 Table of Contents
- [📦 Dataset](#-dataset)
- [🧠 Models Used](#-models-used)
- [🔍 Key Insights](#-key-insights)
- [📈 Evaluation Metrics](#-evaluation-metrics)
- [⚙️ Installation & Usage](#️-installation--usage)
- [👤 Author](#-author)

---

## 📦 Dataset
- **Source**: Scikit-learn's California Housing Dataset  
- **Target**: Median house value (capped at $500,000)

---

## 🧠 Models Used
- Linear Regression (baseline)
- Ridge & Lasso (regularized linear models)
- Random Forest Regressor (final model)

---

## 🔍 Key Insights

- **Median Income (`MedInc`)** is the most important predictor — strong positive correlation and over 50% feature importance in Random Forest.
- **Linear Regression underperforms** on high-end houses due to the target value being capped at 5.0.
- **Random Forest performs best**, handling non-linearity and outliers more effectively.
- **Geographic features (`Latitude`, `Longitude`)** matter — regional differences significantly affect house prices.
- **Average Occupancy (`AveOccup`)** affects value — higher occupancy correlates with lower housing prices.
- **Rooms and Bedrooms** aren't very useful — they have low correlation and limited feature importance.
- **Visualizations** helped identify model flaws and confirmed prediction variance and bias.

---

## 📈 Evaluation Metrics (Random Forest)

- **R² Score**: ~0.80 (varies slightly depending on split)
- **RMSE**: Significantly lower than baseline Linear Regression

---

## ⚙️ Installation & Usage

1. **Clone the repo**
   ```bash
   git clone https://github.com/ShivangD1508/california-housing-ml.git
   cd california-housing-ml


