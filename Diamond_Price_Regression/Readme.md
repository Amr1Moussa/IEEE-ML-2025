Here’s a clean and professional **README.md** file for your Kaggle diamond price prediction project:

---

# 💎 Diamond Price Prediction

This project uses the classic **Diamonds Dataset** from Kaggle to predict diamond prices based on their physical characteristics and quality metrics. It's a great exercise in data preprocessing, feature engineering, regression modeling, and evaluation.

---

## 📦 Dataset Overview

* **Source**: [Kaggle - Diamonds Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds)
* **Rows**: \~54,000
* **Target**: `price` (in USD)

### ✨ Features

| Feature   | Description                                                          |
| --------- | -------------------------------------------------------------------- |
| `carat`   | Weight of the diamond (0.2–5.01)                                     |
| `cut`     | Quality of the cut (`Fair`, `Good`, `Very Good`, `Premium`, `Ideal`) |
| `color`   | Diamond color from J (worst) to D (best)                             |
| `clarity` | Clarity grade: I1 (worst) to IF (best)                               |
| `x`       | Length in mm (0–10.74)                                               |
| `y`       | Width in mm (0–58.9)                                                 |
| `z`       | Depth in mm (0–31.8)                                                 |
| `depth`   | Total depth percentage = 2 \* z / (x + y)                            |
| `table`   | Width of the top of the diamond relative to the widest point         |

---

## 🧹 Data Preprocessing

Steps performed:

* ✅ **Handled skewed numerical features**
* ✅ **Separated target (`price`) and features**
* ✅ **Split dataset into training and test sets**
* ✅ **Encoded categorical features (`cut`, `color`, `clarity`)**
* ✅ **Standardized numerical features for consistent scaling**

---

## 🧠 Modeling & Evaluation

### Models Trained:

* **Linear Regression**
* **Ridge Regression**
* **Lasso Regression**
* **ElasticNet Regression**

### 📊 Evaluation Metrics Used:

* **MSE** (Mean Squared Error)
* **RMSE** (Root Mean Squared Error)
* **R²** (Coefficient of Determination)
* **Adjusted R²**

### 📈 Results:

| Model      | MSE          | RMSE     | R²     | Adjusted R² |
| ---------- | ------------ | -------- | ------ | ----------- |
| Linear     | 681,111.81   | 825.30   | 0.9137 | 0.9135      |
| **Ridge**  | 681,058.15   | 825.26   | 0.9137 | 0.9135      |
| Lasso      | 687,377.42   | 829.08   | 0.9129 | 0.9127      |
| ElasticNet | 1,588,394.24 | 1,260.32 | 0.7986 | 0.7982      |


> 📌 **Note**: Linear Regression performed best overall based on R² and RMSE.


## 🚀 Future Improvements

* Try ensemble models (Random Forest, XGBoost)
* Perform feature selection and importance analysis
* Use polynomial features for potential non-linear relationships

