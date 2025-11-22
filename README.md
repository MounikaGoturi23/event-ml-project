# Event Classification and Recommendation System

This project implements a Natural Language Processing (NLP) pipeline to classify events into predefined categories and recommend relevant events based on user interests. It includes text preprocessing, machine learning model training, evaluation, and a content-based recommendation engine.

---

## 📌 Project Features

- Event classification into:
  - Technical
  - Cultural
  - Sports
  - Devotional
- NLP text preprocessing using TF-IDF
- Logistic Regression classification model
- Evaluation using Accuracy and F1-Score
- Content-based recommendation system using cosine similarity
- Confusion matrix visualization

---

## 📂 Dataset

- File: `events_dataset.csv`
- Size: **240** samples
- Each category contains **60** events
- Columns:
  - `title`
  - `description`
  - `category`

The dataset is synthetic and manually created for ML experimentation.

---

## 🛠 Technologies Used

| Component | Library |
|----------|---------|
| Language | Python |
| ML Model | Scikit-Learn |
| NLP Vectorization | TF-IDF |
| Similarity | Cosine Similarity |
| Visualization | Matplotlib |

---

## 🚀 How to Run

### 🔹 Option 1 — Google Colab

1. Upload:
   - `events_dataset.csv`
   - `event_classification_and_recommendation.ipynb`
2. Run all cells from top to bottom.

### 🔹 Option 2 — Local (Jupyter Notebook / VS Code)

1. Install dependencies:

