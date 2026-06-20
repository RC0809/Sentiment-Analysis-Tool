# Amazon Reviews Sentiment Analysis using TF-IDF and Logistic Regression

A Machine Learning-based Sentiment Analysis Tool built using the Amazon Fine Food Reviews dataset. The project preprocesses review text, converts it into numerical features using TF-IDF, and trains a Logistic Regression classifier to predict sentiment as Positive or Negative.

---

## Project Overview

This project demonstrates an end-to-end Natural Language Processing (NLP) workflow:

- Loading and exploring review data
- Text preprocessing and cleaning
- Feature extraction using TF-IDF
- Sentiment classification using Logistic Regression
- Model evaluation using Accuracy, Precision, Recall, and F1-Score
- Interactive command-line sentiment prediction

---

## Dataset

**Dataset:** Amazon Fine Food Reviews

Columns Used:
- `Text` – Review text
- `Score` – Rating (1–5)

Sentiment Labels:

| Rating | Sentiment |
|----------|----------|
| 1-2 | Negative |
| 3 | Neutral (Removed) |
| 4-5 | Positive |

> Note: The dataset is not included in this repository due to file size limitations.
---

## Features

- Text Cleaning and Preprocessing
- TF-IDF Feature Extraction
- Logistic Regression Classification
- Sentiment Confidence Scores
- Accuracy and F1-Score Evaluation
- Confusion Matrix Visualization
- Interactive CLI-Based Prediction

---

## Technology Stack

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- Matplotlib
- Seaborn

---

## Project Workflow

```text
Review Dataset
      ↓
Text Cleaning
      ↓
TF-IDF Vectorization
      ↓
Train-Test Split
      ↓
Logistic Regression
      ↓
Model Evaluation
      ↓
Sentiment Prediction
```

---

## Model Evaluation

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score


```text
Accuracy : 92.33%
```

---

## Future Improvements

- Multi-class Sentiment Classification (Positive, Neutral, Negative)
- Naive Bayes Model Comparison
- Support Vector Machine (SVM) Implementation
- Streamlit Web Application
- Transformer-Based Sentiment Analysis (BERT)

---
## Repository Structure

```text
Sentiment-Analysis-Tool/
│
├── data/
├── screenshots/
├── sentiment_analysis.ipynb
├── sentiment_analysis.py
├── requirements.txt
├── README.md
└── .gitignore
```
---

## Author

**Rakshit Chugh**

B.Tech CSE (AI Specialization)  
Bennett University

GitHub: https://github.com/RC0809

---

## License

This project is developed for educational and learning purposes.
