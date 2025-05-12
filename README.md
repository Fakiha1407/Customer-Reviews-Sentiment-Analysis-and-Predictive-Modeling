# Customer-Reviews-Sentiment-Analysis-and-Predictive-Modeling
This project analyzes customer feedback from a women’s e-commerce clothing dataset to uncover sentiment trends and build a machine learning model that classifies reviews as positive, neutral, or negative. By leveraging Natural Language Processing (NLP) techniques and supervised learning, the project aims to provide actionable insights into customer satisfaction and product feedback.

# Dataset
Source: Kaggle - Women's E-Commerce Clothing Reviews

Size: ~23,000 reviews

Key Columns:

Review Text (customer-written feedback)

Rating (integer scale: 1–5)

# Objectives
Perform data preprocessing and text cleaning on raw review data.

Conduct sentiment classification using text analytics and machine learning.

Train and evaluate multiple classification models (e.g., Logistic Regression, Naive Bayes, SVM).

Visualize review sentiment trends and feature importance.

Build an interpretable and efficient predictive model for sentiment analysis.

# Technologies Used
Python

Jupyter Notebook

Pandas, NumPy

NLTK, scikit-learn, TextBlob, WordCloud

Matplotlib, Seaborn

# # Methodology
# Data Cleaning & Preprocessing

Removed missing values, duplicates, and irrelevant entries.

Applied text preprocessing: tokenization, stopword removal, lemmatization.

# Exploratory Data Analysis (EDA)

Plotted word clouds and rating distributions.

Investigated relationships between review length, rating, and sentiment.

# Sentiment Labeling

Mapped ratings (1–2 = negative, 3 = neutral, 4–5 = positive).

# Model Building

Vectorized text using TF-IDF.

Trained models: Naive Bayes, Logistic Regression, and SVM.

Used cross-validation for model selection.

# Evaluation

Assessed accuracy, precision, recall, and F1-score.

Generated confusion matrices and classification reports.

