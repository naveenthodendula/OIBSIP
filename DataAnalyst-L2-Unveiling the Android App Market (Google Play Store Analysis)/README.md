\# 📱 Google Play Store Analysis



\## 📌 Project Overview



This project performs a comprehensive Exploratory Data Analysis (EDA) of the Google Play Store ecosystem using Python. The analysis includes data cleaning, visualization, pricing trends, ratings analysis, install patterns, and sentiment analysis of user reviews to uncover meaningful insights for developers and businesses.



\---



\## 🎯 Objectives



\* Load and analyze Google Play Store apps and user reviews datasets.

\* Clean and preprocess real-world messy data.

\* Explore app categories, ratings, installs, pricing, and app size.

\* Perform sentiment analysis on user reviews using \*\*TextBlob\*\*.

\* Visualize findings using \*\*Matplotlib\*\*, \*\*Seaborn\*\*, and \*\*Plotly\*\*.

\* Generate actionable insights for developers planning to launch new applications.



\---



\## 🛠️ Technologies Used



\* Python

\* Jupyter Notebook

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Plotly

\* TextBlob

\* NLTK



\---



\## 📂 Dataset



This project uses the publicly available \*\*Google Play Store Apps\*\* dataset from Kaggle.



Datasets used:



\* `googleplaystore.csv`

\* `googleplaystore\_user\_reviews.csv`



\---



\## 📊 Project Workflow



\### 1. Data Loading



\* Imported the apps dataset.

\* Imported the user reviews dataset.



\### 2. Data Cleaning



\* Removed duplicate records.

\* Handled missing values.

\* Converted incorrect data types.

\* Cleaned the `Installs`, `Price`, `Reviews`, and `Size` columns.



\### 3. Exploratory Data Analysis



\* Distribution of apps by category.

\* Ratings distribution.

\* Average rating by category.

\* Relationship between app size and installs.

\* Free vs Paid app comparison.

\* Price distribution of paid apps.

\* Estimated revenue by category.



\### 4. Sentiment Analysis



\* Performed sentiment analysis using \*\*TextBlob\*\*.

\* Classified reviews into Positive, Neutral, and Negative.

\* Analyzed sentiment across different app categories.



\### 5. Interactive Visualization



\* Created an interactive Plotly visualization for app category analysis.



\---



\## 📈 Key Insights



\* \*\*Family\*\*, \*\*Game\*\*, and \*\*Tools\*\* are the most populated app categories, indicating high competition.

\* The correlation between app size and installs is very weak, suggesting app size has little impact on download count.

\* Most user reviews show positive sentiment, indicating generally high user satisfaction across popular applications.



\---



\## 📁 Project Structure



```text

Google-Play-Store-Analysis/

│

├── dataset/

│   ├── googleplaystore.csv

│   └── googleplaystore\_user\_reviews.csv

│

├── Google\_Play\_Store\_Analysis.ipynb

├── requirements.txt

└── README.md

```



\---



\## ▶️ How to Run



1\. Clone this repository.



2\. Install the required libraries:



```bash

pip install -r requirements.txt

```



3\. Open the Jupyter Notebook:



```bash

jupyter notebook

```



4\. Run all notebook cells from top to bottom.



\---



\## 📌 Future Improvements



\* Build an interactive dashboard using Streamlit or Dash.

\* Apply machine learning models to predict app ratings or installs.

\* Perform topic modeling on user reviews for deeper insights.

\* Develop recommendation systems based on app categories and user preferences.



\---



\## 👨‍💻 Author



\*\*Naveen Thodendula\*\*



\---



\## ⭐ Acknowledgements



\* Kaggle for providing the Google Play Store datasets.

\* Python open-source community for the libraries used in this project.



