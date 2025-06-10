# spam-ham-classifier
SMS Spam Detection using NLP and Naive Bayes
# 📧 Spam/Ham Classifier using NLP

This project classifies SMS messages into **spam** or **ham** using Natural Language Processing and machine learning techniques.

## 🚀 Features
- Clean and preprocess text messages
- TF-IDF vectorization
- Multinomial Naive Bayes classifier
- ~97% accuracy
- Sample predictions
- Bonus: Streamlit app support (optional)

## 📁 Files
- `spam_ham_classifier_colab.ipynb`: Main notebook with code
- `Spam_Ham_Classifier_Project_Report.pdf`: 1-page project report
- `Resume_Project_Description.txt`: Brief description for resumes
- `requirements.txt`: Python dependencies

## 🧪 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run cells step-by-step
3. Use your own messages to test spam/ham prediction

## 🔧 Requirements

## 📊 Sample Prediction
```python
predict_message("You have won a free iPhone!")  # ➝ Spam
predict_message("Are we still on for dinner?")   # ➝ Ham

---

### 📦 **2. Create `requirements.txt`**
```txt
pandas
numpy
scikit-learn
matplotlib
seaborn
