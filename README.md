# Spam-classifier
# 📧 Spam Email Classifier

A machine learning project to classify SMS/email messages as **Spam** or **Ham (Not Spam)** using **Logistic Regression** and **TF-IDF vectorization**.

---

## 📌 Problem Statement
Email spam wastes storage, bandwidth, and user attention. The goal is to build a model that automatically detects spam messages with high precision and recall.

---

## 🛠️ Approach
1. **Data Preprocessing**
   - Lowercased text
   - Removed punctuation, URLs, and extra spaces
   - Converted text to numerical vectors using **TF-IDF**

2. **Modeling**
   - Trained a **Logistic Regression** classifier
   - Evaluated performance using accuracy, precision, recall, and F1-score

3. **Evaluation**
   - Achieved **~96% accuracy** on test data
   - Precision (Spam class): **0.95**
   - Recall (Spam class): **0.97**

---

## 📊 Results
Confusion Matrix (example):

|            | Predicted Ham | Predicted Spam |
|------------|---------------|----------------|
| **Actual Ham**  | 965           | 10             |
| **Actual Spam** | 25            | 140            |

- High recall means very few spam messages go undetected.  
- High precision means very few normal messages are misclassified as spam.  

---

