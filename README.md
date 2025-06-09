# Railway Punctuality Analysis Using Regression

## 📌 Overview

This project analyses UK rail performance data to understand what factors influence punctuality. The focus is on predicting the Public Performance Measure (PPM) using multiple linear regression. The project simulates a real-world transport operations use case where data analysis can help inform scheduling and performance decisions.

---

## 🎯 Objective

To identify which regional sectors and train operating companies significantly impact the national punctuality metric (PPM), and to build an interpretable regression model that supports transport strategy and operational planning.

---

## 📅 Duration

* **Data Range**: Multiple quarterly performance periods
* **Project Phase**: Completed (2025)

---

## 🧠 Key Tasks

* Loaded and cleaned sector/operator punctuality data
* Encoded categorical variables (e.g., time periods, operators)
* Performed correlation and feature selection
* Built a multiple linear regression model using OLS (Statsmodels)
* Evaluated statistical significance and residual distribution
* Visualised insights: heatmaps, coefficient bars, residuals, and prediction accuracy

---

## 🛠️ Tools & Libraries

* **Python**
* **Pandas, NumPy** – data wrangling and cleaning
* **Statsmodels** – regression modelling
* **Matplotlib & Seaborn** – data visualisation

---

## 📊 Visuals Included

* Correlation Heatmap
* Bar Chart of Coefficients
* Residuals Distribution Plot
* Actual vs Predicted Scatter Plot

---

## 🔍 Key Findings

* Sectors like **London & South East**, **Regional & Scotland**, and **Long Distance** had the highest positive influence on national PPM.
* Some operators (e.g., **Southeastern**) showed significant impact.
* The model achieved a high R², indicating strong explanatory power (though initially overfitted before feature reduction).

---

## 💡 Future Work

* Incorporate additional metrics (e.g., delay minutes, cancellations)
* Apply time-series modelling (ARIMA or Prophet)
* Build a live Power BI dashboard to monitor key operators

---

## 📁 Folder Structure

```
📦 railway-ppm-regression
 ┣ 📊 visuals/                  # Generated charts
 ┣ 📁 data/                     # Raw & cleaned datasets
 ┣ 📄 regression_model.py       # Core model and EDA script
 ┣ 📄 README.md                 # Project overview
```

---

## 👤 Author

Sheriff Lawal
🔗 [LinkedIn](https://www.linkedin.com/in/sheriff-lawal-b22722103/)
📧 [shef3luv4real@gmail.com](mailto:shef3luv4real@gmail.com)

---

> *This project was built as part of my data analytics portfolio to demonstrate practical application of statistical modelling in the transport sector.*
