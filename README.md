# yuva-intern-internship-datscience
DATA SCIENCE INTERNSHIP FROM YUVA INTERN
# 🍷 Red Wine Quality — Exploratory Data Analysis

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) and data preprocessing of the **Red Wine Quality Dataset** as part of my internship at **Yuva Intern**, working in the domain of **Data Science – Food Processing**.

The objective is to understand the dataset's structure, identify data quality issues, analyze the distributions of physicochemical properties, investigate relationships between features and wine quality, and explore preprocessing techniques for future machine learning applications.

## 🎯 Objectives

- Understand the dataset structure, features, and target variable.
- Perform data quality checks for missing values, duplicate records, and data types.
- Conduct univariate, bivariate, and multivariate analysis.
- Visualize feature distributions using histograms, box plots, scatter plots, and correlation heatmaps.
- Detect potential outliers using the Interquartile Range (IQR) method.
- Analyze relationships between physicochemical properties and wine quality.
- Learn and explore preprocessing techniques, including feature scaling and categorical encoding.
- Prepare for subsequent machine learning model development.

## 📊 Dataset

- **Dataset:** Red Wine Quality Dataset
- **Source:** UCI Machine Learning Repository
- **File:** `winequality-red.csv`
- **Target variable:** `quality`
- **Number of input features:** 11 physicochemical properties
- **Number of records:** 1,599

The dataset contains physicochemical measurements such as alcohol, volatile acidity, citric acid, residual sugar, chlorides, sulphates, density, and pH, along with a quality score assigned to each wine sample.

Dataset source: [UCI Red Wine Quality Dataset](https://archive.ics.uci.edu/dataset/186/wine+quality)

## 🛠️ Technologies and Libraries

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Work Performed

### 1. Data Inspection
- Viewed sample records using `head()`.
- Examined dataset dimensions using `shape`.
- Inspected column names, data types, and non-null counts using `info()`.
- Generated descriptive statistics using `describe()`.

### 2. Data Quality Assessment
- Checked missing values.
- Identified duplicate records.
- Examined data types and numerical summaries.
- Investigated potential outliers using the IQR method.

### 3. Univariate Analysis
- Analyzed individual feature distributions.
- Created histograms and box plots.
- Examined the distribution of wine quality scores.
- Investigated skewness and descriptive statistics.

### 4. Bivariate Analysis
- Explored relationships between individual physicochemical properties and wine quality.
- Used scatter plots and grouped box plots.
- Compared median feature values across wine quality categories.

### 5. Multivariate Analysis
- Calculated feature correlations.
- Visualized relationships using correlation heatmaps and pair plots.
- Examined patterns among multiple physicochemical variables.

### 6. Preprocessing Exploration
- Studied the IQR-based outlier detection technique.
- Explored `StandardScaler`, `MinMaxScaler`, and `RobustScaler`.
- Learned categorical encoding techniques, including `LabelEncoder`, `OrdinalEncoder`, and one-hot encoding.
- Examined train-test splitting and the importance of preventing data leakage.

## 📈 Key Findings

- Wine quality scores are concentrated primarily around 5 and 6.
- Alcohol content shows a positive correlation with wine quality, with a Pearson correlation of approximately **0.476**.
- Volatile acidity shows a negative correlation with wine quality, with a Pearson correlation of approximately **−0.391**.
- Sulphates and citric acid show positive correlations with quality.
- Density and total sulfur dioxide show negative correlations with quality.
- The IQR method identifies potential outliers in several features; these require investigation before any removal or transformation.
- Correlation indicates association, not causation, and individual features do not perfectly determine wine quality.

## 📂 Project Structure

```text
red-wine-quality-eda/
│
├── README.md
├── winequality-red.csv
└── Red_Wine_Quality_EDA.ipynb
```

*The notebook and dataset filenames should match the files actually uploaded to the repository.*

## 🚀 How to Run

1. Clone or download this repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Install the required libraries if necessary:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. Place `winequality-red.csv` in the expected location.
5. Run the notebook cells sequentially to reproduce the analysis.

**Note:** The dataset is semicolon-separated. When loading the CSV file, use:

```python
import pandas as pd

df = pd.read_csv("winequality-red.csv", sep=";")
```

## 🔮 Future Scope

- Develop regression models to predict wine quality scores.
- Explore classification approaches using quality categories.
- Compare models using appropriate evaluation metrics.
- Apply preprocessing through leakage-safe machine learning pipelines.
- Perform feature selection and hyperparameter tuning.
- Evaluate model performance on unseen data.

## 🎓 Learning Outcomes

This project strengthened my understanding of exploratory data analysis, statistical summaries, data visualization, outlier detection, feature relationships, and foundational preprocessing techniques. It also helped me understand how exploratory findings inform later machine learning decisions.

## 👨‍💻 Internship

**Organization:** Yuva Intern  
**Role:** Junior Data Scientist  
**Domain:** Food Processing  
**Project:** Red Wine Quality — Exploratory Data Analysis and Preprocessing

---

*This project is part of my learning journey in Data Science and Machine Learning.*
