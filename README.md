# 🧠 Amazon User Segmentation

This project uses unsupervised learning (KMeans and DBSCAN) to segment Amazon users based on behavioral data. It demonstrates how clustering techniques can be applied to personalize marketing and improve user engagement.

---

## 📌 Problem Statement

Amazon handles millions of users, making it difficult to understand distinct customer behaviors. Without segmentation, it’s challenging to offer personalized experiences.

---

## 🚀 Solution

We used clustering algorithms (KMeans, DBSCAN) to segment users based on:
- Purchase history
- Browsing behavior
- Demographics
- Category preferences

This helps in building targeted marketing campaigns and improving recommendations.

---

## 🛠️ Tech Stack

| Area | Tools |
|------|-------|
| Language | Python |
| IDE | Google Colab / Jupyter |
| Libraries | Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib |
| Algorithms | KMeans, DBSCAN |
| Visualization | PCA, Boxplots, Heatmaps |
| Version Control | Git + GitHub |

---

## 📊 Features Engineered

- `TotalSpend`, `AvgOrderValue`, `TotalOrders`
- `BrowsingTime`, `Category_Clothing`, etc.
- Normalized features using StandardScaler

---

## 📈 Clustering Approach

- Used **Elbow Method** to find optimal K
- Applied **KMeans** and evaluated with **Silhouette Score**
- Visualized clusters using **PCA**

---

## 🧠 User Segments Identified

1. **High Spenders**
2. **Frequent Shoppers**
3. **Browsers**
4. **Low Activity Users**

Each cluster was interpreted and labeled based on behavior patterns.

---

## 📝 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/amazon-user-segmentation.git
