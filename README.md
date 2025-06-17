# 🍽️ Nourish - Food Recommendation System Using Data Science

This project uses a **custom Indian food dataset** to recommend whether a food item should be *Ideal*, *Limited*, or *Avoided* based on its nutritional values. It combines **Exploratory Data Analysis (EDA)**, **Dimensionality Reduction (PCA)**, **Clustering (K-Means)**, and **Classification (Random Forest)** to provide meaningful insights and predictions.

---

## 📁 Dataset

The dataset consists of 100+ Indian food items with features like:
- **Calories**, **Carbs**, **Fats**, **Protein**, **Fiber**
- **Glycemic Index (GI)**, **Glycemic Load (GL)**, **Insulin Index**
- **Micronutrients**: Magnesium, Potassium, Sodium, Calcium, Iron, Vitamin D, Vitamin C, Folate
- **Recommendation Tag**: *Ideal*, *Limited*, *Avoid*

> This is a **custom curated dataset** used for both web development (Nourish app) and data science analysis.

---

## 🔍 Project Objectives

- Understand nutritional patterns via **EDA**
- Reduce dimensions using **PCA**
- Identify food groups via **K-Means clustering**
- Build a predictive model using **Random Forest**
- Visualize feature importance and explainable results

---

## 🧪 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-Learn (`PCA`, `KMeans`, `RandomForestClassifier`)
- Jupyter Notebook

---

## 🚀 Steps Performed

### 1. Preprocessing
- Handled missing values
- Label-encoded categorical features
- Scaled data using `StandardScaler`

### 2. Exploratory Data Analysis
- Histograms of all nutritional features
- Correlation heatmaps

### 3. Dimensionality Reduction - PCA
- Reduced 16 features to 2 principal components
- Visualized PCA components by food recommendation

### 4. Clustering - KMeans
- Used Elbow Method to find optimal clusters (K=4)
- Grouped similar food items

### 5. Classification - Random Forest
- Predicted the `recommendation` label
- Achieved reasonable accuracy despite limited data
- Evaluated using classification report and confusion matrix

---

## 📊 Results

- PCA revealed patterns in foods with high/low glycemic impact
- KMeans clustered foods based on macro and micro nutrients
- Random Forest predicted food categories with decent precision & recall
- Feature importance showed key nutritional factors behind recommendations

---
