# 📊 Customer Churn Prediction | End-to-End Data Analytics Project

🚀 A complete **end-to-end Machine Learning project** focused on analyzing customer behavior and predicting churn using real-world telecom data.

This project demonstrates **data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling** to help businesses reduce customer loss and improve retention.

---

# 🎯 Objective

The goal of this project is to:
- Identify customers likely to churn
- Understand key factors influencing churn
- Build a high-performance predictive model
- Provide actionable business insights

---

# 📁 Dataset
The dataset contains information about user activity including:
- gender: Customer's gender (M/F)
- city: The city of residence
- telecom_partner: Mobile network operator
- data_used: Amount of data used
- calls_made: Number of calls made
- sms_sent: Number of SMS sent
- estimated_salary: Monthly estimated salary
- churn: Target variable (Yes/No)

---

# 🛠️ Tech Stack

- **Python**
- **Pandas & NumPy** → Data manipulation
- **Matplotlib & Seaborn** → Data visualization
- **Scikit-learn** → Machine Learning

---

# 🔍 Project Workflow

## 1️⃣ Data Cleaning
- Removed unnecessary columns (e.g., customerID)
- Handled missing values
- Converted data types

## 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Identified trends in:
  - Contract type
  - Monthly charges
  - Tenure
- Used visualizations to uncover patterns

## 3️⃣ Feature Engineering
- Encoded categorical variables
- Scaled numerical features
- Selected important predictors

## 4️⃣ Model Building
- Implemented **Random Forest Classifier**
- Trained on processed dataset
- Compared with baseline models

## 5️⃣ Model Evaluation
- Accuracy: **~87%**
- Evaluated using:
  - Confusion Matrix
  - Precision & Recall
  - F1 Score

## 6️⃣ Optimization
- Hyperparameter tuning
- Improved model performance by ~15%

---

# 📈 Key Insights

- Customers with **month-to-month contracts** are more likely to churn  
- **Low tenure customers** have higher churn probability  
- Higher monthly charges increase churn risk  
- Long-term contracts improve retention  

---

# 📊 Results

| Metric        | Score |
|--------------|------|
| Accuracy     | 87%  |
| Precision    | High |
| Recall       | Strong |
| Model Used   | Random Forest |

---

# 📂 Project Structure
```
EDA-Churn-Prediction/
│── data/
│── notebook/
│ └── eda_churn_prediction.ipynb
│── images/
│── README.md
│── .gitignore
```


---

# 🚀 How to Run

```
# Clone repository
git clone https://github.com/surya999610/eda-churn-prediction.git
```
```
# Navigate to folder
cd eda-churn-prediction
```
```
# Install dependencies
pip install -r requirements.txt
```
```
# Run notebook
jupyter notebook
```

# 💡 Business Impact

This project helps companies:

- Reduce customer churn
- Improve customer retention strategies
- Increase revenue by targeting high-risk customers

  
# 📌 Future Improvements
- Deploy model using Streamlit / Flask
- Use advanced models (XGBoost, LightGBM)
- Handle class imbalance using SMOTE
- Add real-time prediction system

## 👤 Author

Surya Gautam

## 📬 Contact
- GitHub: https://github.com/surya999610
- Email: Suryagautam999@gmail.com
- LinkedIn: https://www.linkedin.com/in/surya-gautam-03bba6286/
