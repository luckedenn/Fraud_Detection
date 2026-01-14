# 🔍 Fraud Detection - Bank Transactions Analysis

Proyek machine learning untuk mendeteksi dan menganalisis transaksi mencurigakan dalam data perbankan menggunakan teknik clustering dan klasifikasi.

---

## 📋 Daftar Isi

- [Deskripsi Proyek](#deskripsi-proyek)
- [Struktur File](#struktur-file)
- [Dataset](#dataset)
- [Model & Analisis](#model--analisis)
- [Cara Menggunakan](#cara-menggunakan)
- [Persyaratan](#persyaratan)
- [Hasil & Insights](#hasil--insights)

---

## 📌 Deskripsi Proyek

Proyek ini menganalisis data transaksi bank dengan dua pendekatan utama:

1. **Clustering** - Mengelompokkan transaksi berdasarkan pola dan karakteristik untuk menemukan kelompok perilaku yang serupa
2. **Klasifikasi** - Mengklasifikasikan transaksi sebagai legitimate atau fraudulent menggunakan supervised learning

Tujuan akhir adalah mengidentifikasi dan memahami pola transaksi mencurigakan untuk meningkatkan keamanan sistem perbankan.

---

## 📁 Struktur File

```
Fraud_Detection/
├── [Clustering]_Submission_Akhir_BMLP_Lucas_Chandra.ipynb
│   └── Analisis clustering dengan berbagai algoritma
├── [Klasifikasi]_Submission_Akhir_BMLP_Lucas_Chandra.ipynb
│   └── Model klasifikasi untuk deteksi fraud
├── bank_transactions_data.csv
│   └── Dataset mentah transaksi bank
├── bank_transactions_clustered.csv
│   └── Dataset dengan hasil clustering
└── README.md
    └── File dokumentasi ini
```

---

## 📊 Dataset

### bank_transactions_data.csv

Dataset asli berisi informasi transaksi bank dengan fitur-fitur seperti:

- Informasi pelanggan
- Detail transaksi
- Nilai dan tipe transaksi
- Label fraud/legitimate (jika ada)

### bank_transactions_clustered.csv

Dataset hasil clustering yang sudah diproses dan dilabeli dengan cluster assignment.

---

## 🤖 Model & Analisis

### 1. Clustering Analysis

**File:** `[Clustering]_Submission_Akhir_BMLP_Lucas_Chandra.ipynb`

Metode yang digunakan:

- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- Analisis optimal number of clusters

### 2. Classification Analysis

**File:** `[Klasifikasi]_Submission_Akhir_BMLP_Lucas_Chandra.ipynb`

Algoritma yang diimplementasikan:

- Logistic Regression
- Random Forest
- Gradient Boosting
- Model evaluation & comparison

---

## 🚀 Cara Menggunakan

1. **Persiapan Data**

   ```bash
   # Load dataset
   import pandas as pd
   data = pd.read_csv('bank_transactions_data.csv')
   ```

2. **Jalankan Jupyter Notebook**

   ```bash
   # Buka notebook clustering
   jupyter notebook "[Clustering]_Submission_Akhir_BMLP_Lucas_Chandra.ipynb"

   # Buka notebook klasifikasi
   jupyter notebook "[Klasifikasi]_Submission_Akhir_BMLP_Lucas_Chandra.ipynb"
   ```

3. **Analisis Output**
   - Lihat visualisasi clustering di notebook pertama
   - Analisis performa klasifikasi di notebook kedua
   - Gunakan hasil di `bank_transactions_clustered.csv`

---

## ⚙️ Persyaratan

```
Python 3.7+
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

Instalasi:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

---

## 📈 Hasil & Insights

Proyek ini menghasilkan:

✅ **Cluster Insights**

- Pola transaksi yang teridentifikasi
- Karakteristik setiap cluster
- Distribusi transaksi normal vs anomali

✅ **Classification Metrics**

- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

✅ **Rekomendasi**

- Strategi deteksi fraud yang optimal
- Threshold classification yang ideal
- Integrasi dengan sistem keamanan

---

## 👤 Author

Lucas Chandra

---

## 📝 Notes

- Dataset yang digunakan adalah data transaksi bank
- Model telah divalidasi dengan proper train-test split
- Hyperparameter telah dioptimasi untuk performa terbaik

---
