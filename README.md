# 🚀 Healthcare Claim Denial Prediction  
*A machine learning project predicting whether healthcare claims are approved or denied.*

---

## 📌 Project Overview
Healthcare claim denials cost hospitals millions every year.  
This project explores patterns in medical claim data and builds a predictive model to classify claims as **Approved** or **Denied**.

The project includes:
- Data exploration & visualization  
- Feature engineering  
- Machine learning (Random Forest)  
- Model evaluation  
- Feature importance analysis  

---

## 📊 Dataset
Synthetic dataset with **5,000 healthcare claims**, including:

- Patient Age  
- Insurance Type  
- Provider Type  
- Claim Amount  
- Number of Procedures  
- Diagnosis Category  
- Prior Denials  
- Claim Complexity  
- Submission Type  
- Final Decision (Denied: 1 / Approved: 0)

---

## 🎯 Goal
Identify which claims are likely to be denied and understand **why** denials happen.

---

## 📈 Model Performance (Random Forest)

| Metric | Score |
|--------|--------|
| Accuracy | **0.67** |
| Recall (Approved) | **0.87** |
| Recall (Denied) | **0.29** |
| Precision (Approved) | **0.70** |
| Precision (Denied) | **0.52** |

**Interpretation:**  
The model performs well for approved claims but struggles with denials — a common issue due to class imbalance and claim variability.

---

## 🧠 Feature Importance
Top predictors of denials:

1. **Claim Amount**  
2. **Patient Age**  
3. **Number of Procedures**  
4. **Prior Denials**  
5. **High Claim Complexity**  
6. Insurance Type (HMO, PPO)  
7. Provider Type (Urgent Care, Surgery)

These reflect real-world payer behavior — higher cost, complexity, and prior history drive denials.

---

## 📉 Confusion Matrix
(Add your confusion matrix image here)

---

## 📊 Top Feature Importance Chart
(Add your feature importance chart here)

---

## 🧪 Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📦 Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

```bash
jupyter notebook notebooks/claim_denial_prediction.ipynb
```

---

## 👩‍💻 Author  
**Julia Giles**  
Data & Analytics | Healthcare | Operations  

LinkedIn: https://www.linkedin.com/in/julia-giless

