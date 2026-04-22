# Materi Data Preparation

Tahap **Data Preparation** merupakan tahap lanjutan setelah Data Understanding yang berfokus pada proses menyiapkan data agar siap digunakan dalam pemodelan. Tahap ini sering kali menjadi tahap yang paling memakan waktu karena melibatkan banyak proses pembersihan, transformasi, dan rekayasa fitur. Data yang belum dipersiapkan dengan baik dapat menyebabkan performa model menjadi buruk.

Tujuan utama tahap ini adalah menghasilkan dataset akhir yang bersih, konsisten, dan relevan dengan tujuan analisis.

## Select Data

Select Data adalah proses memilih data yang benar-benar relevan dengan tujuan proyek. Tidak semua atribut atau record dalam dataset awal selalu diperlukan. Oleh karena itu, pada tahap ini dilakukan seleksi terhadap kolom yang dianggap penting serta penghapusan data yang tidak relevan atau redundan.

Pemilihan data yang tepat dapat membantu mengurangi kompleksitas model serta meningkatkan performa analisis. Selain itu, dengan mengurangi jumlah atribut yang tidak diperlukan, proses komputasi menjadi lebih efisien.

## Clean Data

Clean Data bertujuan untuk membersihkan data dari berbagai permasalahan yang dapat mengganggu proses analisis. Permasalahan tersebut dapat berupa nilai yang hilang, data duplikat, kesalahan input, maupun inkonsistensi format.

Pada tahap ini, peneliti dapat melakukan berbagai tindakan, seperti menghapus record yang tidak valid, mengisi nilai yang hilang dengan nilai tertentu (misalnya rata-rata atau median), serta memperbaiki kesalahan penulisan. Proses pembersihan data sangat penting karena data yang kotor dapat menyebabkan hasil model menjadi tidak akurat.

## Construct Data

Construct Data merupakan proses pembuatan fitur baru (feature engineering) dari data yang sudah ada. Fitur baru ini dapat membantu model dalam menangkap pola yang lebih kompleks. Contohnya adalah mengubah tanggal lahir menjadi umur, menggabungkan beberapa kolom menjadi satu fitur baru, atau mengelompokkan nilai numerik ke dalam kategori tertentu.

Tahap ini memerlukan pemahaman yang baik terhadap domain permasalahan, karena fitur yang dibuat harus relevan dan bermakna. Feature engineering yang baik sering kali menjadi kunci keberhasilan dalam proyek machine learning.

## Integrate Data

Integrate Data adalah proses menggabungkan data dari beberapa sumber menjadi satu dataset yang utuh. Pada proyek nyata, data sering kali tersebar di berbagai sistem atau file yang berbeda. Oleh karena itu, proses integrasi diperlukan agar data dapat dianalisis secara menyeluruh.

Proses integrasi harus dilakukan dengan hati-hati untuk menghindari kesalahan penggabungan, seperti duplikasi data atau ketidaksesuaian kunci (key). Integrasi data yang baik akan menghasilkan dataset yang lebih lengkap dan informatif.

## Format Data

Format Data bertujuan untuk menyesuaikan format data agar sesuai dengan kebutuhan algoritma pemodelan. Beberapa algoritma membutuhkan data dalam skala tertentu atau format numerik. Oleh karena itu, pada tahap ini dapat dilakukan normalisasi atau standarisasi data numerik, serta encoding untuk data kategorikal.

Hasil akhir dari tahap Data Preparation adalah dataset final yang siap digunakan dalam tahap modeling. Dataset ini sebaiknya disimpan dan didokumentasikan agar dapat digunakan kembali di masa depan.