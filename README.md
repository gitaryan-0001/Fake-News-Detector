# 📰 Fake News Detection Using Machine Learning
This project is a **Machine Learning-based Fake News Detection system** built using Python and popular ML libraries like **Scikit-learn, Pandas, and TfidfVectorizer**. It predicts whether a news article is real or fake by analyzing its textual content.

The model was trained on real-world datasets and tested using multiple classification algorithms to evaluate accuracy and performance.

---
## 📌 Features

- Classifies news articles as **Fake** or **Real**
- Supports manual testing (custom user input)
- Compares multiple ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- Evaluates model performance using classification reports

---

## 🧠 What I Learned

- Data preprocessing and cleaning using **regex**, **string manipulation**
- Text feature extraction using **TF-IDF Vectorizer**
- Splitting and training data using **train_test_split**
- Applying and comparing **multiple ML models**
- Making predictions and evaluating models using **classification reports**
- Automating prediction on user input with a custom function

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib & Seaborn (for visuals)
- Scikit-learn
- TfidfVectorizer
- Regex & String operations

---

## 📂 Project Workflow

1. Load and merge fake & real news datasets
2. Clean the data using regex and remove noise (dates, punctuation, digits, etc.)
3. Convert text into numerical format using **TF-IDF**
4. Train the following ML models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
5. Evaluate models using accuracy and classification report
6. Accept manual news input and predict its authenticity using all models

---

## 🧪 Manual Testing Example
news = "Some fake article or real news text here..."
manual_testing(news)

