# 🏦 Bank Customer Segmentation and Classification

Clustering and classifying bank customers based on transaction data using unsupervised and supervised learning techniques.

## 📁 Project Structure
```
├── Dataset_clustering.csv # Dataset for clustering process
├── Dataset_klasifikasi.csv # Dataset for classification based on cluster results
├── [Clustering]_Submission_Akhir_BMLP_Trisya_Nurmayanti.ipynb # Clustering analysis notebook
├── [Klasifikasi]_Submission_Akhir_BMLP_Trisya Nurmayanti.ipynb # Classification modeling notebook
```


## 🧾 Project Overview

This project involves segmenting bank customers using clustering techniques and then building a classification model based on those segments. The clustering includes pure clustering, optimization with the Elbow Method, and improvements through feature engineering.

## 🔄 Workflow

1. **Clustering Phase**
   - Perform basic clustering using `Dataset_clustering.csv`
   - Optimize cluster number using the Elbow Method
   - Apply feature engineering for improved segmentation

2. **Classification Phase**
   - Use `Dataset_klasifikasi.csv` containing cluster labels
   - Build classification models to predict customer segments
   - Evaluate using metrics such as accuracy, precision, recall, and F1-score

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
