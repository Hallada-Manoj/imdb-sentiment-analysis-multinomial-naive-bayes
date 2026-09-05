# 🎬 IMDB Sentiment Analysis using Multinomial Naive Bayes

## 📌 Project Overview

This project focuses on binary sentiment classification of movie reviews using the **IMDB Movie Reviews Dataset**. The objective is to classify reviews as **Positive** or **Negative** using **Natural Language Processing (NLP)** techniques and the **Multinomial Naive Bayes** algorithm.

The project demonstrates an end-to-end machine learning workflow including text preprocessing, TF-IDF vectorization, hyperparameter tuning using GridSearchCV, pipeline creation, model training, and evaluation.

---

# 🎯 Problem Statement

Develop a machine learning model capable of automatically predicting whether a movie review expresses **positive** or **negative** sentiment based on its textual content.

---

# 📂 Dataset

**Dataset:** IMDB Movie Reviews Dataset

- Total Reviews: **50,000**
- Target Variable: **Sentiment**

| Class | Description |
|--------|-------------|
| Positive | Positive Movie Review |
| Negative | Negative Movie Review |

> **Note:** The dataset is **not included** in this repository due to its large file size. It can be downloaded from the **Kaggle IMDB Movie Reviews Dataset** and placed in the project directory before running the notebook.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes
- GridSearchCV
- Pipeline
- Jupyter Notebook

---

# ⚙️ Machine Learning Workflow

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Train-Test Split
- TF-IDF Feature Extraction
- Pipeline Creation
- Hyperparameter Tuning using GridSearchCV
- Model Training
- Prediction
- Model Evaluation

---

# 🔍 Hyperparameter Tuning

GridSearchCV was used to optimize the Multinomial Naive Bayes model.

### Best Parameter

| Parameter | Value |
|-----------|------:|
| TF-IDF max_features | **4000** |

---

# 📊 Model Performance

| Metric | Score |
|---------|------:|
| Training Accuracy | **86.03%** |
| Testing Accuracy | **85.11%** |
| Weighted Precision | **0.85** |
| Weighted Recall | **0.85** |
| Weighted F1 Score | **0.85** |

The small difference between training and testing accuracy indicates that the model generalizes well on unseen movie reviews.

---

# 📈 Evaluation

The project includes:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

### Classification Report

| Class | Precision | Recall | F1-Score |
|--------|:---------:|:------:|:--------:|
| Negative | **0.85** | **0.84** | **0.85** |
| Positive | **0.85** | **0.86** | **0.85** |

**Overall Accuracy:** **85.11%**

---

# 📉 Confusion Matrix

| | Predicted Negative | Predicted Positive |
|----------------------|-------------------:|-------------------:|
| **Actual Negative** | **4192** | **769** |
| **Actual Positive** | **720** | **4319** |

The confusion matrix demonstrates balanced prediction performance across both sentiment classes.

---

# 📁 Repository Structure

```text
imdb-sentiment-analysis-multinomial-naive-bayes/
│
├── README.md
├── requirements.txt
└── imdb-sentiment-analysis-multinomial-naive-bayes.ipynb
```

---

# 📈 Key Insights

- Built a complete NLP pipeline for binary sentiment classification.
- Applied TF-IDF vectorization to convert text into numerical features.
- Optimized the model using GridSearchCV.
- Achieved balanced performance across positive and negative sentiment classes.
- Demonstrated the effectiveness of Multinomial Naive Bayes for text classification.

---

# 💡 Future Improvements

- Compare Multinomial Naive Bayes with Logistic Regression, Support Vector Classifier (SVC), and Random Forest.
- Experiment with Word2Vec, FastText, and GloVe embeddings.
- Fine-tune transformer-based models such as BERT.
- Deploy the trained model using Streamlit or Flask.

---

# 🏆 Conclusion

This project successfully demonstrates a complete Natural Language Processing (NLP) workflow for binary sentiment classification using **Multinomial Naive Bayes**.

### Key Achievements

- End-to-end NLP pipeline
- TF-IDF feature extraction
- Hyperparameter tuning using GridSearchCV
- Balanced classification performance
- Good model generalization
- **85.11% Test Accuracy**

The project showcases practical implementation of text preprocessing, feature engineering, machine learning model optimization, and evaluation techniques commonly used in real-world sentiment analysis applications.

---

## 📄 License

This project is created for learning and portfolio purposes.
