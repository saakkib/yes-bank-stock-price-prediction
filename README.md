# yes-bank-stock-price-prediction
Machine Learning project for YES BANK stock price prediction
# YES BANK Stock Price Prediction using Machine Learning

## Project Overview
This project focuses on predicting YES BANK stock closing prices using Machine Learning algorithms. Historical stock market data was analyzed and multiple regression models were implemented to forecast future stock prices with improved accuracy.

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Selection
- Machine Learning Model Building
- Hyperparameter Tuning
- Model Evaluation
- Model Saving for Deployment

---

# Dataset Information

The dataset contains historical stock market data of YES BANK including:
- Date
- Open Price
- High Price
- Low Price
- Close Price

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

# Machine Learning Models Used

1. Linear Regression / Ridge Regression
2. Decision Tree Regressor
3. Random Forest Regressor

---

# Feature Engineering

New features created:
- Price_Range
- Average_Price
- Daily_Return
- Year
- Month

---

# Hyperparameter Optimization

GridSearchCV was used for:
- Cross Validation
- Hyperparameter Tuning
- Model Optimization

---

# Evaluation Metrics

The models were evaluated using:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R2 Score

---

# Best Performing Model

✅ Random Forest Regressor achieved the best prediction performance.

---

# Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Feature Selection
6. Model Training
7. Hyperparameter Tuning
8. Model Evaluation
9. Model Saving
10. Prediction on Unseen Data

---

# Project Structure

```bash
yes-bank-stock-price-prediction/
│
├── yes_bank_stock_prediction.ipynb
├── best_random_forest_model.pkl
├── dataset.csv
├── requirements.txt
└── README.md
```

---

# Model Saving

The best-performing model was saved using Joblib for deployment and future predictions.

```python
import joblib

joblib.dump(best_rf_model, 'best_random_forest_model.pkl')
```

---

# Future Improvements

- Deep Learning Models (LSTM)
- Real-time Stock Prediction
- Streamlit/Flask Deployment
- Live Stock API Integration

---

# Conclusion

This project successfully demonstrated the use of Machine Learning techniques for stock market prediction. Random Forest Regressor provided the best results with high prediction accuracy and strong generalization capability.

---

# Author

Sakib patel
