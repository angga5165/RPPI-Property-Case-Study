# RPPI Property Exploratory Data Analysis (EDA)

## Overview
Proyek ini merupakan studi kasus Exploratory Data Analysis (EDA) terhadap data listing properti yang dikumpulkan oleh PT Ray Pink Property Indonesia (RPPI). Analisis dilakukan untuk memberikan insight strategis kepada manajemen (Direksi, C-Level, dan Senior Managers) dalam memahami kondisi pasar properti, karakteristik rumah yang paling banyak dijual, serta mendukung pengambilan keputusan ekspansi bisnis dan investasi jangka pendek.

Analisis difokuskan pada pemahaman data (data understanding), kualitas data, pola pasar, serta rekomendasi berbasis data tanpa membangun model prediktif.

---

## Business Objectives
Analisis ini bertujuan untuk:
- Mengevaluasi kualitas dan kesiapan data properti yang dimiliki RPPI
- Memberikan masukan perbaikan data agar perusahaan semakin data-driven
- Mengidentifikasi perbedaan harga properti antar kota
- Menentukan karakteristik rumah yang paling banyak dijual
- Memberikan rekomendasi kota potensial untuk pembukaan kantor cabang baru
- Mengidentifikasi peluang investasi properti dengan anggaran maksimal Rp 25 Miliar
- Menggali insight strategis tambahan yang relevan bagi pertumbuhan bisnis RPPI

---

## Dataset Overview
Dataset berisi data rumah yang dijual di beberapa kota di Indonesia dengan variabel utama meliputi:
- Luas tanah (LT) dan luas bangunan (LB)
- Jumlah kamar tidur (KT) dan kamar mandi (KM)
- Kapasitas garasi dan carport
- Lokasi dan kota properti
- Jenis sertifikat
- Daya listrik
- Harga properti
- Tanggal pembuatan iklan

Data diperoleh dari sistem internal yang dikumpulkan oleh tim Data Engineer / Database Administrator RPPI.

---

## Methodology
Pendekatan yang digunakan adalah Exploratory Data Analysis (EDA), dengan tahapan:
- Pemeriksaan kualitas data (missing values, duplikasi, inkonsistensi)
- Data cleaning dan standardisasi
- Feature engineering sederhana (harga per meter persegi, segmentasi harga)
- Analisis deskriptif dan visualisasi data

Analisis ini tidak mencakup pemodelan prediktif, forecasting, maupun optimasi model, sesuai dengan batasan studi kasus.

---

## Key Insights
Beberapa insight utama yang diperoleh dari analisis:
- Segmen properti yang paling banyak dijual adalah segmen low-end (harga < Rp 1 Miliar).
- Luas bangunan dan harga per meter persegi merupakan faktor dominan dalam karakteristik rumah yang paling laku.
- Terdapat perbedaan harga properti yang signifikan antar kota.
- Kabupaten Bogor – Barat menunjukkan kombinasi pasar aktif, dominasi segmen low-end, dan harga yang relatif terjangkau.
- Rumah yang paling banyak dijual umumnya memiliki luas bangunan kecil hingga menengah, 2-3 kamar tidur, 1 carport, dan sertifikat SHM.

---

## Business Recommendations
Berdasarkan hasil analisis:
- RPPI disarankan mempertimbangkan Kabupaten Bogor – Barat sebagai lokasi pembukaan kantor cabang berikutnya.
- Strategi investasi sebaiknya difokuskan pada rumah segmen low-end dengan karakteristik yang sesuai dengan pola rumah paling laku.
- Peningkatan kualitas data, terutama standarisasi atribut lokasi dan kelengkapan informasi properti, akan meningkatkan kemampuan analisis dan pengambilan keputusan di masa depan.
