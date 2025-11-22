# 💳 Loan Eligibility Prediction Project

## 📌 Overview
This project predicts whether a loan application should be **approved or rejected** based on applicant details.  
I implemented **Logistic Regression, Decision Tree, Random Forest, and KNN classifiers**, applied **data preprocessing, feature scaling, and model evaluation techniques**, and built a simple **Gradio app interface** for user-friendly predictions.

---

## ⚙️ Workflow
1. **Data Preparation** – Cleaned and encoded categorical features (Gender, Married, Dependents, Education, etc.).  
2. **Feature Engineering** – Created log-transformed features (ApplicantIncomeLog, LoanAmountLog, TotalIncomeLog) for better scaling.  
3. **Standardisation** – Applied `StandardScaler` to normalise numerical features.  
4. **Model Training** – Trained Logistic Regression, Decision Tree, Random Forest, and KNN classifiers.  
5. **Model Evaluation** – Compared models using accuracy, precision, recall, and F1-score.  
6. **Deployment** – Built a **Gradio interface** to allow interactive loan eligibility predictions.  

---

## 📊 Results

| Model               | Accuracy  | Precision | Recall  | F1-Score |
|---------------------|-----------|-----------|---------|----------|
| Random Forest       | 0.788618  | 0.770000  | 0.9625  | 0.855556 |
| Decision Tree       | 0.674797  | 0.743902  | 0.7625  | 0.753086 |
| KNN                 | 0.731707  | 0.737374  | 0.9125  | 0.815642 |
| Logistic Regression | 0.788618  | 0.759615  | 0.9875  | 0.858696 |

👉 Final chosen model: **Logistic Regression** (balanced accuracy, precision, recall, and interpretability).

---

## 🚀 Key Learnings
- Handling categorical variables with encoding is crucial for ML models.  
- Log transformations improved feature scaling and model stability.  
- Ensemble models like Random Forest performed well, but Logistic Regression provided clearer interpretability.  
- Building a **Gradio app** demonstrated deployment skills and practical usability.

---

## 📂 Project Structure
- `notebooks/loan_eligibility_prediction.ipynb` → Main notebook with code and analysis.  
- `app/loan_prediction_app.py` → Gradio app script.  
- `data/` → Dataset (not included here, add your source).  
- `README.md` → Project documentation.  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn (Logistic Regression, Decision Tree, Random Forest, KNN)  
- Gradio (for app interface)  
- Jupyter Notebook  

---

## 📌 Conclusion
Logistic Regression achieved the best balance of accuracy (**0.79**), precision (**0.76**), recall (**0.99**), and F1-score (**0.86**).  
This makes it the most effective and interpretable model for loan eligibility prediction.  
Future improvements could include **hyperparameter tuning** and testing advanced models like XGBoost.

---

## 📜 Author
**Sashank** – Data Science & Machine Learning Enthusiast
