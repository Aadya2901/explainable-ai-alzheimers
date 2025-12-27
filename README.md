# 🧠 Explainable AI for Early Alzheimer’s Risk Detection

An interpretable machine learning project exploring **early Alzheimer’s risk detection** using **synthetic clinical and cognitive data**, with a strong emphasis on **transparency, ethics, and reproducibility**.

This project was developed as part of the **AI 4 Alzheimer’s (Hack4Health) Hackathon**.

---

## 📌 Project Overview

Alzheimer’s disease is often diagnosed at a late stage, even though early warning signals may be present in cognitive and clinical indicators.

This project demonstrates how **machine learning models combined with explainability techniques** can support **early risk analysis** in a responsible and interpretable manner.

⚠️ This system is **not a diagnostic tool**.  
It is intended for **research, education, and awareness**, highlighting patterns and contributing factors associated with Alzheimer’s risk.

---

## 🎯 Objectives

- Build machine learning models for **binary Alzheimer’s risk classification**
- Compare a baseline linear model with a non-linear ensemble model
- Emphasize **model interpretability** using feature importance analysis
- Ensure **reproducibility** through a clean, end-to-end notebook
- Maintain an **ethical and non-diagnostic framing**

---

## 📊 Dataset

- **Synthetic clinical and cognitive dataset** generated for this project  
- Designed to mimic real-world Alzheimer’s-related indicators:
  - Age
  - MMSE score
  - Memory score
  - Cognitive score
- Target variable:
  - `0` → No Alzheimer’s  
  - `1` → Alzheimer’s  

📌 No real patient data was used.

---

## 🛠️ Methodology

### Data Preprocessing
- Handling missing values  
- Feature normalization (for linear models)  
- Stratified train–test split  

### Modeling
- **Logistic Regression** (baseline model)  
- **Random Forest Classifier** (advanced, non-linear model)  

### Evaluation
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  
- ROC-AUC score  

### Explainability
- Random Forest **feature importance analysis**  
- SHAP (SHapley Additive exPlanations) explored for interpretability  
  *(visualization limited due to execution environment constraints)*  

---

## 📈 Key Results

- Tree-based models outperformed linear baselines  
- Cognitive and memory-related features showed strong influence  
- Feature importance analysis improved transparency and interpretability  
- Performance is limited due to synthetic data, but the pipeline demonstrates a complete and ethical ML workflow  

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
2. Run all cells sequentially 

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

- Incorporate additional public Alzheimer’s datasets (e.g., OASIS, ADNI)
- Explore longitudinal modeling for disease progression  
- Improve uncertainty estimation and calibration  
- Collaborate with domain experts for clinical validation  

---

## 📜 License

This project is released under the **MIT License**.

