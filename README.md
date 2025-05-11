# Klasifikasi Region Pelanggan Wholesale menggunakan Algoritma K-Nearest Neighbors (KNN)

Repositori ini berisi implementasi algoritma K-Nearest Neighbors (KNN) untuk klasifikasi pelanggan berdasarkan wilayah (Region) menggunakan data pembelian dari dataset Wholesale Customers. Proyek ini bertujuan untuk mengidentifikasi pola pembelian yang dapat digunakan untuk memprediksi wilayah asal pelanggan.

## 📊 Dataset

Dataset yang digunakan diambil dari kaggel "https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set", terdiri dari 440 data pelanggan grosir dengan informasi pengeluaran tahunan dalam berbagai kategori produk.

### Fitur Input:
- **Fresh**: Pengeluaran untuk produk segar
- **Milk**: Pengeluaran untuk susu
- **Grocery**: Pengeluaran untuk bahan kebutuhan pokok
- **Frozen**: Pengeluaran untuk makanan beku
- **Detergents_Paper**: Pengeluaran untuk deterjen dan kertas
- **Delicassen**: Pengeluaran untuk makanan jadi
- **Channel**: Jenis pelanggan

### Target Klasifikasi:
- **Region**: Wilayah pelanggan  
  - 1 = Lisbon  
  - 2 = Oporto  
  - 3 = Other Region

## 🎯 Tujuan Proyek

- Mengembangkan model klasifikasi menggunakan KNN untuk memprediksi region pelanggan.
- Mengukur performa model berdasarkan akurasi dan metrik evaluasi lainnya.
- Menggunakan pendekatan supervised learning terhadap data numerik multi-fitur.

## ⚙️ Teknologi dan Library

- Python 3.x
- Jupyter Notebook
- Pandas dan NumPy untuk manipulasi data
- Scikit-learn untuk pemodelan machine learning
- Matplotlib dan Seaborn untuk visualisasi

## 🔁 Alur Implementasi

1. **Eksplorasi Data**  
   Analisis distribusi, korelasi antar fitur, dan deteksi nilai ekstrim.

2. **Pra-pemrosesan Data**  
   - Normalisasi fitur numerik  
   - Pemisahan data latih dan uji (train-test split)

3. **Modeling KNN**  
   - Penentuan parameter `k` terbaik  
   - Pelatihan model dengan `KNeighborsClassifier`  
   - Prediksi kelas region pelanggan

4. **Evaluasi Model**  
   - Akurasi  
   - Confusion Matrix  
   - Classification Report (precision, recall, f1-score)

## ✅ Hasil

Model KNN menunjukkan performa yang cukup baik dalam mengklasifikasikan pelanggan berdasarkan region. Eksperimen dengan nilai `k` menunjukkan perbedaan tingkat akurasi dan memberikan wawasan tentang sensitivitas parameter model terhadap distribusi data.


