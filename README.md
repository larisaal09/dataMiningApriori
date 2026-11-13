# Penerapan Data Mining dengan Algoritma Apriori untuk Analisis Pola Pemesanan Paket Layanan pada Berjodoh Wedding

Tugas akhir Program Studi Teknik Informatika, Fakultas Teknik dan Ilmu Komputer,
Universitas Indraprasta PGRI (2026).

## Deskripsi
Aplikasi desktop untuk menganalisis data transaksi pemesanan paket layanan
Berjodoh Wedding dan menemukan kombinasi layanan yang paling sering dipesan
bersamaan. Hasilnya berupa aturan asosiasi yang dapat dipakai untuk menyusun
paket layanan dan strategi promosi.

## Fitur
- Pengolahan data transaksi pemesanan (pre-processing)
- Pembentukan frequent itemset dengan algoritma Apriori
- Perhitungan nilai support dan confidence
- Pembentukan aturan asosiasi dengan parameter minimum support dan
  minimum confidence yang dapat diatur
- Filter data berdasarkan rentang tanggal

## Data dan Hasil
- Data: 483 transaksi pemesanan (Januari 2023 – Februari 2026)
- Parameter: minimum support 20%, minimum confidence 70%
- Kombinasi paling sering dipesan: Indoor, MUA, dan Dekorasi
  (support 37,62%)
- Confidence tertinggi: Indoor & Dekorasi → MUA (96,93%)

## Teknologi
Java (NetBeans), MySQL, JDBC, UML (use case, activity, deployment diagram)

## Penulis
Larisa Umi Salamah Al Khoir (NPM 202243501235)
Pembimbing: Fanisya Alva Mustika, M.Kom (Materi) dan Dr. Irwan Agus, SE., MMSI (Teknik)
