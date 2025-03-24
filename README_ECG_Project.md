
# ECG Classification using Machine Learning and Deep Learning



## 🩺 Introduction

Electrocardiogram (ECG) signals are essential in diagnosing abnormalities in heart rhythms, including arrhythmias. Arrhythmias can lead to symptoms such as chest pain, fainting, or sudden cardiac arrest. This project focuses on analyzing two widely used datasets — **MIT-BIH Arrhythmia** and **PTB Diagnostic ECG** — using machine learning and deep learning techniques to classify heartbeats and detect abnormalities.

The goal is to build robust models that can accurately classify heartbeats, visualize results, and evaluate performance using metrics like accuracy, F1-score, and confusion matrix.

##  Dataset Description

- **MIT-BIH Dataset:**  
  - 48 half-hour recordings from 47 subjects  
  - 109,446 samples categorized into 5 classes  
  - Challenges include class imbalance

- **PTB Diagnostic Dataset:**  
  - 549 records from 290 subjects  
  - 14,552 heartbeat samples in 2 categories (normal/abnormal)  
  - Binary classification problem

## 🔍 Methodology

- **Data Preprocessing:** Cleaning and checking for missing/null values
- **Exploratory Data Analysis (EDA):** Understanding patterns and visualizing class distribution
- **Data Imbalance Handling:** Using SMOTE (Synthetic Minority Oversampling Technique)
- **Data Transformation & Concatenation:** Ensuring consistency across datasets for modeling

## 🤖 Machine Learning Models

| Model                  | MIT-BIH Accuracy | PTB Accuracy |
|------------------------|------------------|--------------|
| Support Vector Machine | -                | 87.6%        |
| Random Forest          | 98.1%            | 96.8%        |
| K-Nearest Neighbor     | 95.2%            | 93.5%        |
| Logistic Regression    | -                | 80.1%        |

## 🧠 Deep Learning Models

- **Artificial Neural Network (ANN):**  
  - MIT-BIH: 97%  
  - PTB: 98.4%  
- **Convolutional Neural Network (CNN):**  
  - MIT-BIH: 94.08%  
  - PTB: 98.9%

##  Evaluation Metrics

- **Confusion Matrix**
- **Precision / Recall / F1 Score**
- **Overfitting Analysis (Accuracy & Loss curves)**

## ⚠️ Limitations

- MIT-BIH is based mostly on patients from a single hospital (Boston), affecting diversity
- PTB dataset has limited samples (290 subjects)
- Lack of real-world noise might limit generalization
- Datasets are relatively old

## ✅ Conclusion

All models performed well, especially deep learning models due to their network architecture. Class imbalance was effectively handled using SMOTE. Random Forest and CNN produced the highest accuracies on both datasets, showing great potential for automated ECG classification in medical applications.

## 📚 References

- Ahamed, M.A. et al. (2020). *ECG heartbeat classification using ensemble...*
- Keerthana, N. et al. (2023). *Analysis of Cardiovascular Arrhythmia...*
- Sarvani, K.N.S. et al. (2023). *Prediction of Sudden Cardiac Arrest...*
- Sraitih, M. et al. (2021). *An overview on machine learning methods...*
- Zheng, H. and IEEE (2014). *2014 IEEE Conference on Bioinformatics...*

---

## 🧠 Skills Demonstrated

- Data Cleaning & EDA
- Imbalanced Data Handling
- Model Building & Evaluation
- Deep Learning (ANN, CNN)
- Scientific Reporting & Research

This project uses:

- [MIT-BIH Arrhythmia Dataset](https://www.physionet.org/content/mitdb/1.0.0/)
- [PTB Diagnostic ECG Dataset](https://www.physionet.org/content/ptbdb/1.0.0/)

