# 🧠 TripAdvisor Hotel Review Classification

This project focuses on classifying hotel reviews from TripAdvisor into different sentiment categories using Natural Language Processing (NLP) and Machine Learning techniques.

## 📌 Project Objective

The goal is to build a multi-class text classification model that can predict the sentiment (rating) of a given review. This can help businesses understand customer opinions and improve their services based on feedback.

---

## 🗂️ Dataset

- Source: [Kaggle TripAdvisor Hotel Reviews Dataset](https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews)
- Total Records: 20,000+ hotel reviews
- Features:
  - `Review`: Text of the review
  - `Rating`: Numerical rating (1 to 5)

---

## ⚙️ Technologies & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn, WordCloud
- NLTK, Scikit-learn
- TF-IDF Vectorization
- Machine Learning Models:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Support Vector Machines (SVM)
  - Random Forest
  - XGBoost

---

## 🔍 Key Steps

1. **Data Cleaning**
   - Removed null values
   - Text preprocessing (lowercase, punctuation removal, stopwords removal, etc.)

2. **Exploratory Data Analysis (EDA)**
   - Visualized rating distributions
   - WordClouds for frequent words per rating

3. **Feature Extraction**
   - Applied TF-IDF Vectorizer to convert text to numerical features

4. **Model Building**
   - Trained multiple classifiers
   - Evaluated models using accuracy, precision, recall, F1-score, and confusion matrix

5. **Model Comparison**
   - Compared model performance to select the best classifier

---

## 📈 Results

- The best-performing model showed high accuracy in classifying reviews.
- Model helps automate review analysis and can be integrated into customer service systems.

---

## 📎 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ghantahaindavi/tripadvisor.git
