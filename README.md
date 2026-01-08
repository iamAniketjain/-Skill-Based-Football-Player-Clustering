
<img width="1085" height="722" alt="Screenshot 2026-01-08 194725" src="https://github.com/user-attachments/assets/f8a93780-bd63-4c04-99a0-f9159a25da5e" />


<p align="center">
  <img src="https://img.shields.io/badge/Football%20Player%20Clustering-Unsupervised%20Machine%20Learning-blue?style=for-the-badge&logo=python&logoColor=white" />
</p>

<p align="center">
  <b>PCA • KMeans • Hierarchical Clustering • EDA • Feature Engineering • Sports Analytics</b>
</p>



# ⚽ Skill-Based Football Player Clustering

## 📌 Project Overview
This project focuses on **segmenting football players based on their skill attributes** using **unsupervised machine learning techniques** applied to the FIFA 20 dataset.  
The goal is to identify meaningful player groups that share similar technical, physical, and tactical characteristics, enabling insights for **player profiling, talent identification, and recruitment analysis**.

---

## 🎯 Objectives
- Perform detailed **Exploratory Data Analysis (EDA)** on FIFA 20 player data  
- Preprocess data by handling missing values, outliers, and correlated features  
- Reduce dimensionality using **Principal Component Analysis (PCA)**  
- Cluster players based on skills using **KMeans and Hierarchical Clustering**  
- Compare clustering models and select the most suitable one  

---

## 📂 Dataset
- **Source:** FIFA 20 Player Dataset  
- **Type:** Sports Analytics  
- **Data Includes:**  
  - Player demographics (age, height, nationality)  
  - Technical skills (passing, dribbling, shooting, defending)  
  - Physical attributes (strength, stamina, agility)  
  - Positional and performance-related attributes  

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn  
  - scipy  

---

## 🔍 Exploratory Data Analysis (EDA)
- Analyzed distributions of numerical features using histograms and boxplots  
- Identified skewness and outliers in performance and financial attributes  
- Examined feature ranges and scale differences  
- Removed highly correlated features to reduce redundancy  
- Derived insights to guide preprocessing and modeling  

---

## ⚙️ Data Preprocessing
- Removed identifier columns (IDs, URLs)  
- Handled missing values appropriately  
- Treated outliers using **IQR-based capping**  
- Applied **StandardScaler** to normalize feature scales  
- Reduced dimensionality using **PCA** to address multicollinearity  

---

## 🤖 Models Used
### Clustering Algorithms
- **KMeans (k = 5)** – Baseline clustering
- **KMeans (k = 4)** – Optimized based on silhouette score
- **Hierarchical Clustering** – For hierarchical structure analysis

---

## 📊 Model Evaluation Metrics
Since clustering is unsupervised, evaluation focused on:
- **Cluster Distribution**
- **Inertia (Cluster Compactness)**
- **Silhouette Score (Cluster Separation)**

---

## 🏆 Model Comparison Summary

| Model | No. of Clusters | Silhouette Score |
|------|----------------|------------------|
| KMeans (k=5) | 5 | Not Provided |
| KMeans (k=4) | 4 | 0.19 |
| Hierarchical Clustering | 5 | 0.14 |

---

## ✅ Final Model Selection
**KMeans with k = 4** was selected as the final model because:
- It achieved the **highest silhouette score**
- Provided better cluster separation
- Produced interpretable and balanced player segments
- Scales efficiently for large datasets

---

## 📈 Key Insights
- Players cluster naturally based on technical and physical skill combinations  
- PCA significantly improves clustering quality by reducing noise  
- Different clusters represent distinct player profiles such as:
  - Technically skilled attackers  
  - Physically strong players  
  - Balanced all-rounders  

---

## ⚠️ Challenges & Solutions

| Challenge | Solution |
|--------|---------|
| High dimensionality | Applied PCA |
| Feature scale imbalance | Used StandardScaler |
| Presence of outliers | IQR-based capping |
| Highly correlated features | Feature removal |
| Cluster selection | Silhouette score comparison |

---

## 📌 Conclusion
A complete **end-to-end unsupervised learning pipeline** was successfully implemented to cluster football players based on skill attributes.  
**KMeans (k=4)** emerged as the most effective model, offering meaningful segmentation and practical applicability in sports analytics.

---

## 🚀 Future Enhancements
- Cluster profiling with real player examples  
- Comparison across FIFA versions  
- Integration with scouting or recommendation systems  

---

## 👤 Author
**Aniket Jain**  
Data Analyst | Machine Learning Enthusiast  

