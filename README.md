# UTS Machine Learning: Linear & Logistic Regression

Repositori ini dibuat untuk memenuhi Ujian Tengah Semester (UTS) mata kuliah Machine Learning.

## Identitas Mahasiswa
- **Nama:** Gantha Davianza Tanuwijaya
- **NIM:** 241011401403
- **Kelas:** Reg B
- **Random State:** 3 

## Ringkasan Hasil & Evaluasi

### 1. Bagian A – Linear Regression (`Ads_Data.csv`)
* **Model:** Linear Regression (Normal Equation & Gradient Descent)
* **Persamaan Regresi:** $\hat{y} = 28.21 + 9.07 X$
* **Metrik Evaluasi (Data Testing):**
  * **MAE:** ~4.69
  * **MSE:** ~24.82
  * **RMSE:** ~4.98
  * **$R^2$ Score:** ~0.952 (Model sangat baik dalam menjelaskan variasi penjualan berdasarkan biaya iklan).

### 2. Bagian B – Logistic Regression (`Email_Data.csv`)
* **Model:** Logistic Regression (Gradient Descent dengan fungsi Sigmoid)
* **Metrik Evaluasi (Data Testing pada Threshold 0.5):**
  * **Accuracy:** Tinggi (~93-100% tergantung pembagian data acak)
  * **Precision & Recall:** Seimbang untuk mendeteksi email Spam dan Bukan Spam.
  * **Decision Boundary:** Berhasil memisahkan data menggunakan kombinasi fitur *JumlahLink* dan *KataPromo*.

## Struktur Repositori
```text
uts-machine-learning-241011401403/
├── README.md            # Informasi identitas dan ringkasan hasil UTS
├── tugas_UTS.ipynb      # Notebook Jupyter lengkap dengan kode, grafik, dan output
├── Ads_Data.csv         # Dataset regresi biaya iklan dan penjualan
└── Email_Data.csv       # Dataset klasifikasi email spam
