# Reducing False Negatives in Breast Cancer Diagnosis  
### A Hybrid Framework Using Feature Selection, ADASYN, and Cost-Sensitive XGBoost

## 📌 Overview
False negative errors in medical diagnosis represent one of the most critical risks in clinical decision support systems, particularly in cancer detection where missed diagnoses can lead to delayed treatment and reduced survival rates.  
This repository presents a **hybrid machine learning framework** specifically designed to **minimize false negatives** in breast cancer diagnosis under class imbalance.

The proposed approach integrates **feature selection**, **adaptive oversampling (ADASYN)**, and **cost-sensitive gradient boosting (XGBoost)** into a unified pipeline that aligns statistical performance with real-world clinical priorities.

---

## 🧠 Research Motivation
Medical datasets are inherently imbalanced, with malignant cases typically forming the minority class. Conventional classifiers optimized for accuracy tend to favor the majority class, leading to dangerously high false negative rates.

This research addresses the gap between:
- **High statistical accuracy**
- **Low clinical reliability**

by explicitly prioritizing **sensitivity (recall)** for malignant cases while maintaining robust overall performance.

---

## 🏗️ Proposed Hybrid Framework
The system follows a sequential architecture:

