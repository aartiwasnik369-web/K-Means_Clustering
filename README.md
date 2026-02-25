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

 Difference between clustering and classification

---

## 🎯 Learning Outcomes
- Understood unsupervised learning
- Learned K-Means clustering algorithm
- Learned how to evaluate clustering models
- Learned how to visualize clusters effectively

---

## 🚀 Conclusion
Successfully performed customer segmentation using K-Means clustering and evaluated the model using the Elbow Method and Silhouette Score.
