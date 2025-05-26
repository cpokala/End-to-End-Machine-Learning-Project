# 🏠 End-to-End Machine Learning: California Housing Price Prediction

This project demonstrates a complete machine learning workflow to predict California housing prices using real-world data. It covers every essential step in building a robust ML system—from data ingestion to final model evaluation.

---

## 📌 Project Overview

The notebook walks through the following stages:

### 📥 Data Collection
- Downloads and extracts `housing.tgz` dataset from [ageron/data](https://github.com/ageron/data)
- Loads CSV into a DataFrame using `pandas`

### 🧹 Data Exploration & Preprocessing
- Basic EDA with `.head()`, `.describe()`, and `.info()`
- Frequency analysis of categorical features like `ocean_proximity`
- Histograms and distribution analysis

### 🧪 Train-Test Splitting
- Implements both random and hash-based test splits for reproducibility
- Explanation of the pros/cons of each method

### 📊 Data Visualization
- Uses `matplotlib` to create histograms for numerical features
- Observations about skewed distributions and capped values

### 🔧 Feature Engineering (Planned or Executed)
- Fixing skewness
- Handling capped or non-standardized features
- Encoding categorical variables

### 🤖 Modeling (Coming soon or partially done)
- Placeholder for regression model training (Linear Regression, Decision Trees, etc.)

---

## 🗂 Dataset

- **Source:** [Housing Dataset](https://github.com/ageron/data/raw/main/housing.tgz)
- **Features Include:**
  - Median income
  - Housing median age
  - Median house value
  - Location-based proximity to the ocean

---

## 🧰 Dependencies

Install the required packages with:

```bash
pip install pandas numpy matplotlib scikit-learn
```
or 

```bash
pip install -r requirements.txt
```

##💬 Acknowledgements
Géron, Aurélien. Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow

Dataset from: https://github.com/ageron/data
