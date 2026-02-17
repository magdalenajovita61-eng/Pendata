# Materi Data Understanding

Tahap **Data Understanding** merupakan tahap awal dalam metodologi CRISP-DM yang berfokus pada proses memahami data yang akan digunakan dalam proyek data mining atau machine learning. Pada tahap ini, peneliti atau analis belum melakukan pemodelan, melainkan berusaha mengenal karakteristik data secara menyeluruh. Pemahaman data yang baik sangat penting karena kesalahan interpretasi data di tahap awal dapat menyebabkan hasil analisis yang keliru di tahap selanjutnya.

Tahap ini membantu memastikan bahwa data yang digunakan benar-benar relevan dengan tujuan penelitian serta memiliki kualitas yang memadai untuk dianalisis.

## Collect Initial Data

Collect Initial Data adalah proses mengumpulkan data dari berbagai sumber yang tersedia. Data dapat berasal dari database internal perusahaan, file CSV atau Excel, API, web scraping, maupun sumber terbuka (open data). Pada tahap ini, penting untuk mendokumentasikan dari mana data diperoleh, bagaimana cara pengambilannya, serta dalam format apa data tersebut disimpan.

Tujuan utama dari tahap ini adalah untuk mengetahui apakah data yang tersedia sudah mencukupi untuk menjawab permasalahan yang ingin diselesaikan. Selain itu, tahap ini juga membantu peneliti memahami batasan data, misalnya apakah data hanya mencakup periode waktu tertentu, apakah ada data yang tidak lengkap, atau apakah ada batasan akses terhadap data tertentu.

Hasil dari tahap ini biasanya berupa laporan pengumpulan data awal yang berisi daftar sumber data, jumlah data yang berhasil dikumpulkan, serta catatan awal mengenai kondisi data.

## Describe Data

Pada tahap Describe Data, data yang telah dikumpulkan dideskripsikan secara umum. Deskripsi ini mencakup struktur dataset, jumlah baris (record), jumlah kolom (atribut), tipe data setiap kolom (numerik, kategorikal, tanggal, dan sebagainya), serta contoh nilai yang terdapat dalam dataset.

Tahap ini bertujuan untuk memberikan gambaran awal tentang bentuk dan isi data. Dengan memahami struktur data, peneliti dapat mulai membayangkan teknik analisis atau model apa yang mungkin sesuai digunakan. Selain itu, tahap ini juga membantu dalam mengidentifikasi atribut mana yang berpotensi relevan dengan tujuan analisis.

Deskripsi data biasanya disajikan dalam bentuk tabel ringkasan atau penjelasan tertulis yang menggambarkan setiap atribut dalam dataset.

## Explore Data

Explore Data merupakan tahap eksplorasi data secara lebih mendalam. Pada tahap ini, dilakukan analisis statistik deskriptif serta visualisasi data untuk menemukan pola, tren, atau keanehan dalam dataset. Eksplorasi data membantu peneliti memahami bagaimana distribusi nilai dalam setiap atribut, apakah terdapat outlier, serta apakah terdapat hubungan tertentu antar variabel.

Beberapa teknik yang umum digunakan pada tahap ini meliputi pembuatan histogram untuk melihat distribusi data, boxplot untuk mendeteksi outlier, serta scatter plot untuk melihat hubungan antar dua variabel. Selain itu, analisis korelasi juga dapat dilakukan untuk mengetahui hubungan antar variabel numerik.

Tujuan utama dari eksplorasi data adalah untuk mendapatkan wawasan awal tentang karakteristik data. Wawasan ini sangat berguna dalam menentukan strategi pembersihan data, pemilihan fitur, serta pemilihan algoritma pada tahap modeling.

## Verify Data Quality

Verify Data Quality bertujuan untuk mengevaluasi kualitas data yang dikumpulkan. Data yang berkualitas buruk dapat menyebabkan model yang dihasilkan menjadi tidak akurat atau menyesatkan. Oleh karena itu, pada tahap ini dilakukan pemeriksaan terhadap berbagai permasalahan umum pada data, seperti nilai yang hilang (missing values), data duplikat, inkonsistensi format, serta kesalahan penulisan.

Selain itu, pada tahap ini juga dievaluasi apakah terdapat data yang tidak masuk akal, misalnya nilai umur negatif atau tanggal yang tidak valid. Semua permasalahan yang ditemukan sebaiknya didokumentasikan agar dapat ditangani pada tahap Data Preparation.

Hasil dari tahap ini biasanya berupa laporan kualitas data yang menjelaskan jenis permasalahan yang ditemukan, tingkat keparahan masalah tersebut, serta rekomendasi awal untuk pembersihan dan perbaikan data.