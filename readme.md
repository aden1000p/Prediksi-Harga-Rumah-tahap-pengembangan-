# 🏠 Prediksi Harga Rumah

<div align="center">
  <img src="https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-blue?style=for-the-badge" alt="ML Type" />
  <img src="https://img.shields.io/badge/Python-3.8+-green?style=for-the-badge&logo=python" alt="Python" />
</div>

---

## 📌 Deskripsi Proyek

Proyek ini adalah sistem **prediksi harga rumah** berbasis Machine Learning yang membantu Anda membuat keputusan pembelian rumah dengan lebih baik dan akurat berdasarkan data-data real dari pasar properti.


---

## 🎯 Maksud & Tujuan

### 🔍 **Maksud**
Pengambilan keputusan berbasis data yang fokus memprediksi kejadian di masa depan dengan memanfaatkan data-data historis yang tersedia.

### 🚀 **Tujuan**
- ✅ Memudahkan calon pembeli dalam memilih rumah dengan harga yang sesuai
- ✅ Memberikan rekomendasi harga berdasarkan karakteristik rumah (lokasi, luas, jumlah ruangan, dll)
- ✅ Meningkatkan akurasi estimasi harga properti di area tertentu
- ✅ Menjadi tools referensi untuk negosiasi harga

---

## 🛠️ Metodologi

### Data yang Digunakan
- 📍 **Lokasi/Area** - Wilayah atau district
- 📐 **Luas Bangunan** - Total square meter
- 🏘️ **Jumlah Kamar** - Bedroom count
- 🚿 **Fasilitas** - Bathroom, Kitchen, dll
- 📊 **Kondisi Properti** - Age, Condition status

### Tahapan Pengembangan 
📥 Data Collection & Cleaning
📥 Pengumpulan & Pembersihan Data
📊 Exploratory Data Analysis (EDA)
📊 Analisis Data Eksploratif (EDA)
⚙️ Feature Engineering
⚙️ Rekayasa Fitur
🏗️ Model Selection & Training
🏗️ Pemilihan Model & Pelatihan
📈 Model Evaluation & Tuning
📈 Evaluasi & Penyetelan Model
🚀 Deployment & Testing
🚀 Penerapan & Pengujian

**Status Saat Ini:** 🔄 Tahap Analisa & Development

---

## 📊 Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
</div>

---

## ⚠️ Catatan Pengembangan

### Kekurangan & Area Improvement
- 🔧 Model masih dalam tahap development dan testing
- 📉 Akurasi prediksi masih perlu ditingkatkan melalui feature engineering lebih lanjut
- 📚 Dataset masih terbatas, perlu ekspansi data
- 🐛 Masih ada beberapa bugs yang perlu diperbaiki
- 🔍 Validasi hasil masih perlu pengawasan manual

### Rencana Pengembangan
- [ ] Menambah dataset dengan sample lebih banyak
- [ ] Optimasi model dengan hyperparameter tuning
- [ ] Implementasi model advanced (Ensemble, Neural Networks)
- [ ] Membuat Web Interface untuk user-friendly
- [ ] Deploy ke cloud platform (Heroku/AWS)

---

## 📁 Struktur Project

Prediksi-Harga-Rumah/ ├── data/ │ ├── raw/ # Data mentah │ └── processed/ # Data yang sudah dibersihkan ├── notebooks/ │ ├── 01_eda.ipynb # Exploratory Data Analysis │ └── 02_modeling.ipynb # Model Training & Evaluation ├── src/ │ ├── preprocessing.py # Data cleaning & preprocessing │ ├── model.py # Model definition │ └── utils.py # Helper functions ├── README.md └── requirements.txt
# Definisi model
│ └── utils.py # Fungsi pembantu
├── README.md
└── requirements.txt
