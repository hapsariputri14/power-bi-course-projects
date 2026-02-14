# Data Exploration

Folder ini mendokumentasikan tahap awal dalam siklus analisis data, yang berfokus pada pemahaman struktur, kualitas, dan pola dasar dari dataset sebelum dilakukan analisis lanjutan atau visualisasi kompleks.

## Ringkasan Proyek
Tujuan utama dari modul ini adalah melakukan analisis eksploratif pada dataset penjualan e-commerce untuk mengidentifikasi tren pelanggan, pola pembelian, dan anomali data (outlier).

## Aktivitas Utama
* **Profiling Data:** Mengidentifikasi tipe data, struktur tabel, dan ringkasan statistik (mean, median, standar deviasi) untuk memahami karakteristik angka penjualan.
* **Pembersihan Data:** Mengelola kualitas data melalui identifikasi nilai yang hilang (null values) dan menangani ketidakkonsistenan data menggunakan Power Query Editor.
* **Analisis Tren dan Pola:** * Mengidentifikasi lonjakan transaksi pada akhir tahun (Oktober - Desember) yang dipengaruhi oleh musim belanja.
    * Menganalisis korelasi antara kelompok usia pelanggan dengan kategori produk yang diminati (contoh: segmen usia 16-25 tahun lebih dominan pada produk Fashion).
* **Identifikasi Outlier:** Menemukan transaksi dengan nilai ekstrem (di atas Rp 50 juta) yang disebabkan oleh pembelian dalam jumlah besar atau transaksi khusus.

## Wawasan Utama (Key Insights)
* **Distribusi Transaksi:** Sebagian besar transaksi pelanggan berada pada kisaran Rp 300.000 hingga Rp 400.000.
* **Stabilitas Pelanggan:** Pelanggan dalam kelompok usia yang lebih tua cenderung memiliki nilai transaksi yang lebih stabil dan sedikit lebih tinggi dibandingkan kelompok usia muda.
* **Segmentasi Pasar:** Terdapat perbedaan preferensi belanja yang signifikan antar kelompok usia, yang memberikan dasar kuat untuk strategi pemasaran tertarget.

## Alat yang Digunakan
* **Power BI Desktop:** Digunakan untuk pengolahan awal dan visualisasi statistik dasar.
* **Power Query Editor:** Digunakan untuk proses ETL (Extract, Transform, Load) dan pembersihan data.
