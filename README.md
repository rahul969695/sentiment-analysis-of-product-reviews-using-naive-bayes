# 🧠 Sentiment Analysis of Amazon Product Reviews
This project performs sentiment analysis on Amazon product reviews using Machine Learning and NLP techniques.
The model classifies reviews into:
- Positive 😊
- Negative 😡
- Neutral 😐

---

## 📌 Project Description

This project uses the **Amazon Review Dataset (3 million reviews)** and applies Natural Language Processing (NLP) techniques to analyze customer sentiment.

The dataset includes:
- Rating (1 to 5)
- Title
- Review Text

We combine Title + Review and classify sentiment based on rating.

---

## 🎯 Sentiment Logic

- Rating > 3 → Positive  
- Rating < 3 → Negative  
- Rating = 3 → Neutral  

---

## 📊 Dataset Details

- Total Records: **3,000,000**
- Columns:
  - Review (Title + Review combined)
  - Rating
  - Sentiment (Generated)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas & NumPy
- NLTK (Text Processing)
- Scikit-learn (ML Models)
- Matplotlib & Seaborn (Visualization)
- WordCloud

---

## 🔄 Workflow

### 1. Data Loading
- Loaded dataset using Pandas

### 2. Data Preprocessing
- Combined Title + Review
- Tokenization using NLTK
- Stopwords removal
- Stemming & Lemmatization

### 3. Feature Extraction
- CountVectorizer
- TF-IDF Vectorizer

### 4. Model Building
- Logistic Regression
- Support Vector Machine (SVM)

### 5. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

### 6. Visualization
- Sentiment distribution
- WordCloud for frequent words

---

## 📈 Results

- Balanced dataset across all ratings
- Model successfully classifies sentiment into 3 categories
- Visualization shows distribution of positive, negative, and neutral reviews

---
