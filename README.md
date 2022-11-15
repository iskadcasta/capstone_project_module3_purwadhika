# capstone_project_module3_purwadhika
Business Problem Understanding
Context
Divisi Big Data yang ada pada suatu perusahaan e-commerce sedang diminta untuk melakukan identifikasi pelanggan yang akan hilang atau tidak lagi menggunakan layanan perusahaan. Salah satu fungsinya melakukan identifikasi pelanggan tersebut adalah untuk menawarkan penawaran-penawaran khusus yang dapat membuat pelanggan tersebut tidak hilang dan tetap menggunakan layanan perusahaan. Fenomena pelanggan yang berpotensi hilang atau tidak lagi menggunakan layanan perusahaan dapat disebut sebagai Customer Churn. Dengan adanya aktivitas ini diharapkan pelanggan-pelanggan tetap loyal terhadap layanan yang diberikan oleh perusahaan.

Problem Statement
Hal yang diperlukan untuk melakukan aktivitas ini adalah dengan membuat problem statement. Fenomena Customer Churn ini dapat disebabkan oleh banyak faktor seperti munculnya pesaing-pesaing baru perusahaan yang memiliki layanan sejenis, layanan perusahaan yang kurang memuaskan dan lain sebagainya. Hal ini memiliki sedikit ambiguitas karena ketidaktahuan secara pasti penyebab dari Customer Churn.

Oleh sebab itu tugas dari Divisi Big Data akan memprediksi fenomena Customer Churn ini. Dengan adanya aktivitas ini membuat perusahaan dapat mengantisipasi fenomena Customer Churn yang akan terjadi nantinya.

Goals
Maka berdasarkan context dan permasalahan tersebut, perusahaan membutuhkan kemampuan memprediksi kemungkinan pelanggan yang dapat churn dikemudian hari. Hal tersebut bertujuan agar pendapatan perusahaan tidak akan berkurang dikemudian hari kare terjadinya Customer Churn.

Selain itu, perusahaan juga ingin mengetahui faktor dan variabel apa saja yang menyebabkan terjadinya Customer Churn. Dengan mengetahui hal tersebut perusahaan dapat membuat rencana yang lebih baik untuk mendekati pelanggan agar tetap loyal terhadap layanan yang diberikan oleh perusahaan.

Analytic Approach
Jadi kita akan melakukan analisis data untuk menemukan pelanggan yang akan Churn dan pelanggan yang tetap loyal pada layanan yang diberikan oleh perusahaan.kemudian hasil analisis tersebut dapat kita gunakan untuk membuat program atau promosi atau kegiatan lainnya yang bertujuan untuk tetap mempertahankan pelanggan yang memiliki kemungkinan Churn.

Metric Evaluation
Type 1 error : False Positive
Konsekuensi: Biaya penawaran khusus yang dikeluarkan oleh perusahaan menjadi sia-sia.

Type 2 error : False Negative
Konsekuensi: Pelanggan melakukan Churn dan tidak lagi menggunakan layanan perusahaan.

Berdasarkan konsekuensinya, maka sebisa mungkin yang akan kita lakukan adalah dengan mengoptimalkan biaya pengeluaran yang dikeluarkan oleh perusahaan untuk membuat penawaran maupun promo khusus untuk pelanggan dan tidak membuat pelanggan menjadi Churn.
Jadi, matric yang cocok untuk digunakan dalam kasus ini adalah roc_auc. Karena kita akan memaksimalkan nilai Recall/True Positive Rate dan meminimalkan False Positive Rate.
