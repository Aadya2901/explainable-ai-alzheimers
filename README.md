# 🧠 Explainable AI for Early Alzheimer’s Risk Detection

An interpretable machine learning project that explores early Alzheimer’s disease risk detection using de-identified clinical and cognitive data, with a strong focus on transparency, ethics, and reproducibility.

This project was developed as part of the **AI 4 Alzheimer’s (Hack4Health)** hackathon.

---

## 📌 Project Overview

Alzheimer’s disease is often diagnosed at a late stage, despite early warning signals being present in clinical and cognitive data. This project investigates how **machine learning models**, combined with **explainability techniques**, can support early risk analysis in a responsible and interpretable manner.

Rather than acting as a diagnostic system, this work is intended to **support research and awareness** by highlighting patterns and contributing factors associated with Alzheimer’s risk.

---

## 🎯 Objectives

- Build machine learning models to classify cognitive states (CN / MCI / AD)
- Compare baseline and advanced ML approaches
- Emphasize **model interpretability** using feature importance and SHAP values
- Ensure reproducibility through a clean, end-to-end notebook
- Maintain ethical and non-diagnostic framing

---

## 📊 Dataset

- De-identified clinical and cognitive dataset provided by the AI 4 Alzheimer’s hackathon
- Includes demographic, cognitive assessment, and clinical features
- Used strictly for research and educational purposes

---

## 🛠️ Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Feature normalization
   - Train–test split with stratification

2. **Modeling**
   - Logistic Regression (baseline)
   - Random Forest Classifier
   - Gradient Boosting / XGBoost

3. **Evaluation**
   - Accuracy
   - Precision & Recall
   - Confusion Matrix
   - ROC-AUC (where applicable)

4. **Explainability**
   - Feature importance analysis
   - SHAP (SHapley Additive exPlanations) for global and individual predictions

---

## 📈 Key Results

- Tree-based models outperformed linear baselines
- Cognitive assessment scores and age-related features showed strong influence
- SHAP analysis provided clear, interpretable explanations for predictions

---

## 📁 Repository Structure

```
.
├── AI_4_Alzheimers_Explainable_ML.ipynb 
├── README.md 
└── report.pdf
```


---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Open the notebook in Google Colab
2. Upload the dataset or mount Google Drive
3. Run all cells sequentially

### Option 2: Local Setup

```
pip install pandas numpy scikit-learn xgboost shap matplotlib seaborn
```

Then open the notebook using Jupyter.

---

## 🧑‍🤝‍🧑 Team Contributions

This project was developed collaboratively. Team members contributed across:

- Data preprocessing & exploratory analysis  
- Model development & evaluation  
- Explainability analysis  
- Documentation & reporting  

---

## ⚠️ Ethical Disclaimer

This project is intended for **research and educational purposes only**.  
It does **not** provide medical diagnosis, treatment, or clinical recommendations.  
All predictions should be interpreted by qualified healthcare professionals.

---

## 🔮 Future Work

- Incorporate additional public Alzheimer’s datasets  
- Explore longitudinal modeling for disease progression  
- Improve uncertainty estimation and calibration  
- Collaborate with domain experts for clinical validation  

---

## 📜 License

This project is released under the **MIT License**.

