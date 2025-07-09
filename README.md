# 🏠 House Price Prediction

This project demonstrates how to predict house prices in California using multiple regression models with the [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html). We use models like Linear Regression, Decision Tree Regressor, and Ridge Regression to compare performance and evaluate accuracy.

---
## 📦 Tech Stack

- Python 3.10+
- `pandas`, `numpy`
- `scikit-learn` for ML modeling
- `matplotlib` for visualization

---
## 📊 Dataset Overview

The California Housing Dataset contains features such as:

| Feature       | Description                                       |
|---------------|---------------------------------------------------|
| `MedInc`      | Median income in the block group                  |
| `HouseAge`    | Median house age in the area                      |
| `AveRooms`    | Average rooms per household                       |
| `AveBedrms`   | Average bedrooms per household                    |
| `Population`  | Block group population                            |
| `AveOccup`    | Average household occupancy                       |
| `Latitude`    | Geographical latitude                             |
| `Longitude`   | Geographical longitude                            |
| `MedHouseVal` | **Target**: Median house value (in $100,000s)     |

---
## 🧪 ML Models Used

### 1️ Linear Regression
- Baseline model
- Fast and interpretable

### 2️ Decision Tree Regressor
- Captures non-linear patterns
- Tuned with `GridSearchCV`

### 3️ Ridge Regression
- Regularized Linear Regression
- Cross-validated with `RidgeCV`

  ---
  ## 📈 Evaluation Metrics

| Metric | Description |
|--------|-------------|
| MAE    | Mean Absolute Error |

---
## 📊 Visualizations

- 🔹 **Predicted vs Actual** scatter plots
- 🔹 **Residual plots** to detect over/under-fitting
  ![image](https://github.com/user-attachments/assets/8939367f-5afb-4acd-836e-b72f24f5ecb2)
  ![image](https://github.com/user-attachments/assets/dcc9e5b6-abb2-4ca9-b1bf-fe7d04ff5818)
  ![image](https://github.com/user-attachments/assets/bd72f510-76a6-466d-81b6-c37c916b3c50)
