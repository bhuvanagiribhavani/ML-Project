# Emotion Detection from Text

## Overview
This project implements a Machine Learning based emotion classification system that detects human emotions from textual data using Natural Language Processing (NLP) techniques.

The model classifies text into six emotion categories:
- Anger  
- Fear  
- Joy  
- Love  
- Sadness  
- Surprise  

The objective is to build an emotion-aware system capable of understanding and categorizing emotional expressions in social media text.

---

## Dataset
- Source: SemEval-2018 Affect in Tweets  
- Total Samples: 20,000 labeled tweets  
- Emotion Classes: anger, fear, joy, love, sadness, surprise  

---

## Methodology

### Text Preprocessing
- Lowercasing text  
- Emoji replacement using a custom dictionary  
- Removal of URLs, mentions, punctuation, and numbers  
- Tokenization  
- Stopword removal  
- Lemmatization  

### Feature Engineering
- CountVectorizer  
- TF-IDF (Term Frequency – Inverse Document Frequency)  

### Models Implemented
- Support Vector Machine (SVM)  
- Logistic Regression  
- Random Forest Classifier  
- Multinomial Naive Bayes  
- Decision Tree Classifier  

---

## Results

| Model                     | Accuracy  |
|---------------------------|-----------|
| Support Vector Machine    | 85.675%   |
| Logistic Regression       | 80.847%   |
| Decision Tree             | 83.434%   |
| Random Forest             | 75.805%   |
| Naive Bayes               | 43.572%   |

Best Performing Model: Support Vector Machine (SVM)

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## Tech Stack
- 🐍 Python  
- 📊 Pandas  
- 🔢 NumPy  
- 🧠 NLTK  
- 🤖 Scikit-learn  
- 📈 Matplotlib  
- 🎨 Seaborn  
- 📓 Jupyter Notebook  

---

## Applications
- Social Media Sentiment Monitoring  
- Mental Health Analysis  
- Customer Feedback Analysis  
- Emotionally Intelligent Chatbots  

---

## Author
Bhuvanagiri Bhavani  
B.Tech – CSE (Artificial Intelligence & Machine Learning)