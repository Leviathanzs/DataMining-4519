# DataMining-4519

# Analisis Kepuasan Pelanggan Maskapai Menggunakan Model Pembelajaran Mesin

## Deskripsi
Proyek ini bertujuan untuk menganalisis faktor-faktor yang mempengaruhi kepuasan pelanggan maskapai dan memprediksi tingkat kepuasan pelanggan menggunakan berbagai model pembelajaran mesin. Dataset yang digunakan berisi informasi tentang pelanggan maskapai dan fitur-fitur terkait, yang digunakan untuk memprediksi apakah pelanggan merasa **"satisfied"** atau **"neutral or dissatisfied"** dengan layanan maskapai.

Model yang digunakan untuk analisis ini meliputi:
1. **Logistic Regression**
2. **Random Forest**
3. **Gradient Boosting (XGBoost)**

## Fitur Utama
- Pemrosesan data dan feature engineering
- Pemisahan dataset untuk pelatihan dan pengujian model
- Penggunaan model pembelajaran mesin untuk prediksi kepuasan pelanggan
- Evaluasi model menggunakan metrik seperti akurasi, precision, recall, dan F1-score
- Diagram alur untuk menggambarkan proses penyelesaian proyek

## Prasyarat
Sebelum menjalankan notebook ini, pastikan Anda telah menginstal dependensi berikut:

- Python 3.x
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `xgboost`
- `networkx`
- `google-colab` (untuk mengakses Google Drive jika diperlukan)

Anda dapat menginstal dependensi tersebut menggunakan `pip`:
```bash
pip install pandas numpy matplotlib scikit-learn xgboost networkx google-colab
Cara Menggunakan
1. Menggunakan Google Colab
Proyek ini sudah dikonfigurasi untuk digunakan di Google Colab, sehingga Anda hanya perlu membuka file analisis_kepuasan_pelanggan.ipynb di Google Colab.

Langkah-langkah:
Membuka Notebook:

Pergi ke Google Colab dan buka file .ipynb ini. Anda dapat mengupload file ke Colab jika belum ada di Google Drive Anda.
Menghubungkan Google Drive (jika dataset berada di Drive):

Jalankan kode berikut untuk menghubungkan Google Drive dan mengakses dataset:
python
Salin kode
from google.colab import drive
drive.mount('/content/drive')
Setelah itu, sesuaikan path dataset di dalam kode Anda dengan lokasi file di Google Drive.
Menjalankan Proses:

Setelah menghubungkan Google Drive atau mengunggah file dataset, jalankan seluruh notebook untuk memulai pemrosesan data, pembuatan model, dan evaluasi.
2. Menjalankan Secara Lokal
Jika Anda lebih memilih untuk menjalankan notebook ini di lingkungan lokal, Anda perlu melakukan hal berikut:

Pastikan Anda memiliki semua dependensi yang dibutuhkan.
Unduh file dataset yang digunakan (misalnya, Dataset Airlines.csv) dan pastikan dataset berada di direktori yang sesuai.
Jalankan notebook dengan mengganti path dataset sesuai dengan lokasi file dataset Anda.
Struktur Folder
bash
Salin kode
.
├── analisis_kepuasan_pelanggan.ipynb  # Notebook untuk analisis
├── Dataset/                            # Folder yang berisi dataset
│   └── Dataset Airlines.csv            # Dataset yang digunakan untuk analisis
└── README.md                           # File ini
Evaluasi Model
Model dievaluasi menggunakan beberapa metrik evaluasi:

Accuracy: Persentase prediksi yang benar.
Precision: Proporsi prediksi positif yang benar.
Recall: Proporsi data positif yang terprediksi dengan benar.
F1-Score: Rata-rata harmonis dari precision dan recall.
Berikut adalah hasil evaluasi dari masing-masing model:

Logistic Regression:
Accuracy: 0.87
Precision: 0.86
Recall: 0.83
F1-Score: 0.84

Random Forest:
Accuracy: 0.95
Precision: 0.96
Recall: 0.93
F1-Score: 0.95

XGBoost:
Accuracy: 0.96
Precision: 0.96
Recall: 0.94
F1-Score: 0.95

Diskusi Hasil dan Kesimpulan
Model XGBoost memberikan performa terbaik dengan F1-Score sebesar 0.95.
Random Forest memberikan keseimbangan yang baik antara akurasi dan recall.
Logistic Regression meskipun sederhana, memberikan hasil yang cukup baik.
Secara keseluruhan, model pembelajaran mesin dapat digunakan untuk memprediksi kepuasan pelanggan dengan tingkat akurasi yang tinggi, dengan faktor-faktor yang paling berpengaruh seperti jenis perjalanan, keterlambatan kedatangan, dan kelas penerbangan.

Kontribusi
Jika Anda ingin berkontribusi pada proyek ini, silakan lakukan fork dari repositori ini dan buat pull request dengan perubahan atau perbaikan yang Anda buat.

Lisensi
Proyek ini dilisensikan di bawah lisensi MIT.

Penulis
Nama: Oky Satria Widhiansyah
NIM: A11.2020.12674
Universitas: Universitas Dian Nuswantoro
Prodi: Teknik informatika
Jika ada pertanyaan atau saran, jangan ragu untuk membuka issue di GitHub ini.
