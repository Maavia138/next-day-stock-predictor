# 📈 Short-Term Stock Prediction

This project uses machine learning to predict the **next day's closing price** of a selected stock based on historical market data. The data is fetched using the `yfinance` API and processed using Python libraries like `pandas`, `scikit-learn`, and `matplotlib`.

---

## 📌 Objective

To predict short-term stock closing prices using features such as:
- Open
- High
- Low
- Volume

Two models are used:
- **Linear Regression**
- **Random Forest Regressor**

---

## 📦 Libraries Used

- `yfinance` – For fetching historical stock data
- `pandas` – For data cleaning and manipulation
- `numpy` – For numerical operations
- `scikit-learn` – For regression models and evaluation
- `matplotlib` – For visualization

---

## 📊 Models Trained

- **Linear Regression**
- **Random Forest Regressor**

Both models are trained on historical stock data to predict the next day's `Close` price. Performance is evaluated using:
- **R² Score**
- **Mean Squared Error (MSE)**
- **Plot of actual vs predicted values**

---

## 🖼️ Output

- Evaluation metrics printed in the terminal
- Visualization plot comparing actual and predicted prices
- Final predicted closing price for the next day

---

