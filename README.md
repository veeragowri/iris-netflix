# 📊 Exploratory Data Analysis (EDA)  
## Iris Dataset & Netflix Movies and TV Shows Dataset

This repository contains a **combined Exploratory Data Analysis (EDA) project** performed on two popular datasets:

1. **Iris Dataset** – a classic machine learning dataset with numerical features  
2. **Netflix Movies and TV Shows Dataset** – a real-world dataset with categorical and numerical features  

The goal of this project is to **analyze data distributions, identify patterns, detect outliers, and extract meaningful insights** using Python.

---

## 📁 Datasets Used

### 🌸 Iris Dataset
- Source: `sklearn.datasets`
- Records: 150
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target Variable: Species (Setosa, Versicolor, Virginica)

### 🎬 Netflix Movies and TV Shows Dataset
- Source: Kaggle
- Records: 8,000+
- Features include:
  - Type (Movie / TV Show)
  - Release Year
  - Rating
  - Duration
  - Country
  - Genre

---

## 🎯 Objectives

- Plot **histograms** for numerical feature distributions  
- Analyze **categorical features** using count plots  
- Identify **outliers** using box plots  
- Understand feature relationships using **correlation heatmaps**  
- Extract **insights** from each visualization  
- Identify **important features for prediction**  
- Summarize findings clearly  

---

## 🛠️ Technologies & Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📌 Steps Performed

### 1️⃣ Data Loading
- Iris dataset loaded using `sklearn`
- Netflix dataset loaded from CSV file

### 2️⃣ Data Understanding
- Used `.info()` and `.head()` to inspect structure
- Checked for missing values and data types

### 3️⃣ Data Visualization
- Histograms for numerical distributions
- Count plots for categorical analysis
- Box plots for outlier detection
- Heatmaps for correlation analysis

### 4️⃣ Feature Importance Identification
- Iris: Petal length and petal width are strong predictors
- Netflix: Release year, content type, rating, and genre are influential

---

## 📊 Key Insights

### 🌸 Iris Dataset
- Dataset is clean and balanced
- Strong correlation between petal length and petal width
- Ideal for classification tasks
- Minimal outliers

### 🎬 Netflix Dataset
- Movies dominate the platform
- Majority of content released after 2015
- Older titles appear as outliers
- Requires preprocessing for machine learning

---

## 📂 Project Structure

EDA-Iris-Netflix
│
├── netflix_titles.csv
├── combined_eda.ipynb
├── README.md

---

## 🚀 How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/EDA-Iris-Netflix.git
📌 Future Enhancements

Add machine learning models (Logistic Regression, KNN, Random Forest)

Perform feature engineering on Netflix dataset

Deploy insights using Streamlit dashboard
