# Social Media Sentiment Analysis using NLP and Machine Learning

## Project Overview

This project analyzes social media sentiment data to understand public opinion and attitudes toward different brands and topics. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, natural language processing (NLP), and machine learning-based sentiment classification.

The goal is to identify whether a tweet expresses a Positive, Negative, Neutral, or Irrelevant sentiment.

---

## Problem Statement

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes toward specific topics or brands.

---

## Dataset Information

The dataset contains social media posts with the following attributes:

* ID
* Entity (Brand/Topic)
* Sentiment
* Tweet Text

### Sentiment Categories

* Positive
* Negative
* Neutral
* Irrelevant

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* WordCloud
* Scikit-learn

---

## Project Workflow

### 1. Data Cleaning

* Loaded dataset
* Renamed columns
* Checked missing values
* Removed duplicates

### 2. Exploratory Data Analysis

* Sentiment Distribution
* Sentiment Percentage Analysis
* Top Discussed Brands
* Brand-wise Sentiment Analysis
* Positive Brand Analysis
* Negative Brand Analysis
* Tweet Length Analysis

### 3. Data Visualization

* Count Plot
* Pie Chart
* Heatmap
* Bar Charts
* Word Cloud
* Confusion Matrix
* Accuracy Visualization

### 4. Natural Language Processing

* Text preprocessing
* TF-IDF Vectorization

### 5. Machine Learning

Model Used:

* Logistic Regression

---

## Model Performance

### Classification Accuracy

**Accuracy: ~70%**

### Classification Report Summary

| Sentiment  | Precision | Recall | F1-Score |
| ---------- | --------- | ------ | -------- |
| Irrelevant | 0.70      | 0.54   | 0.61     |
| Negative   | 0.71      | 0.81   | 0.76     |
| Neutral    | 0.69      | 0.64   | 0.66     |
| Positive   | 0.68      | 0.72   | 0.70     |

The model performs best on Negative sentiment classification and achieves an overall accuracy of approximately 70%.

---

## Key Insights

* Negative sentiment is the most common sentiment category.
* Positive sentiment also represents a significant portion of the dataset.
* Social media data provides valuable information about customer opinions.
* Sentiment analysis helps businesses monitor brand perception.
* NLP techniques can automate sentiment classification effectively.

---

## Conclusion

This project successfully analyzed social media sentiment using Natural Language Processing and Machine Learning techniques.

TF-IDF Vectorization and Logistic Regression were used to classify tweet sentiments. The model achieved approximately 70% accuracy and demonstrated the ability to identify sentiment patterns from social media text data.

The project can help organizations understand customer opinions, improve products and services, and support data-driven decision-making.

---

## Author

Dev Patel
Data Analytics
