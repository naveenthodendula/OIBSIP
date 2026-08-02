# 📱 Google Play Store Analysis

A comprehensive Exploratory Data Analysis (EDA) project on the Google Play Store ecosystem using Python. This project focuses on data cleaning, visualization, pricing trends, app ratings, install patterns, and sentiment analysis of user reviews to uncover valuable insights for developers and businesses.

---

## 📖 Project Overview

The Google Play Store hosts millions of applications across various categories. This project analyzes real-world Play Store data to understand app distribution, ratings, installs, pricing, and user sentiment. The objective is to identify trends and generate actionable insights that can help developers make informed decisions when launching or improving an application.

---

## 🎯 Objectives

* Load and analyze Google Play Store app and review datasets.
* Clean and preprocess messy real-world data.
* Analyze app categories, ratings, installs, pricing, and app size.
* Perform sentiment analysis on user reviews using TextBlob.
* Create informative visualizations using Matplotlib, Seaborn, and Plotly.
* Generate data-driven insights for app developers.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* TextBlob
* NLTK

---

## 📂 Dataset

The project uses the publicly available **Google Play Store Apps** dataset from Kaggle.

Files used:

* `googleplaystore.csv`
* `googleplaystore_user_reviews.csv`

---

## 📊 Project Workflow

### 1. Data Loading

* Imported Play Store applications dataset.
* Imported user reviews dataset.

### 2. Data Cleaning

* Removed duplicate records.
* Handled missing values.
* Corrected data types.
* Cleaned `Reviews`, `Installs`, `Price`, and `Size` columns.

### 3. Exploratory Data Analysis

* App distribution by category.
* Ratings distribution.
* Average rating by category.
* App size vs. installs relationship.
* Free vs. paid app analysis.
* Price distribution of paid apps.
* Estimated revenue by category.

### 4. Sentiment Analysis

* Classified user reviews using TextBlob.
* Categorized reviews into Positive, Neutral, and Negative.
* Analyzed sentiment across different app categories.

### 5. Interactive Visualization

* Built an interactive Plotly chart for category analysis.

---

## 📈 Key Insights

* **Family**, **Game**, and **Tools** are the most populated app categories, indicating high competition in these segments.
* The correlation between app size and installs is extremely weak, suggesting that app size has minimal influence on download count.
* Most user reviews exhibit positive sentiment, indicating generally high user satisfaction across popular applications.
* Free apps dominate the Play Store, while paid apps contribute significantly to estimated revenue in selected categories.

---

## 📁 Project Structure

```text
Google-Play-Store-Analysis/
│
├── dataset/
│   ├── googleplaystore.csv
│   └── googleplaystore_user_reviews.csv
│
├── Google_Play_Store_Analysis.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/naveenthodendula/Google-Play-Store-Analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
jupyter notebook
```

Open **Google_Play_Store_Analysis.ipynb** and run all cells sequentially.

---

## 📊 Visualizations Included

* App Distribution by Category
* Ratings Distribution
* Average Rating by Category
* App Size vs. Installs Scatter Plot
* Free vs. Paid Apps Pie Chart
* Paid App Price Distribution
* Estimated Revenue by Category
* Sentiment Distribution
* Positive Sentiment by Category
* Interactive Plotly Bar Chart
* Correlation Heatmap

---

## 🚀 Future Enhancements

* Build an interactive dashboard using Streamlit.
* Predict app ratings using machine learning.
* Perform topic modeling on user reviews.
* Add recommendation and trend analysis features.

---

## 👨‍💻 Author

**Naveen Thodendula**

---

## 🙏 Acknowledgements

* Kaggle for providing the Google Play Store datasets.
* The Python open-source community for the libraries used in this project.
