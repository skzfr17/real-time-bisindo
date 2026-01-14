# Real-Time Pengenalan Bahasa Isyarat BISINDO Menggunakan EfficientNetB0

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun sistem **pengenalan Bahasa Isyarat Indonesia (BISINDO) secara real-time** menggunakan metode **Deep Learning** dengan arsitektur **EfficientNetB0**.  
Sistem ini memanfaatkan input video dari kamera atau webcam untuk mendeteksi dan mengklasifikasikan gerakan tangan menjadi huruf BISINDO secara langsung.

Proyek ini diharapkan dapat membantu meningkatkan aksesibilitas komunikasi antara penyandang disabilitas tuli dan masyarakat umum.

---

## 🎯 Tujuan
- Membangun sistem pengenalan BISINDO berbasis **real-time video**
- Mengimplementasikan **EfficientNet** sebagai model klasifikasi citra
- Menguji performa model dalam kondisi real-time
- Menghasilkan output prediksi bahasa isyarat secara langsung

---

## 🧠 Metode yang Digunakan
- **Convolutional Neural Network (CNN)**
- **EfficientNet (Transfer Learning)**
- **Computer Vision**
- **Real-Time Video Processing**

---

## 📂 Dataset
- Dataset berupa **citra huruf alfabet bahasa isyarat BISINDO**
- Data diperoleh dari:
  - Pengambilan data mandiri menggunakan kamera
  - Dataset pendukung
- Setiap kelas mewakili **huruf BISINDO**
- Dataset melalui tahapan:
  - Data cleaning
  - Resize & normalisasi
  - Data Augmentasi
  - Split data
---
## 🏗️ Arsitektur Model
- Model dasar: **EfficientNetB0**
- Teknik:
  - Transfer Learning
  - Fine-tuning
- Loss Function: Categorical Crossentropy
- Optimizer: Adam
- Metrics: accuracy

---

## 🛠️ Teknologi & Tools
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy**
- **Matplotlib**

---

## 📊 Hasil & Evaluasi
- Model mampu mengenali bahasa isyarat BISINDO secara real-time
- Evaluasi dilakukan menggunakan:
  - Accuracy
  - Confusion Matrix
- Sistem berjalan dengan latency rendah dan responsif

## 👤 Author

**Bayyinahtun Dwi Sumatri**
Mahasiswa Ilmu Komputer
