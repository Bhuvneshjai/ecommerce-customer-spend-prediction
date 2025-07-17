# Ecommerce Customer Spend Prediction 🛒📈

This project applies **Linear Regression** to predict customer **yearly spending** based on ecommerce behavioral data such as session time, time on app, and membership status.

## 📌 Project Overview

The goal is to help the business understand which factors influence customer spending the most, and to build a simple machine learning model that can predict **Yearly Amount Spent**.

Dataset: `Ecommerce Customers.csv`

---

## 📂 Contents

- `Linear Regression Project.ipynb` — Jupyter notebook with data analysis and model
- `Ecommerce Customers.csv` — Dataset used in the project
- `README.md` — Project documentation

---

## 📊 Dataset Description

The dataset includes the following features:

| Feature               | Description                                |
|------------------------|--------------------------------------------|
| Email                  | Customer's email ID                        |
| Address                | Physical address                           |
| Avatar                 | Profile picture                            |
| Avg. Session Length    | Average time spent per session             |
| Time on App            | Time spent on mobile app                   |
| Time on Website        | Time spent on website                      |
| Length of Membership   | Years of membership with the company       |
| Yearly Amount Spent    | Target variable — how much they spend/year |

---

## 🛠️ Tools & Technologies

- Python 🐍
- Pandas
- NumPy
- Matplotlib & Seaborn (visualization)
- Scikit-learn (Linear Regression)

---

## 🔍 Key Steps

1. **Exploratory Data Analysis (EDA)**
2. **Data Visualization**
3. **Feature Selection**
4. **Model Training**
5. **Model Evaluation (MSE, RMSE, R² Score)**
6. **Business Recommendations**

---

## ✅ Results

The model successfully predicts customer spending with good accuracy. The most influential feature was found to be **Length of Membership**, indicating strong customer loyalty impacts revenue.

## 🤝 Contributions

If you have suggestions to improve the model or enhance visualizations, feel free to contribute!
