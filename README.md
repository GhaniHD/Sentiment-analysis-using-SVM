# Sentiment Analysis using SVM


Dalam aplikasi ini, **Support Vector Machine (SVM)** digunakan untuk mengklasifikasikan ulasan film atau produk menjadi **positif** atau **negatif**. Dataset yang digunakan dalam aplikasi ini diambil dari **UMICH SI650** yang tersedia di Kaggle.

[Link Dataset Kaggle](https://www.kaggle.com/c/si650winter11/data)

Proyek ini berfokus pada analisis sentimen teks, yang digunakan untuk memahami bagaimana ulasan pengguna berhubungan dengan perasaan atau opini mereka tentang film atau produk yang dibahas.

## Teknologi

* **Bahasa Pemrograman**: Python
* **Library**:

  * **scikit-learn**: Untuk model SVM dan preprocessing
  * **pandas**: Untuk manipulasi dan analisis data
  * **numpy**: Untuk operasi numerik
  * **matplotlib**: Untuk visualisasi hasil
  * **nltk**: Untuk preprocessing teks

## Fitur Utama

* **Preprocessing Data**:

  * Penghapusan stopwords
  * Tokenisasi teks
  * Vektorisasi menggunakan `CountVectorizer` atau `TF-IDF`
* **Training Model**: Penggunaan algoritma **SVM** untuk melatih model berdasarkan dataset.
* **Evaluasi Model**: Menggunakan metrik evaluasi seperti akurasi, precision, recall, dan f1-score.
* **Visualisasi**: Menghasilkan grafik untuk menggambarkan hasil evaluasi model.


### Deskripsi Proyek:

Proyek ini bertujuan untuk mengklasifikasikan **ulasan film atau produk** menjadi dua kategori: **positif** dan **negatif**, menggunakan algoritma **Support Vector Machine (SVM)**. Dataset yang digunakan diambil dari Kaggle UMICH SI650.

### Tugas yang Dilakukan:

* **Data Preprocessing**:

  * Membersihkan teks dengan menghapus stopwords, simbol, dan karakter tidak relevan.
  * Melakukan tokenisasi dan konversi teks menjadi vektor numerik menggunakan `TF-IDF`.
* **Model Training**:

  * Menggunakan **SVM** untuk melatih model berdasarkan data ulasan.
* **Evaluasi**:

  * Menilai akurasi, precision, recall, dan f1-score untuk mengevaluasi performa model.
* **Visualisasi**:

  * Membuat grafik untuk menunjukkan distribusi sentimen dan hasil evaluasi model.

### Teknologi yang Digunakan:

* **Python** (versi 3.x)
* **scikit-learn**: Untuk training dan evaluasi model.
* **pandas & numpy**: Untuk data manipulation.
* **matplotlib**: Untuk visualisasi.
* **nltk**: Untuk text preprocessing.


