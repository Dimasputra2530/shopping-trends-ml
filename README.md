# 📊 Prediksi Penjualan Barang - Decision Tree vs Random Forest

Project ini menggunakan dataset **Shopping Trends Updated** dari Kaggle untuk memprediksi penjualan barang.  
Model yang diuji: **Decision Tree Regressor** dan **Random Forest Regressor**.

---

## 🚀 Dataset
- Sumber: [Shopping Trends Updated - Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/shopping-trends-dataset)
- Jumlah data: 3,900 baris × 140 fitur  
- Fitur mencakup informasi: harga, diskon, kategori produk, metode pembayaran, dll.

---

## ⚙️ Teknologi
- Python 3.13
- scikit-learn
- pandas, numpy
- matplotlib, seaborn


## 📈 Hasil Model

| Model           | R²   | RMSE |
|-----------------|------|------|
| Decision Tree   | 0.65 | 0.52 |
| Random Forest   | 0.89 | 0.29 |

➡️ Random Forest terbukti lebih akurat dan stabil dalam memprediksi penjualan dibandingkan Decision Tree.  
Fitur seperti **harga** dan **diskon** menjadi faktor dominan.

---

## 🔍 Visualisasi
Contoh visualisasi *feature importance*:

![Feature Importance](images/feature_importance.png)

---

## 📌 Langkah Eksekusi
1. Clone repo ini
   ```bash
   git clone https://github.com/username/shopping-trends-ml.git
   cd shopping-trends-ml
