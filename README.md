# Preprocessing_and_Modeling_Laptop_Price_Spesification
Proyek Machine Learning untuk memprediksi harga laptop menggunakan prapemrosesan data, analisis data eksploratif (EDA), dan pemodelan regresi dengan Python.

# Deskripsi Proyek

Proyek ini merupakan implementasi Machine Learning menggunakan Python untuk melakukan pengolahan data dan pemodelan prediksi harga laptop berdasarkan spesifikasi yang tersedia pada dataset laptop_price.csv.

Proyek ini berfokus pada tahapan data preprocessing, Exploratory Data Analysis (EDA), pembagian dataset, pemodelan regresi, evaluasi model, dan penyimpanan model. Seluruh proses pengolahan dan analisis dilakukan menggunakan Jupyter Notebook.

# Tujuan
Memahami proses pengumpulan dan pemuatan dataset.
Melakukan pembersihan serta transformasi data.
Menganalisis karakteristik dataset menggunakan EDA.
Mempersiapkan data untuk kebutuhan Machine Learning.
Membangun model regresi untuk memprediksi harga laptop.
Mengevaluasi performa model menggunakan metrik evaluasi.
Menyimpan model agar dapat digunakan kembali.

# Struktur Repository

Preprocessing_and_Modeling_Laptop_Price_Spesification/
├── Laporan3.ipynb
├── laptop_price.csv
└── README.md

# Dataset

Dataset laptop_price.csv digunakan sebagai sumber data untuk menganalisis spesifikasi dan harga laptop.

Informasi yang terdapat dalam dataset mencakup karakteristik laptop, seperti merek, tipe laptop, ukuran layar, resolusi layar, prosesor, RAM, penyimpanan, kartu grafis, sistem operasi, berat, dan harga.

# Teknologi dan Library

Proyek ini menggunakan beberapa teknologi dan library Python berikut:
Python — bahasa pemrograman utama.
Jupyter Notebook — lingkungan untuk menjalankan kode dan menganalisis data.
Pandas — pengolahan dan manipulasi dataset.
NumPy — operasi numerik.
Matplotlib — visualisasi data.
Seaborn — visualisasi statistik.
Scikit-learn — preprocessing, pemodelan Machine Learning, dan evaluasi model.
Joblib — penyimpanan dan pemuatan model.

# Tahapan Pengerjaan

Data Collecting — menyiapkan dataset yang akan digunakan.
Data Loading — memuat dataset ke dalam Python.
Data Cleaning and Transformation — membersihkan dan mempersiapkan data.
Exploratory Data Analysis (EDA) — memahami karakteristik data melalui statistik dan visualisasi.
Data Splitting — membagi data menjadi data pelatihan dan pengujian.
Modeling — melatih algoritma regresi untuk prediksi harga laptop.
Model Evaluation — mengevaluasi hasil prediksi menggunakan MAE, MSE, dan R².
Model Saving — menyimpan model yang telah dilatih agar dapat digunakan kembali.

# Cara Menjalankan Proyek

1. Clone Repository
git clone https://github.com/USERNAME/Preprocessing_and_Modeling_Laptop_Price_Spesification.git
Ganti USERNAME dengan username GitHub pemilik repository.

2. Masuk ke Folder Proyek
cd Preprocessing_and_Modeling_Laptop_Price_Spesification

3. Instal Library yang Dibutuhkan
pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter

4. Jalankan Jupyter Notebook
jupyter notebook
Buka file Laporan3.ipynb, kemudian jalankan setiap sel kode secara berurutan.
Pastikan file laptop_price.csv berada pada lokasi yang sesuai dengan path yang digunakan di dalam notebook.

# Evaluasi Model

Performa model dievaluasi menggunakan metrik berikut:
MAE (Mean Absolute Error) — mengukur rata-rata selisih absolut antara nilai aktual dan prediksi.
MSE (Mean Squared Error) — mengukur rata-rata kuadrat kesalahan prediksi.
R² (Coefficient of Determination) — mengukur seberapa baik model menjelaskan variasi nilai target.
Hasil evaluasi digunakan untuk membandingkan performa model yang diterapkan pada dataset.

# Hasil yang Diharapkan

Proyek ini diharapkan dapat menghasilkan pemahaman mengenai proses preprocessing data, analisis spesifikasi laptop, penerapan algoritma regresi, dan evaluasi model untuk prediksi harga laptop.

# Author

Ahmad Raja
Machine Learning Project — Laptop Price Prediction
Dataset digunakan untuk mempelajari hubungan antara spesifikasi laptop dan harga yang tercatat.
