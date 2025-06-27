# Email-Spam-Detection

This project is a machine learning-based SMS spam detection system using the Multinomial Naive Bayes classifier. It classifies text messages as either **spam** or **ham** (not spam).

---

## 📂 Dataset

The dataset used is the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset), which contains 5,574 SMS messages tagged as "ham" or "spam".

- `v1`: Label (ham or spam)
- `v2`: SMS message text

---

## 🧠 Machine Learning Workflow

1. **Data Preprocessing**:
   - Load CSV data
   - Split into training and testing sets

2. **Text Vectorization**:
   - Use `CountVectorizer` to convert text to numeric features

3. **Model Training**:
   - Train a `MultinomialNB` (Naive Bayes) classifier

4. **Model Evaluation**:
   - Accuracy score
   - Classification report
   - Confusion matrix heatmap
   - Bar chart of predicted vs actual labels

---
