# Sistem Pendukung Keputusan Pemilihan Produk Unggulan UMKM (Metode SAW)
*Nama*   : Herlita

*NPM*    : G1A023018

Aplikasi berbasis web ini merupakan Sistem Pendukung Keputusan (SPK) yang dirancang untuk membantu menentukan produk unggulan Usaha Mikro, Kecil, dan Menengah (UMKM) secara objektif. Sistem ini menggunakan metode **Simple Additive Weighting (SAW)** untuk melakukan normalisasi nilai alternatif berdasarkan kriteria yang telah ditentukan (*Benefit* & *Cost*) hingga menghasilkan rekomendasi produk terbaik berdasarkan ranking tertinggi.

Proyek ini dibuat untuk memenuhi Tugas Proyek Akhir pada Mata Kuliah Decision Suport Sistem (.

## ✨ Fitur Utama
* **Manajemen Kriteria Dinamis:** Mendukung penambahan kriteria baru serta pengaturan bobot persentase secara *real-time* menggunakan slider penyesuai.
* **Input Alternatif Produk:** Kemudahan dalam memasukkan data produk beserta penilaian skalanya secara fleksibel.
* **Kalkulasi Otomatis Metode SAW:** Proses perhitungan transparan yang menampilkan:
  * Matriks Asal ($X$)
  * Matriks Normalisasi ($R$)
  * Skor Tertimbang ($V$)
* **Visualisasi Ranking:** Output hasil keputusan akhir yang dilengkapi dengan visual progress bar dan rekomendasi produk unggulan teratas.
* **Desain Responsif & Modern:** Antarmuka yang bersih, nyaman di mata, dan adaptif di berbagai ukuran layar berkat integrasi CSS Grid dan Flexbox.

## 🛠️ Teknologi yang Digunakan
* **HTML5** (Struktur halaman Semantik)
* **CSS3** (Kustomisasi UI modern, Flexbox, Grid, & Variabel CSS)
* **Vanilla JavaScript** (Logika perhitungan metode SAW dan manipulasi DOM secara dinamis)
