# customer-churn-prediction
Machine Learning model to predict customer churn
# 🧠 Customer Churn Prediction

This project focuses on building a machine learning model to predict whether a customer will churn based on various behavioral and demographic features.

---

## 📊 Dataset Features

- **Tenure**: Customer relationship duration  
- **WarehouseToHome**: Distance from warehouse to home  
- **NumberOfDeviceRegistered**  
- **PreferedOrderCat**: Preferred order category (e.g., Laptop, Mobile, etc.)  
- **SatisfactionScore**: Customer satisfaction score  
- **MaritalStatus**  
- **NumberOfAddress**: Number of addresses associated with the customer  
- **Complain**: Whether the customer filed a complaint  
- **DaySinceLastOrder**  
- **CashbackAmount**  
- **Churn**: Target variable (1 = Churned, 0 = Retained)

---

## 🛠️ Project Workflow

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
   - Univariate and Bivariate plots
   - Correlation heatmap
3. **Data Preprocessing**
   - Label Encoding
   - Feature Scaling
4. **Model Building**
   - Logistic Regression
   - Random Forest
   - XGBoost
5. **Model Evaluation**
   - Classification Report
   - Confusion Matrix
   - ROC Curve
   - Feature Importance
6. **Conclusion**

---

## 🚀 Results

- **Best Performing Model**: Random Forest
- **Evaluation Metrics**:
  - Accuracy: ~`XX%`
  - AUC Score: ~`XX`

---

## 📌 Key Insights

- Customers with lower satisfaction scores and higher complaint rates were more likely to churn.
- Cashback amount and tenure also played a significant role.

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Folder Structure

