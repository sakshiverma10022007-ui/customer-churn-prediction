# customer-churn-prediction
# Customer Churn Prediction

## 📌 Problem Statement
Predict whether a customer will leave the bank (churn) based on their profile and account details.

---

## 📊 Dataset
Bank customer dataset containing features like credit score, geography, gender, age, balance, and tenure.

---

## ⚙️ Steps Performed
- Data Cleaning and Preprocessing  
- Handling Categorical Variables (One-Hot Encoding)  
- Feature Selection  
- Handling Imbalanced Data using class_weight  
- Model Training and Evaluation  

---

## 🤖 Models Used
- Logistic Regression  
- Random Forest  

---

## 📈 Results
- Logistic Regression Recall (Churn): **0.72**  
- Random Forest Recall (Churn): **0.47**  
- Selected Logistic Regression due to better churn detection  

---

## 🧠 Key Insights
- Class imbalance significantly affects model performance  
- Improving recall is more important than accuracy in churn prediction  
- Features like age, balance, and tenure impact churn behavior  

---

## 🚀 Future Improvements
- Use SMOTE for better imbalance handling  
- Try advanced models like XGBoost  
- Deploy model using Flask or Streamlit  

---

## 📌 Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
