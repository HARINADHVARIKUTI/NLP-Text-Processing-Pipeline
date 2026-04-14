# NLP-Text-Processing-Pipeline

# 🧠 Feature Engineering on Text Data (NLP)

## 📌 Overview

This project focuses on **feature engineering techniques in Natural Language Processing (NLP)** using real-world product reviews.

Initially, **200 reviews of an Amazon product were web scraped** and used as the dataset. The notebook demonstrates how raw text is converted into numerical representations suitable for machine learning models.

---

## 📁 Project Structure

.
├── NLP_Feature_Engineering.ipynb
├── amazon_reviews_200.csv
└── README.md
```

---

## 🔍 Dataset

* **Source:** Amazon product reviews
* **Collection Method:** Web scraping
* **Size:** 200 reviews
* **Format:** CSV file with column:

---

## 🧹 Preprocessing Steps

The following preprocessing steps are applied:

* Convert text to lowercase
* Tokenization
* Remove punctuation
* Remove stopwords (optional)
* Lemmatization (optional)

---

## 🔧 Feature Engineering Techniques

The notebook implements the following techniques:

### 1️⃣ One Hot Encoding (OHE)

* Converts words into binary vectors
* High dimensional and sparse representation

---

### 2️⃣ Bag of Words (BoW)

* Counts frequency of words in each document
* Simple and effective baseline method

---

### 3️⃣ TF-IDF (Term Frequency - Inverse Document Frequency)

* Assigns importance to words
* Reduces weight of common words

---

### 4️⃣ Word2Vec Embeddings

* Generates dense vector representations
* Captures semantic relationships between words

---

## 📊 Sparse Matrix Analysis

* Matrix shapes are analyzed
* Sparsity (percentage of zeros) is calculated
* Observed that BoW and TF-IDF produce highly sparse matrices

---

## 🎯 Key Insights

* One Hot Encoding produces very high-dimensional sparse vectors
* BoW captures frequency but not importance
* TF-IDF improves feature importance by reducing common word influence
* Word2Vec captures semantic meaning and produces dense vectors

---

## ⚠️ Notes

* Amazon scraping may require manual CAPTCHA handling
* Dataset size is limited (200 reviews)
* Results depend on preprocessing quality

---

## 📦 Requirements

pip install pandas numpy scikit-learn nltk gensim selenium webdriver-manager
```

---


## 🚀 Future Work

* Apply these features to classification models
* Use pre-trained embeddings (GloVe, BERT)
* Increase dataset size for better analysis

---

## 🙌 Conclusion

This project demonstrates how different feature engineering techniques transform raw text into structured numerical data, which is essential for building effective NLP models.

---


