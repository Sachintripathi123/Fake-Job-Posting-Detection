# Fake Job Posting Detection using Machine Learning

## 📌 Project Overview

This project aims to detect fraudulent job postings using **Machine Learning** and **Natural Language Processing (NLP)** techniques. The system analyzes job-related textual information and predicts whether a job posting is **Genuine** or **Fraudulent**.

The project was developed as part of the **3Skills AI & ML Internship**.

---

## 🎯 Objectives

- Detect fake job postings automatically.
- Perform text preprocessing using NLP techniques.
- Compare multiple machine learning models.
- Identify the best-performing classification model.
- Build a prediction system for unseen job postings.

---

## 📂 Dataset

**Dataset Name:** Fake Job Postings Dataset

- Total Records: **17,880**
- Features: **18**
- Target Variable:
  - **0 → Genuine Job Posting**
  - **1 → Fraudulent Job Posting**

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK

---

## 🔄 Project Workflow

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Handling Missing Values
4. Text Preprocessing
5. Stopword Removal
6. Stemming
7. TF-IDF Feature Extraction
8. Model Training
9. Model Evaluation
10. Prediction System

---

## 🧹 Text Preprocessing

The following preprocessing techniques were applied:

- Handling Missing Values
- Lowercase Conversion
- Removing Special Characters
- Removing Numbers
- Removing Extra Spaces
- Stopword Removal
- Stemming

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- Multinomial Naive Bayes
- Random Forest Classifier
- Support Vector Machine (Linear SVM)

Hyperparameter tuning was performed using **GridSearchCV**.

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **97.23%** |
| Naive Bayes | **96.25%** |
| Random Forest | **97.90%** |
| Support Vector Machine | **98.32%** |
| Tuned SVM | **98.23%** |

**Best Model:** Support Vector Machine (SVM)

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🚀 Prediction System

The final model predicts whether a new job posting is:

- ✅ Genuine Job Posting
- ❌ Fraudulent Job Posting

---

## 📁 Project Structure

```
Fake-Job-Posting-Detection/
│
├── Fake_Job_Posting_Detection.ipynb
├── Fake_Job_Posting_Detection_Report.pdf
├── fake_job_postings.csv.zip
├── README.md
└── images/
```

---

## ▶️ How to Run

1. Clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required libraries.
4. Run all cells in sequence.
5. Test the model using new job posting text.

---

## 📌 Future Improvements

- BERT-based Text Classification
- LSTM Model
- Explainable AI (XAI)
- Flask/Django Web Application
- Real-time Fraud Detection API

---

## 👨‍💻 Author

**Sachin Tripathi**

B.Tech – Computer Science & Engineering (AI & ML)

Swami Devi Dayal Institute of Engineering & Technology

Project completed during the **3Skills AI & ML Internship**.

---

## ⭐ If you found this project useful, consider giving it a Star.