# 🏠 House Price Prediction using Linear Regression

![house-pp](https://github.com/user-attachments/assets/ba44a7e0-e715-4018-9ec7-04b3223b418a)


> Predict house prices using key features like income, number of rooms, population, and house age. Built using Python and scikit-learn.

---

## 📌 Problem Statement

A real estate agent is trying to predict house prices across the U.S. based on various parameters. The dataset contains key indicators like average income, house age, rooms, bedrooms, and population.

---

## 🧠 Key Features

| Feature | Description |
|--------|-------------|
| Avg. Area Income | Average income of area residents |
| Avg. Area House Age | Average age of homes in that area |
| Avg. Area Number of Rooms | Avg. rooms per home |
| Avg. Area Number of Bedrooms | Avg. bedrooms per home |
| Area Population | City population |
| Price | Target: House sale price |

---

## 📊 Exploratory Data Analysis (EDA)

- 🔍 Pairplot to understand relationships
- 🔥 Heatmap to visualize correlation
- 📉 Histogram to analyze distribution of price
- 📌 Insights:
  - Price is most influenced by: Area Income, Number of Rooms, and Population

---

## 🔨 Model Building

- 📦 Used **Linear Regression** from `scikit-learn`
- 🧪 Train-Test Split: 60% training, 40% testing
- 🔁 Training the model using:
  ```python
  LinearRegression().fit(X_train, y_train)
📈 Model Performance
Intercept: -2,640,159

Coefficients:

Feature	Coefficient
Avg. Area Income	21.53
Avg. Area House Age	164,883
Avg. Area Number of Rooms	122,369
Avg. Area Number of Bedrooms	2,234
Area Population	15.15

R² Score: 0.92

MAE: ~82,288

MSE: ~10.46B

RMSE: ~102,279

📉 Visualizations
📌 Scatter Plot: Predictions vs Actuals (aligned pattern = good fit)

📊 Residual Plot: Bell-shaped curve = errors are normally distributed


🧑‍💻 Author:
Vijay kalyan ❤️
