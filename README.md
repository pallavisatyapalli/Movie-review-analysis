# 🎬 Movie Review Sentiment Classifier

A machine learning project that classifies movie reviews as **positive** or **negative** using Natural Language Processing (NLP) techniques. Built using Python, NLTK, and Scikit-learn, this project leverages the preloaded `movie_reviews` corpus from NLTK to demonstrate sentiment analysis on textual data.

---

## 📌 Project Overview

- ✅ Uses **NLTK's movie_reviews** dataset
- ✅ Implements **CountVectorizer** for text feature extraction
- ✅ Trains a **Multinomial Naive Bayes** classifier
- ✅ Achieves around **84% accuracy** on test data
- ✅ Easily extendable to other review-based datasets

---

## 🧠 Tech Stack

| Area              | Tools Used                      |
|-------------------|---------------------------------|
| Language          | Python                          |
| NLP Library       | NLTK                            |
| ML Library        | Scikit-learn                    |
| Algorithms        | CountVectorizer + Naive Bayes   |

---

## 🔍 How It Works

1. **Load Dataset:** Uses `movie_reviews` from NLTK with 2 classes – `pos` and `neg`
2. **Preprocessing:** No extensive cleaning needed, raw text used directly
3. **Vectorization:** Converts text into numerical vectors using `CountVectorizer`
4. **Model Training:** Trains `MultinomialNB` (Naive Bayes for text data)
5. **Evaluation:** Tests on 500 reviews, calculates accuracy

---

## 🚀 Getting Started

### ✅ Requirements

Install dependencies:

```bash
pip install nltk scikit-learn
