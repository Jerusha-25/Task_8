# 📊 K-Means Clustering: Customer Segmentation

## 🧠 Objective
Perform **unsupervised learning** using the **K-Means clustering** algorithm to segment customers based on `Annual Income` and `Spending Score`. This helps in identifying customer groups for personalized marketing strategies.

---

## 🧰 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Dataset Information
This dataset is collected via supermarket mall membership cards and includes the following features:

- `CustomerID`  
- `Gender`  
- `Age`  
- `Annual Income (k$)`  
- `Spending Score (1–100)`

> ℹ️ **Spending Score** is a value assigned based on customer behavior and purchasing data.

---

## 🔍 Steps Performed

1. **Data Loading & Exploration**
   - Loaded the dataset with Pandas
   - Explored data through descriptive statistics

2. **Feature Selection**
   - Focused on `Annual Income` and `Spending Score` for clustering

3. **Optimal K Selection**
   - Used the **Elbow Method** to determine the ideal number of clusters

4. **Model Training**
   - Applied **K-Means** clustering
   - Assigned cluster labels to the data

5. **Cluster Visualization**
   - Plotted the clusters using Seaborn and Matplotlib

6. **Evaluation**
   - Calculated **Silhouette Score** to measure clustering performance

---

## 📈 Results
- Chosen number of clusters: **5**
- Segments show clear separation of customer behavior
- Suitable for applying targeted marketing or promotions

---


