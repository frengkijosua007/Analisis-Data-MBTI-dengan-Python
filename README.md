Analisis K-Means pada Dataset Tipe Kepribadian Myers-Briggs (MBTI) dengan Python

Deskripsi:
Dalam proyek ini, saya menggunakan algoritma K-Means untuk menganalisis dataset tipe kepribadian Myers-Briggs (MBTI) yang diambil dari Kaggle. Proses analisis ini dilakukan menggunakan bahasa Python di Jupyter Notebook. Dataset ini berisi 50 postingan dari 8600 individu beserta 4 huruf kode MBTI mereka.

Tujuan dan Metodologi:
Proyek ini bertujuan untuk mengeksplorasi apakah unggahan publik seseorang dapat digunakan untuk mengelompokkan tipe kepribadian mereka dengan lebih akurat. Dengan menggunakan teknik K-Means clustering, saya memproses data untuk menemukan pola-pola yang tersembunyi dalam tulisan-tulisan mereka.

1. Persiapan dan Pembersihan Data:
Dataset yang digunakan tidak memiliki nilai yang hilang tetapi memerlukan beberapa pengorganisasian ulang karena distribusi postingan yang tidak merata untuk setiap tipe kepribadian. Saya melakukan pembersihan data untuk memastikan bahwa setiap individu diwakili dengan baik dalam analisis.
2. K-Means Clustering:
   - Proses Pengelompokan:
     Saya menerapkan algoritma K-Means untuk mengelompokkan data berdasarkan fitur-fitur yang diekstraksi dari postingan publik. Data setiap individu dipecah dan digabungkan kembali berdasarkan tipe kepribadian mereka.
   - Visualisasi Hasil:
  Menggunakan berbagai teknik visualisasi, seperti grafik sebar dan grafik bar, untuk memahami distribusi dan karakteristik masing-masing klaster yang terbentuk.

Hasil dan Pembahasan:
Setelah menerapkan K-Means clustering, saya menemukan bahwa kepribadian yang berbeda menunjukkan pola tulisan yang berbeda di media sosial. Misalnya, tipe kepribadian introvert cenderung menggunakan kata-kata yang berbeda dibandingkan dengan tipe ekstrovert. Pola ini dapat membantu dalam mengelompokkan individu ke dalam tipe kepribadian tertentu.
1. Akurasi Klasifikasi:
Saya juga menggunakan Naive Bayes Classifier dari NLTK untuk membandingkan hasilnya dengan metode K-Means. Pengklasifikasi ini mencapai tingkat akurasi sekitar 60% untuk setiap sifat yang ditentukan.
Implementasi Fungsi:
2. Saya mendefinisikan sebuah fungsi yang memungkinkan pengguna untuk memasukkan postingan mereka dan mendapatkan grafik yang menunjukkan tipe kepribadian mereka berdasarkan informasi persentase dan tipe kepribadian akhir.

Kesimpulan:
Proyek ini menunjukkan bahwa analisis tulisan publik dapat digunakan untuk mengelompokkan tipe kepribadian dengan teknik K-Means clustering. Hasilnya memberikan wawasan yang menarik tentang bagaimana tipe kepribadian yang berbeda berinteraksi di media sosial. Penelitian ini juga membuka kemungkinan untuk lebih lanjut mengembangkan alat yang dapat membantu psikolog dan perusahaan media sosial dalam memahami pengguna mereka dengan lebih baik.
