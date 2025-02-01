
📊 Advanced Clustering Techniques for RFM Ranking: K-Means, Fuzzy C-Means & Feature Engineering

🚀 Project Overview

This project focuses on unsupervised learning for customer segmentation, using K-Means and Fuzzy C-Means (FCM) clustering on Recency, Frequency, and Monetary (RFM) analysis.

By leveraging Box-Cox transformation and feature engineering, this project enhances clustering accuracy for customer ranking and segmentation.

The approach is inspired by the research paper:

📄 [Customer Segmentation Using K-Means and RFM Analysis](https://www.sciencedirect.com/science/article/pii/S1319157818304178)


🔥 Key Features & Techniques:

✔ RFM Segmentation: Ranking customers based on Recency, Frequency, and Monetary values

✔ K-Means Clustering: Hard clustering for customer groups

✔ Fuzzy C-Means Clustering: Soft clustering, allowing customers to belong to multiple clusters

✔ Box-Cox Transformation: Data normalization for better clustering performance

✔ Feature Engineering: Enhancing input variables for optimal clustering

✔ Python-powered: NumPy, Pandas, Matplotlib, Scikit-Learn, and Fuzzy C-Means



📌 Why RFM Analysis?

RFM Analysis is a widely used technique in customer segmentation that helps businesses understand customer behavior and target them efficiently:

Recency (R) → How recently a customer made a purchase

Frequency (F) → How often a customer makes purchases

Monetary Value (M) → Total amount spent by a customer

Applying clustering algorithms to RFM values allows businesses to identify high-value customers, churn risks, and potential marketing targets.

📂 Project Structure:

## 📂 Project Structure
```plaintext
📁 clusteringkmeans  
 ┣ 📜 clustering_kmeans.py        # K-Means clustering implementation  
 ┣ 📜 clustering_fuzzy.py         # Fuzzy C-Means clustering  
 ┣ 📜 feature_engineering.py      # Preprocessing & transformations  
 ┣ 📜 boxcox_transformation.py    # Box-Cox normalization  
 ┣ 📜 data_visualization.py       # 3D & 2D visualizations  
 ┗ 📜 README.md                   # This file  
