# 🏠 House Price Prediction using Linear Regression

## 📌 Overview

This project demonstrates an end-to-end Machine Learning workflow for predicting house prices using **Linear Regression**. The model is trained on the **Ames Housing Dataset**, which contains various features describing residential properties such as area, neighborhood, number of rooms, construction year, garage details, and more.

The project covers the complete pipeline from **data exploration and preprocessing** to **model training, evaluation, visualization, and interpretation**.

---

## 🎯 Project Objectives

* Perform Exploratory Data Analysis (EDA)
* Handle missing values
* Encode categorical variables using One-Hot Encoding
* Identify important features through correlation analysis
* Train a Linear Regression model
* Evaluate model performance using standard regression metrics
* Visualize predictions and residuals
* Analyze feature coefficients
* Compare Linear Regression with Ridge Regression

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── dataset/
│   └── (Download train.csv from Kaggle)
│
├── House_Price_Prediction_Linear_Regression.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

This project uses the **House Prices: Advanced Regression Techniques** dataset from Kaggle.

The dataset contains **1,460 residential properties** with **81 attributes**, including the target variable:

* **Target Variable:** `SalePrice`

### Key Features

* Overall Quality
* Living Area
* Lot Area
* Number of Rooms
* Garage Capacity
* Basement Area
* Construction Year
* Neighborhood
* Exterior Quality
* Foundation Type
* and many more...

> **Note:** The dataset is not included in this repository. Download `train.csv` from Kaggle and place it inside the `dataset/` folder before running the notebook.

---

## 🔍 Exploratory Data Analysis

The project includes:

* Dataset inspection
* Descriptive statistics
* Missing value analysis
* Target variable distribution
* Correlation heatmap
* Feature relationship analysis

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

* Median imputation for numerical features
* Most frequent value imputation for categorical features
* One-Hot Encoding for categorical variables
* Automatic preprocessing using Scikit-learn Pipelines

---

## 🤖 Machine Learning Model

### Linear Regression

The primary regression model was developed using Scikit-learn's `LinearRegression`.

### Bonus Model

* Ridge Regression

Both models were trained using an **80:20 Train-Test Split**.

---

## 📈 Model Evaluation

The following evaluation metrics were used:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### Results

| Metric                         |          Value |
| ------------------------------ | -------------: |
| Mean Squared Error (MSE)       | 980,045,047.32 |
| Root Mean Squared Error (RMSE) |      31,305.67 |
| R² Score                       |     **0.8722** |

The Linear Regression model explains approximately **87% of the variance** in house prices, demonstrating strong predictive performance.

---

## 📉 Visualizations

The notebook includes:

* House Price Distribution
* Correlation Heatmap
* Actual vs Predicted Scatter Plot
* Residual Plot
* Coefficient Analysis

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
```

### 2. Navigate to the project directory

```bash
cd House-Price-Prediction
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Download the dataset

Download the **House Prices: Advanced Regression Techniques** dataset from Kaggle and place the `train.csv` file inside the `dataset/` folder.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
House_Price_Prediction_Linear_Regression.ipynb
```

and run all cells.

---

## 📚 Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* jupyter

---

## 📌 Future Improvements

* Feature Engineering
* Hyperparameter Tuning
* Lasso Regression
* ElasticNet Regression
* Random Forest Regressor
* XGBoost Regressor
* Model Deployment using Flask or FastAPI

---

## 📄 License

This project is intended for educational, learning, and portfolio purposes.

---

## 👨‍💻 Author

**Naveen Thodendula**

If you found this project useful, consider giving the repository a ⭐ to support the work.
