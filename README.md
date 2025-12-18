# Predicting CSE Undergraduate Students’ Careers Using Machine Learning  
### Context: Bangladesh

## 📌 Overview
This repository contains the complete research materials for a thesis and research study on **multi-label career prediction for Computer Science and Engineering (CSE) undergraduate students in Bangladesh** using machine learning techniques.

The project integrates real student data, skill assessments, and career preferences to recommend **multiple relevant career sectors** instead of a single career outcome.

---

## 📄 Research Paper
**Title:** Predicting CSE Undergraduate Students’ Careers Using Machine Learning Algorithms in the Context of Bangladesh  

**Authors:**  
- Asfak Shahriur  
- Israt Jahan Reshma  
- Saleh Ahmed  


## 📊 Dataset Information
- **Total students:** 468  
- **Universities covered:** 47 (public & private)  
- **Features:** 24  
- **Label type:** Multi-label (students can belong to multiple career sectors)

### Dataset files used in the study:
- `CSE Thesis - Sheet1.csv` (raw survey data)
- `clean_data.csv`
- `final_dataset.csv`
- `skills.csv`
- `Skills_list.csv`
- `rules.csv`
- `predictions.csv`

> All datasets are anonymized and collected via structured questionnaire surveys.

---

## 🧠 Methodology Summary
1. Data collection via online survey  
2. Data preprocessing (cleaning, encoding, normalization)  
3. Multi-label encoding using `MultiLabelBinarizer`  
4. Model training & evaluation  

### Machine Learning Models:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- XGBoost  
- Support Vector Machine (SVM / SVC)  
- KNN  
- Neural Network (MLP)  
- Hard & Soft Voting Classifiers  

### Evaluation Metrics:
- Accuracy  
- Precision  
- Recall  
- Micro F1-score  
- Macro F1-score  
- Hamming Loss  

XGBoost achieved the best overall performance across most metrics.

