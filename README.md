# 🫀 Prediksi Risiko Penyakit Jantung menggunakan KNN

![Python 3.10](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Scikit-learn 1.3](https://img.shields.io/badge/Scikit--learn-1.3-orange?logo=scikit-learn&logoColor=white)
![Status Completed](https://img.shields.io/badge/Status-Completed-success)
![Dataset 303 data](https://img.shields.io/badge/Dataset-303_data-blueviolet)

> Proyek Machine Learning untuk memprediksi apakah seorang pasien memiliki risiko penyakit jantung berdasarkan parameter medis klinis menggunakan algoritma **K-Nearest Neighbors (KNN) Classifier**.

---

## 📌 Deskripsi Proyek

Penyakit jantung merupakan salah satu penyebab utama kematian di dunia. Diagnosis dini yang cepat dan akurat dapat membantu pencegahan risiko fatal. Proyek ini mengimplementasikan Kecerdasan Buatan untuk membantu melakukan skrining awal pasien berdasarkan beberapa metrik kesehatan dasar.

Proyek ini membangun model Machine Learning untuk mengklasifikasikan apakah seorang pasien **Berisiko (Yes)** atau **Sehat (No)** berdasarkan data rekam medis dari 303 pasien.

---

## 📂 Struktur Repositori

Proyek ini sengaja dipecah menjadi pipeline modular yang terbagi ke dalam 4 berkas Notebook Google Colab terpisah demi kemudahan analisis:

* `1_Data_Acquisition.ipynb` : Proses pengunduhan dataset asli dari repositori publik.
* `2_Data_Preprocessing.ipynb` : Pembersihan data kosong dan transformasi skala fitur (*Feature Scaling*).
* `3_Model_Training_Testing.ipynb` : Proses training algoritma KNN dengan rasio data 80:20.
* `4_Model_Evaluation_Demo.ipynb` : Evaluasi performa model, pembuatan grafik hasil, dan simulasi prediksi data baru.

---

## 📊 Hasil Evaluasi & Grafik

Model dievaluasi menggunakan data testing terpisah untuk menjamin keaslian akurasi. Berikut adalah visualisasi hasil pengujian model:

### A. Analisis Distribusi Umur Pasien
![Distribusi Umur](1_distribusi_umur.png)

### B. Confusion Matrix Pengujian Model
![Confusion Matrix](2_confusion_matrix.png)

### C. Performa Metrik Model KNN
![Metrik Evaluasi](3_metrik_evaluasi.png)

---

## 🛠️ Spesifikasi Fitur Dataset

Dataset yang digunakan berasal dari **UCI Machine Learning Repository (Cleveland Heart Disease Dataset)**. Fitur utama yang digunakan meliputi:
1. `age`: Umur pasien (Tahun)
2. `sex`: Jenis kelamin (1 = Pria, 0 = Wanita)
3. `cp`: Tipe nyeri dada (Skala kualitatif 1-4)
4. `trestbps`: Tekanan darah saat istirahat / Tensi (mm Hg)
5. `chol`: Kadar kolesterol serum (mg/dl)

---

## 🎥 Media Tambahan

* **Link Video Demo (3-5 Menit):** [https://drive.google.com/file/d/1dpdm9iXETpDu89oXHERudAefEqLBWpp9/view?usp=sharing]
* **Slide Presentasi:** [https://drive.google.com/file/d/1C8teWaNbHfctxRYvjy7jPRK3SkEkqsKq/view?usp=sharing]

---
*Proyek ini disusun untuk memenuhi Tugas Pengganti UAS Genap Mata Kuliah Kecerdasan Buatan (Kelas C), Departemen Teknik Elektro, Universitas Brawijaya.*
