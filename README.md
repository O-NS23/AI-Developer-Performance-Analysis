# 🚀 AI Developer Performance Prediction

This project analyzes developer productivity and well-being using Machine Learning.  
Using metrics like coding hours, bugs, AI usage, sleep, stress and workload, the model predicts:

- ✅ Task Success Rate
- 😰 Stress Level
- ❌ Expected Errors

The goal is to understand how developer behavior affects performance and to help improve productivity and health.

---

## 📂 Dataset Overview
The dataset contains **1000 developer records** with the following features:

### 🔹 Input Features
- Hours_Coding  
- Lines_of_Code  
- Bugs_Found  
- Bugs_Fixed  
- AI_Usage_Hours  
- Sleep_Hours  
- Cognitive_Load  
- Coffee_Intake  
- Task_Duration_Hours  
- Commits  

### 🎯 Prediction Outputs
- Task_Success_Rate  
- Stress_Level  
- Errors  

---

## 🧠 Project Workflow

### ✅ Step 1 — Data Understanding
- Checked missing data  
- Verified datatypes  
- Summary statistics  

---

### 📊 Step 2 — EDA
- Correlation Heatmap  
- Relationship Visualizations  
  - Coding Hours vs Success Rate  
  - Sleep vs Success Rate  
  - AI Usage vs Success Rate  
  - Coffee Intake vs Success  

---

### 🤖 Step 3 — Machine Learning Models
Multiple regression models were trained and compared:

- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  

📌 **Best Models:** Gradient Boosting & XGBoost (Highest R²)

---

## 🏆 Model Evaluation
Performance measured using:

- MAE  
- MSE  
- RMSE  
- R² Score  

Also included:
- Comparison Charts  
- Performance Heatmap  

---

## 🎯 Final Feature — User Prediction System
A custom prediction pipeline allows the user to enter developer details and predicts:

- Task Success Rate  
- Stress Level  
- Expected Errors  

Useful for:
- Team Leads  
- Project Managers  
- Developer Health Monitoring  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- XGBoost  

---

## ▶️ How to Run
1️⃣ Clone the repo  
```bash
git clone <repository_link>
```

2️⃣ Install dependencies  
```bash
pip install -r requirements.txt
```

3️⃣ Run the notebook or script

---

## 💡 Key Insights
- AI usage improves productivity  
- Sleep strongly reduces stress  
- High cognitive load decreases performance  
- Commits indicate structured progress  

---

## 🚀 Future Enhancements
- Streamlit Web App  
- Interactive Dashboard  
- Model Explainability (SHAP)  
- API Deployment  

---

## 🙌 Contributions
Contributions are welcome!  
Feel free to fork, improve, and submit PRs.

---

## ⭐ Support
If you like this project, please ⭐ star the repository 🙂
