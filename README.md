# 📩 Spam Classification using Logistic Regression

This project builds a machine learning model to classify SMS messages as **spam or ham** using Natural Language Processing (NLP) techniques.

---

## 🚀 Project Overview
The goal of this project is to automatically detect spam messages using text processing and machine learning. The dataset is preprocessed, transformed using TF-IDF, and classified using Logistic Regression.

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- NLTK  
- Matplotlib, Seaborn  

---

## 📊 Dataset
- SMS Spam Collection Dataset  
- Contains labeled messages as *spam* or *ham*  

---

## ⚙️ Methodology
1. Data loading and cleaning  
2. Text preprocessing (lowercasing, removing punctuation, stopwords)  
3. Feature extraction using TF-IDF  
4. Model training using Logistic Regression  
5. Prediction and evaluation  

---

## 📈 Results
- Successfully classifies SMS messages into spam or ham  
- TF-IDF captures important word patterns  
- Words like *free*, *win*, *call* strongly indicate spam  

---

## 🔍 Observations
- Dataset is imbalanced (more ham than spam)  
- Spam messages tend to be longer and promotional  
- Logistic Regression works well but does not capture deep context  

---

## 📁 Files
- `spam_classifier.ipynb` → Main project notebook  
- `cleaned_sms_spam.csv` → Processed dataset  

---

## 💡 Future Improvements
- Try advanced models (Naive Bayes, SVM, Deep Learning)  
- Improve text preprocessing (stemming/lemmatization)  
- Deploy as a web app  

---

## 👩‍💻 Author
Preksha
