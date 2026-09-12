# Movie Review Sentiment Classification

A Natural Language Processing (NLP) project that classifies movie reviews as **Positive** or **Negative** using Machine Learning.

The project uses **TF-IDF Vectorization** and compares the performance of multiple classification algorithms using Scikit-learn Pipelines.

---

## Project Overview

This project demonstrates an end-to-end NLP workflow for sentiment analysis.

The workflow includes:

- Loading and exploring the dataset
- Text preprocessing
- Feature extraction using TF-IDF
- Building Scikit-learn Pipelines
- Training multiple machine learning models
- Evaluating and comparing model performance
- Predicting the sentiment of new movie reviews

---

## Dataset

The dataset contains movie reviews with two sentiment labels:

- **Positive (pos)**
- **Negative (neg)**

Example:

| Review | Label |
|---------|-------|
| This movie was absolutely amazing! | Positive |
| I regret watching this movie. | Negative |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## Machine Learning Models

The following classifiers were implemented and compared:

- Support Vector Machine (SVM)
- Logistic Regression
- Multinomial Naive Bayes
- Random Forest
- Decision Tree


---

## Machine Learning Pipeline

Each classifier was built using a Scikit-learn Pipeline.

```
Movie Review
      │
      ▼
TF-IDF Vectorizer
      │
      ▼
Machine Learning Model
      │
      ▼
Prediction
```

This ensures that text preprocessing and classification are performed consistently for every model.

---

## Model Evaluation

The models were evaluated using:

- Accuracy
- Classification Report
- Performance Comparison

Example:

| Model | Accuracy |
|--------|-----------|
| SVM | 0.85  |
| Logistic Regression | 0.82 |
| Naive Bayes | 0.76 |
| Random Forest | 0.77  |
| Decision Tree | 0.62  |




