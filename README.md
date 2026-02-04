# 🏠 Housing Price Prediction using Linear Regression

## 📌 Project Overview

This project focuses on building a **regression-based machine learning model** to predict housing prices using key numerical and categorical features. The objective is not only to predict prices but also to **analyze how different factors influence house pricing**.

The project follows a **complete end-to-end data science workflow**, making it suitable for beginners while still demonstrating strong analytical depth.

---

## 🎯 Objectives

* Understand relationships between housing features and price
* Perform Exploratory Data Analysis (EDA) using visualizations
* Preprocess data for machine learning
* Build and evaluate a Linear Regression model
* Interpret regression metrics and model performance

---

## 🛠️ Technologies & Libraries Used

* **Python**
* **NumPy** – numerical computations
* **Pandas** – data manipulation and analysis
* **Matplotlib & Seaborn** – data visualization
* **Scikit-learn** – model training and evaluation

---

## 📂 Dataset Description

The dataset includes the following features:

* `SquareFeet` – Size of the house
* `Bedrooms` – Number of bedrooms
* `Bathrooms` – Number of bathrooms
* `YearBuilt` – Year the house was constructed
* `Neighborhood` – Categorical location feature
* `Price` – Target variable (house price)

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand data distribution and feature relationships:

* Price distribution analysis using histograms
* Feature vs Price analysis using scatter plots
* Neighborhood-wise price comparison using bar plots

These visualizations helped identify trends such as:

* Larger houses generally having higher prices
* Newer houses being more expensive
* Price variation across neighborhoods

---

## ⚙️ Data Preprocessing

* Checked and confirmed **no missing values**
* Converted categorical variable (`Neighborhood`) using **One-Hot Encoding**
* Split dataset into **features (X)** and **target (y)**
* Performed **Train–Test Split (70% / 30%)**

---

## 🤖 Model Used

### Linear Regression

Linear Regression was chosen as a **baseline regression model** due to its simplicity and interpretability.

```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(x_train, y_train)
```

---

## 📈 Model Evaluation

The model was evaluated using standard regression metrics:

| Metric   | Value         |
| -------- | ------------- |
| MAE      | 39,823        |
| MSE      | 2,485,271,109 |
| RMSE     | 49,852        |
| R² Score | 0.56          |

### Interpretation:

* The **R² score of 0.56** indicates that the model explains approximately **56% of the variance** in housing prices
* This performance makes it a **reliable baseline model** for price prediction

---

## 📊 Visualization

* Actual vs Predicted price scatter plot was used to assess prediction accuracy
* The plot shows a moderate alignment along the diagonal, indicating reasonable predictions

---

## 🧾 Results

The project successfully demonstrates:

* Application of regression techniques on real-world data
* Importance of EDA and preprocessing
* Interpretation of regression metrics
* End-to-end machine learning workflow

---

## 🚀 Future Improvements

* Apply feature scaling
* Try advanced models (Ridge, Lasso, Random Forest)
* Perform cross-validation
* Hyperparameter tuning
* Residual analysis

---

## 📌 How to Run the Project

1. Clone this repository
2. Open the notebook in **Google Colab / Jupyter Notebook**
3. Install required libraries
4. Run cells sequentially

---

## 🔗 Notebook Link

👉 https://colab.research.google.com/drive/1zd63_ugeMu9urPGTn0dDgd5PAA3ELHpE?usp=sharing

---

## 📬 Contact

If you have suggestions or would like to collaborate, feel free to connect!

---

⭐ If you found this project helpful, consider giving it a star!


