# Prediksi Konsumsi Rumah Tangga Menggunakan Data Smart Meter

## Deskripsi Project

Project ini bertujuan untuk memprediksi konsumsi listrik rumah tangga menggunakan data Smart Meter dengan pendekatan Machine Learning.
Hasil prediksi diharapkan dapat membantu dalam memahami pola penggunaan energi serta mendukung pengambilan keputusan dalam manajemen energi.



## Dataset

Dataset yang digunakan adalah **smart_meter_data.csv** yang berisi data konsumsi listrik dan faktor-faktor yang mempengaruhinya.

### Fitur dalam dataset:

* **Timestamp** → Waktu pencatatan data
* **Electricity_Consumed** → Konsumsi listrik (target)
* **Temperature** → Suhu lingkungan
* **Humidity** → Kelembapan udara
* **Wind_Speed** → Kecepatan angin
* **Avg_Past_Consumption** → Rata-rata konsumsi sebelumnya
* **Anomaly_Label** → Indikator anomali

Jumlah data: ±5000 baris



## Tahapan Penelitian

1. Data Understanding
2. Data Preprocessing
   * Konversi timestamp
   * Feature engineering
   * Penanganan missing value
   * Normalisasi/Scaling data
3. Exploratory Data Analysis (EDA)
4. Pembagian data (data splitting)
5. Pelatihan model (training)
6. Hyperparameter tuning
7. Evaluasi model
8. Cross-validation
9. Penyimpanan model


## Algoritma yang Digunakan

* Decision Tree Regressor
* Extra Trees Regressor
* Gradient Boosting Regressor


## Model Terbaik

Model terbaik yang diperoleh adalah **Extra Trees Regressor**.

File model disimpan pada folder `model/`:

* `best_model_extra_trees.pkl` → model hasil training
* `scaler.pkl` → digunakan untuk preprocessing data sebelum prediksi

Model dan scaler digunakan bersama untuk memastikan hasil prediksi tetap konsisten.


## Tools & Library

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

## Cara Menjalankan Project

1. Buka file notebook `.ipynb` menggunakan Jupyter Notebook atau Google Colab
2. Jalankan setiap cell secara berurutan
3. Pastikan semua library telah terinstall


## Catatan

Project ini berfokus pada pengembangan dan evaluasi model machine learning, sehingga tidak mencakup tahap deployment (implementasi ke dalam aplikasi atau sistem berbasis web).

## Catatan Model
File model tidak disertakan di repository karena ukuran file melebihi batas GitHub.
Model dapat dibuat ulang melalui notebook yang disediakan.

## Penulis

UPI WIRANINGSIH
F1G123054
