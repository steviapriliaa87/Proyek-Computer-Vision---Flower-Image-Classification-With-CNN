# 🌸 Flower Classification - Klasifikasi Gambar Bunga (10 Kelas)

Proyek ini merupakan implementasi klasifikasi gambar bunga ke dalam 10 kelas menggunakan model CNN (Convolutional Neural Network) dengan TensorFlow dan Keras. Model ini kemudian diekspor dalam format SavedModel, TensorFlow Lite, dan TensorFlow.js.

---

## 👩‍💻 Profil Kontributor

- **Nama:** Stevi Aprilianti Cahyani  
- **Email:** steviaprilia7@gmail.com  
- **ID Dicoding:** apriliaastevi

---

## 🛠️ Teknologi dan Library

- Python
- TensorFlow dan Keras  
- TensorFlow Lite  
- TensorFlow.js  
- Matplotlib, NumPy, OS, Shutil  
- Kaggle API (untuk dataset)

---

## 📁 Struktur Proyek

- **01 - Import Library dan Setup Kaggle**
- **02 - Download & Ekstrak Dataset dari Kaggle**
- **03 - Visualisasi Gambar Contoh**
- **04 - Data Augmentasi & Image Generator**
- **05 - Arsitektur Model CNN**
- **06 - Training Model**
- **07 - Evaluasi dan Visualisasi Akurasi**
- **08 - Simpan & Konversi Model ke TFLite & TFJS**
- **09 - Kompres & Unduh Model**

---

## 🔧 Instalasi

Untuk menginstal dependensi yang dibutuhkan, jalankan:

```python
pip install -r requirements.txt
```
---

## ▶️ Cara Penggunaan

1. Buka file notebook di Jupyter Notebook atau [Google Colab](https://colab.research.google.com/).
2. Jalankan setiap sel secara berurutan:
   - Mengunduh dataset dari Kaggle
   - Menampilkan gambar sampel
   - Membangun dan melatih model
   - Mengevaluasi performa
   - Menyimpan dan mengekspor model
3. Ubah parameter sesuai kebutuhan untuk eksperimen model lain.

---

## 📦 Output Model

- `saved_model/` → format TensorFlow standar
- `tflite/` → model untuk deployment ringan
- `tfjs_model/` → model untuk deployment web

Semua hasil akan dikompresi dan tersedia dalam bentuk `.zip`.

---

## 📜 Lisensi

Proyek ini menggunakan dataset dari [Kaggle](https://www.kaggle.com/datasets/utkarshsaxenadn/flower-classification-5-classes-roselilyetc).
