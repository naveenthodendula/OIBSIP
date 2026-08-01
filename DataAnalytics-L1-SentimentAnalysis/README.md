# Sentiment Analysis using Machine Learning

## 📌 Overview

This project implements a **Sentiment Analysis** system using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The model classifies Twitter text into **Positive**, **Negative**, and **Neutral** sentiments. The project demonstrates the complete NLP pipeline, from text preprocessing to model evaluation and visualization.

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (Task 4)**.

---

## 🎯 Objective

To build a machine learning model capable of automatically predicting the sentiment of textual data, enabling organizations to analyze customer opinions, social media discussions, and public feedback efficiently.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- WordCloud

---

## 📂 Dataset

**Dataset:** Twitter Entity Sentiment Analysis Dataset

The dataset contains tweets labeled into four categories:
- Positive
- Negative
- Neutral
- Irrelevant

For this project, the **Irrelevant** class was removed, and the model was trained only on:

- Positive
- Negative
- Neutral

---

## ⚙️ Project Workflow

1. Load and inspect the dataset
2. Analyze sentiment distribution
3. Perform text preprocessing
   - Lowercase conversion
   - Remove URLs
   - Remove mentions
   - Remove punctuation
   - Stopword removal
   - Lemmatization
4. Convert text into numerical features using **TF-IDF Vectorization**
5. Split the dataset into Training (80%) and Testing (20%)
6. Train multiple Machine Learning models
   - Multinomial Naive Bayes
   - Logistic Regression
7. Evaluate model performance
8. Generate visualizations
9. Perform error analysis
10. Draw conclusions

---

## 📊 Data Visualizations

The project includes:

- Sentiment Distribution Bar Chart
- Naive Bayes Confusion Matrix
- Logistic Regression Confusion Matrix
- Positive WordCloud
- Negative WordCloud
- Neutral WordCloud

---

## 🤖 Machine Learning Models

### 1. Multinomial Naive Bayes

A probabilistic classifier commonly used for text classification tasks.

**Accuracy:** **71.67%**

---

### 2. Logistic Regression

A supervised machine learning algorithm widely used for classification problems.

**Accuracy:** **75.55%**

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Multinomial Naive Bayes | **71.67%** |
| Logistic Regression | **75.55%** |

**Best Performing Model:** Logistic Regression

---

## 🔍 Text Preprocessing

The following preprocessing steps were performed:

- Convert text to lowercase
- Remove URLs
- Remove user mentions
- Remove punctuation
- Remove stopwords
- Lemmatize words

---

## 📌 TF-IDF Vectorization

TF-IDF (Term Frequency–Inverse Document Frequency) converts textual data into numerical feature vectors by assigning higher importance to informative words while reducing the impact of frequently occurring words.

---

## ❌ Error Analysis

Some tweets were misclassified due to:

- Very short text with insufficient context
- Ambiguous language
- Informal expressions
- Sarcasm and irony
- Context-dependent sentiment

---

## 📈 Results

- Successfully classified tweets into **Positive**, **Negative**, and **Neutral** sentiments.
- Logistic Regression outperformed Naive Bayes on this dataset.
- The preprocessing pipeline significantly improved model performance.

---

## 💡 Real-World Applications

- Customer Feedback Analysis
- Product Review Classification
- Social Media Monitoring
- Brand Reputation Analysis
- Public Opinion Mining
- Business Intelligence
- Market Research

---

## 📁 Project Structure

```
DataAnalytics-L1-SentimentAnalysis/
│
├── Sentiment_Analysis.ipynb
├── twitter_training.csv
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/naveenthodendula/OIBSIP.git
```

2. Open the project folder.

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open

```
Sentiment_Analysis.ipynb
```

and run all cells.

---

## 📜 License

This project was developed for educational purposes as part of the **Oasis Infobyte Data Analytics Internship**.

---

## 👨‍💻 Author

**Naveen Thodendula**

Data Analytics Intern — Oasis Infobyte
