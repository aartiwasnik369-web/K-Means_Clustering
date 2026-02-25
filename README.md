# Task 8 - Clustering with K-Means

## 📌 Objective
Perform unsupervised learning using K-Means clustering on the Mall Customers dataset.

---

## 📂 Dataset
Mall Customers Dataset  
Features used:
- Annual Income (k$)
- Spending Score (1-100)

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔎 Steps Performed

### 1️⃣ Data Loading
- Loaded dataset using Pandas
- Checked first few rows
- Selected relevant features for clustering

### 2️⃣ Feature Selection
Used:
- Annual Income (k$)
- Spending Score (1-100)

### 3️⃣ Elbow Method
- Applied K-Means for K = 1 to 10
- Plotted Inertia vs Number of Clusters
- Found optimal K using elbow point

### 4️⃣ Model Building
- Applied K-Means with optimal K
- Assigned cluster labels to dataset

### 5️⃣ Visualization
- Plotted clusters using Matplotlib
- Displayed centroids

### 6️⃣ Model Evaluation
- Calculated Silhouette Score
- Evaluated cluster quality

---

## 📊 Results
- Optimal Number of Clusters: 5
- Silhouette Score: ~0.5 (approximate, may vary slightly)

---

## 🧠 Interview Questions Covered

1. How does K-Means clustering work?
2. What is the Elbow method?
3. What are the limitations of K-Means?
4. How does initialization affect results?
5. What is inertia in K-Means?
6. What is Silhouette Score?
7. How do you choose the right number of clusters?
8. Difference between clustering and classification

---

## 🎯 Learning Outcomes
- Understood unsupervised learning
- Learned K-Means clustering algorithm
- Learned how to evaluate clustering models
- Learned how to visualize clusters effectively

---

## 📁 Project Structure
```
Task-8-KMeans-Clustering/
│
├── Mall_Customers.csv
├── Task8_KMeans.ipynb
└── README.md
```

---

## 🚀 Conclusion
Successfully performed customer segmentation using K-Means clustering and evaluated the model using the Elbow Method and Silhouette Score.
