# 🧾 Labor Earnings Prediction (1978)

This project focuses on predicting **labor earnings in 1978** using demographic and socio-economic data from **1974** and **1975**. The model helps explore how factors like education, age, and past earnings impact future income.

---

## 🎯 Objective

To build a regression model that predicts an individual's earnings in 1978 using historical data (1974–75), including age, education level, degree status, and prior earnings.

---

## 📁 Dataset Overview

The dataset includes the following features:

- `Age` — Age of the individual
- `Education` — Years of education completed
- `Nodeg` — 1 if the individual has no degree, 0 otherwise
- `Earnings_1974` — Income in 1974
- `Earnings_1975` — Income in 1975
- `Earnings_1978` — **Target variable** (income in 1978)


---

## 🧰 Technologies Used

- **Python**
- **Pandas** & **NumPy** – Data cleaning and preparation
- **Matplotlib** & **Seaborn** – Visualization
- **Scikit-learn** – Linear Regression model

---

## 📊 Model Used

### 🔹 Linear Regression

A basic supervised learning model that assumes a linear relationship between the independent variables and the target variable (earnings in 1978).
