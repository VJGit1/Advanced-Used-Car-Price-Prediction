# Advanced-Used-Car-Price-Prediction
Dataset : https://www.kaggle.com/competitions/playground-series-s4e9/data

## Project Objective

To build, tune, and compare multiple regression models to accurately predict used car prices based on features like brand, mileage, year, engine size, fuel type, and more.

---

## Technologies & Tools Used

- Python  
- Scikit-learn  
- XGBoost  
- LightGBM  
- MLPRegressor  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- GridSearchCV & RandomizedSearchCV

---

## Models Implemented

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost  
- LightGBM  
- Multi-layer Perceptron (MLP)

Each model was evaluated using **RMSE, MAE**, and **R² Score**. Hyperparameter tuning was conducted using **GridSearchCV** and **RandomizedSearchCV**.

---

## Results & Insights

- XGBoost outperformed other models with the best balance between bias and variance  
- Feature importance analysis revealed that `mileage`, `engine_size`, and `year` were among the most influential features  
- Insights can be used by dealerships or resale platforms to improve pricing strategies

---

## 💡 Future Work

- Deploy the best-performing model using Streamlit or Flask  
- Apply feature selection techniques like Boruta  
- Test the model on live scraped data or API-connected marketplace data

---
 
