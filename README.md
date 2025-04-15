# 🚗 Project: Used Car Price Prediction

## 🎯 Project Objective  
The goal of this project is to build a regression model capable of predicting the market value of used cars based on historical and technical data.  
This solution is designed for the fictitious company **Rusty Bargain**, which is developing an app to help users quickly estimate the value of their vehicles.

---

## ✅ Results Achieved  
- Cleaned and prepared a large dataset containing car specs, brand, mileage, fuel type, and more  
- Standardized column names and removed irrelevant or low-variance features  
- Encoded categorical variables using both One-Hot Encoding and Ordinal Encoding strategies  
- Scaled numerical features for better model performance  
- Trained and compared several regression models including:
  - **Linear Regression**
  - **Random Forest Regressor**
  - **CatBoost Regressor**
  - **LightGBM**  
- Tuned hyperparameters using GridSearchCV and RandomizedSearchCV  
- Evaluated models based on RMSE and training/prediction time  
- Achieved a solid balance between **prediction quality and training efficiency**

---

## 🛠️ Tools and Technologies Used  
- **Language:** Python  
- **Main libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, CatBoost, LightGBM  
- **Techniques and resources:**
  - Exploratory Data Analysis (EDA)
  - Feature scaling
  - Categorical encoding (OneHot, Ordinal)
  - Regression modeling
  - Hyperparameter tuning
  - Error analysis using RMSE

---

## 🚀 Skills Developed  
- Implementation of preprocessing pipelines for real-world datasets  
- Comparative analysis of model performance  
- Understanding trade-offs between model accuracy and runtime  
- Experience with regression metrics and interpretation  
- Use of automated search techniques for optimization  

---

## 🔧 Future Improvements  
- Try stacking ensemble models to improve prediction  
- Add additional features like geographic data (ZIP code, region)  
- Deploy the best model as a REST API  
- Build a Streamlit interface to interact with predictions
