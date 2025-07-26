# 📈 Google Stock Price Prediction

A machine learning project focused on predicting Google stock prices using various regression techniques. The analysis compares the performance of different models on real historical stock data.

---


## 🎯 Objective
To predict Google's stock closing prices using regression models. This helps understand the relationship between stock features and closing price, and evaluate how well different algorithms generalize.

---

## 📚 Dataset
- **Source**: Yahoo Finance
- **Target Variable**: Closing Price (`Close`)
- **Features Used**:
  - `Open`, `High`, `Low`, `Volume`, etc.
  - Additional engineered features (if any) using `PolynomialFeatures` or transformations.

---

## 🛠️ Tools & Libraries
- Python, Jupyter Notebook
- `pandas`, `numpy`, `matplotlib`
- `scikit-learn`: for preprocessing, modeling, and evaluation

---

## ⚙️ Models Implemented
- Linear Regression
- Ridge Regression (`alpha=0.1`, `0.5`, `1`)
- Lasso Regression
- ElasticNet Regression
- Polynomial Regression (using `PolynomialFeatures`)
- Stochastic Gradient Descent (SGDRegressor)

---

## 🧹 Data Preprocessing
- **Scaling**: StandardScaler used to normalize features.
- **Splitting**: Data split into training and testing sets.
- **Polynomial Expansion**: For capturing non-linear patterns.
- **Dimensionality Reduction**: Optionally used `TruncatedSVD`.

---

## 📊 Evaluation Metrics
Each model is evaluated using:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score (Coefficient of Determination)

---

## 🏆 Best Model
> The Ridge Regression model with appropriate regularization showed a balance between low error and high R² on test data.

---

## 📈 Visualizations
- Line plots for **actual vs. predicted stock prices**
- Bar plots for comparing model performances across metrics

---

## 🔍 Key Takeaways
- Regularization (Ridge/Lasso) helps prevent overfitting.
- Feature scaling is critical for gradient-based models.
- Polynomial features can improve accuracy but risk overfitting if not regularized.

---

## 📂 Project Structure

