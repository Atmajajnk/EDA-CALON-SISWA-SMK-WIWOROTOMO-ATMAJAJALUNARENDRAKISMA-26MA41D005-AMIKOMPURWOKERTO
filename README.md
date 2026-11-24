# 📊 Exploratory Data Analysis (EDA) Calon Siswa SMK Wiworotomo 2026/2027

<p align="center">
  <img src="https://github.com/user-attachments/assets/397eeb4e-1bdf-4e5b-b243-5a4d3f5aca34" alt="Sampul EDA SMK Wiworotomo 2026/2027" width="100%">
</p>

<p align="center">
  <b>Analisis Data Pendaftaran Calon Siswa Baru</b><br>
  SMK Wiworotomo Purwokerto<br>
  Tahun Ajaran 2026/2027
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas" />
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab" />
  <img src="https://img.shields.io/badge/Project-EDA-success" />
</p>

---

## 📌 Gambaran Proyek

Proyek ini merupakan penerapan **Exploratory Data Analysis (EDA)** terhadap data pendaftaran calon siswa SMK Wiworotomo tahun ajaran 2026/2027.

Analisis dilakukan untuk memahami karakteristik dan pola pendaftaran calon siswa berdasarkan beberapa atribut yang tersedia dalam dataset.

Melalui proses eksplorasi data, proyek ini berupaya memperoleh informasi mengenai minat calon siswa terhadap program keahlian, asal sekolah, komposisi jenis kelamin, pekerjaan orang tua, serta kualitas dan kelengkapan data pendaftaran.

Hasil analisis diharapkan dapat memberikan gambaran awal yang bermanfaat sebagai bahan evaluasi dan pendukung pengambilan keputusan dalam proses penerimaan siswa baru.

## 🎯 Tujuan Analisis

1. Mengetahui distribusi calon siswa pada setiap program keahlian.
2. Mengidentifikasi sekolah asal dengan jumlah pendaftar terbanyak.
3. Mengamati komposisi jenis kelamin calon siswa.
4. Menganalisis kategori pekerjaan orang tua calon siswa.
5. Mengamati persebaran tempat lahir dan atribut numerik yang tersedia.
6. Memeriksa kelengkapan, konsistensi, dan potensi permasalahan pada dataset.
7. Menyusun insight awal berdasarkan hasil eksplorasi data.

## 📁 Dataset

<p align="center">
  <img src="https://github.com/user-attachments/assets/94dcf59a-52ea-4e07-8f77-06187524155a" alt="Dataset Pendaftaran Calon Siswa" width="85%">
</p>

Dataset yang digunakan merupakan data internal pendaftaran calon siswa SMK Wiworotomo tahun ajaran 2026/2027.

| Informasi | Keterangan |
|---|---|
| Sumber Data | Data internal pendaftaran sekolah |
| Jumlah Baris | 654 |
| Jumlah Kolom | 37 |
| Jumlah Program Keahlian | 5 kategori |
| Periode | Tahun Ajaran 2026/2027 |

**Program keahlian yang dianalisis:**
- TPm (Teknik Pemesinan)
- TKR (Teknik Kendaraan Ringan)
- TKJ (Teknik Komputer dan Jaringan)
- TSM (Teknik Sepeda Motor)
- TITL (Teknik Instalasi Tenaga Listrik)

Atribut yang dianalisis meliputi program keahlian, sekolah asal, jenis kelamin, pekerjaan orang tua, tempat lahir, serta beberapa atribut numerik yang tersedia.

> **Catatan Privasi:** Dataset mentah mengandung informasi pribadi calon siswa. Oleh karena itu, data mentah tidak disertakan dalam repository publik. Publikasi hasil analisis harus memperhatikan anonimisasi dan izin penggunaan data.

## 🛠️ Tools dan Library

Proyek ini menggunakan beberapa tools dan library Python untuk proses pengolahan, analisis, dan visualisasi data.

| Tools / Library | Kegunaan |
|---|---|
| Python | Bahasa pemrograman |
| Google Colab | Lingkungan pengolahan data |
| Pandas | Manipulasi dan analisis data |
| NumPy | Pengolahan data numerik |
| Matplotlib | Visualisasi data |
| Seaborn | Visualisasi statistik |

## 🔍 Tahapan Exploratory Data Analysis

Analisis dilakukan melalui beberapa tahapan berikut:

**1. Data Loading dan Inspection**
- Memuat dataset ke dalam lingkungan Google Colab.
- Memeriksa jumlah baris dan kolom.
- Mengidentifikasi tipe data setiap atribut.
- Memeriksa struktur dan isi dataset.

**2. Data Quality Checking**
- Memeriksa missing values.
- Mengidentifikasi kolom yang tidak memiliki nama jelas.
- Memeriksa konsistensi data.
- Mengidentifikasi potensi duplikasi data.

**3. Analisis Distribusi Program Keahlian**
- Menghitung jumlah calon siswa pada setiap program keahlian.
- Mengidentifikasi program keahlian dengan jumlah pendaftar terbanyak.

**4. Analisis Jenis Kelamin**
- Mengamati komposisi calon siswa berdasarkan jenis kelamin.
- Membandingkan distribusi laki-laki dan perempuan.

**5. Analisis Sekolah Asal**
- Mengidentifikasi sekolah asal calon siswa.
- Mengamati sekolah dengan jumlah pendaftar terbanyak.
- Meninjau variasi penulisan nama sekolah.

**6. Analisis Pekerjaan Orang Tua**
- Mengamati kategori pekerjaan orang tua.
- Mengidentifikasi distribusi pekerjaan berdasarkan data yang tersedia.

**7. Analisis Tempat Lahir dan Atribut Numerik**
- Mengamati variasi tempat lahir.
- Meninjau atribut numerik yang tersedia dalam dataset.

**8. Analisis Hubungan Antarvariabel**
- Membuat tabulasi silang antara program keahlian dan jenis kelamin.
- Mengamati pola distribusi calon siswa berdasarkan kedua atribut tersebut.

## 📈 Hasil Analisis Utama

Berdasarkan hasil eksplorasi data yang tercatat dalam notebook, diperoleh beberapa temuan berikut.

### 1. Distribusi Calon Siswa Berdasarkan Program Keahlian

| Program Keahlian | Jumlah Pendaftar |
|---|---:|
| TPm | 205 |
| TKR | 161 |
| TKJ | 103 |
| TSM | 96 |
| TITL | 89 |
| **Total** | **654** |

TPm menjadi program keahlian dengan jumlah pendaftar tertinggi, yaitu 205 calon siswa. Sementara itu, TITL memiliki jumlah pendaftar sebanyak 89 calon siswa.

### 2. Distribusi Jenis Kelamin

Dari 654 record pendaftaran, terdapat 617 record yang memiliki informasi jenis kelamin.

| Jenis Kelamin | Jumlah |
|---|---:|
| Laki-laki | 566 |
| Perempuan | 51 |
| Belum Terisi | 37 |
| **Total** | **654** |

Data menunjukkan bahwa calon siswa laki-laki mendominasi jumlah pendaftaran.

### 3. Analisis Sekolah Asal

Pada kolom sekolah asal ditemukan sebanyak 275 nama sekolah berbeda.

Namun, terdapat kemungkinan bahwa beberapa nama sekolah yang sebenarnya sama tercatat sebagai kategori berbeda karena perbedaan penulisan. Oleh karena itu, diperlukan proses normalisasi nama sekolah untuk meningkatkan akurasi analisis.

### 4. Kualitas Data

Beberapa permasalahan kualitas data yang ditemukan:

- Terdapat missing values pada sejumlah atribut.
- Terdapat kolom tambahan yang tidak memiliki nama jelas.
- Ditemukan variasi penulisan pada nama sekolah asal.
- Terdapat 36 baris duplikat pada dataframe analisis setelah beberapa kolom dikeluarkan.

**Catatan:** Angka 36 merupakan duplikasi pada dataframe analisis tersebut, bukan hasil pemeriksaan duplikasi seluruh baris dataset mentah.

## 📊 Visualisasi Hasil EDA

Hasil eksplorasi data juga disajikan dalam bentuk visualisasi untuk memudahkan pemahaman terhadap pola dan distribusi data.

Visualisasi yang digunakan meliputi:
- Distribusi calon siswa berdasarkan program keahlian.
- Komposisi jenis kelamin.
- Distribusi sekolah asal.
- Distribusi pekerjaan orang tua.
- Persebaran tempat lahir.
- Hubungan program keahlian dengan jenis kelamin.

## 💡 Insight dan Temuan

Berdasarkan hasil analisis, beberapa insight awal yang dapat diperoleh adalah:

1. **Minat Program Keahlian:** TPm menjadi program keahlian dengan jumlah pendaftar terbanyak, diikuti oleh TKR.
2. **Komposisi Pendaftar:** Jumlah calon siswa laki-laki lebih banyak dibandingkan perempuan.
3. **Asal Sekolah:** Terdapat variasi asal sekolah yang cukup beragam, dengan 275 nama sekolah berbeda tercatat.
4. **Kualitas Data:** Missing values dan variasi penulisan data masih menjadi perhatian dalam proses pengolahan dataset.
5. **Evaluasi Pendaftaran:** Hasil eksplorasi dapat digunakan sebagai gambaran awal untuk mengevaluasi distribusi pendaftar pada setiap program keahlian.

## 📝 Kesimpulan

Berdasarkan proses Exploratory Data Analysis terhadap 654 data pendaftaran calon siswa SMK Wiworotomo tahun ajaran 2026/2027, diketahui bahwa TPm merupakan program keahlian dengan jumlah pendaftar tertinggi, yaitu 205 calon siswa, disusul TKR sebanyak 161 calon siswa.

Dari sisi jenis kelamin, data menunjukkan dominasi calon siswa laki-laki. Sementara itu, analisis sekolah asal menunjukkan adanya variasi penulisan nama sekolah yang perlu dinormalisasi.

Selain itu, ditemukan sejumlah missing values dan potensi duplikasi pada dataframe analisis. Hal tersebut menunjukkan bahwa proses pembersihan dan peningkatan kualitas data masih diperlukan untuk mendukung analisis lebih lanjut.

Secara keseluruhan, EDA ini memberikan gambaran deskriptif mengenai karakteristik pendaftaran calon siswa dan dapat menjadi bahan evaluasi awal bagi sekolah. Namun, hasil analisis ini belum digunakan untuk menjelaskan penyebab pemilihan jurusan ataupun memprediksi jumlah siswa yang akan melakukan daftar ulang.

## 🚀 Akses Google Colab

Notebook lengkap yang berisi proses pengolahan data, kode Python, analisis, dan visualisasi dapat diakses melalui tautan berikut:

<p align="center">
  <a href="https://colab.research.google.com/drive/1993a-ZV3Mln4p1hY6-0CVsudxNtC4kZX?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
  </a>
</p>

<p align="center">
  <b>Google Colab Notebook - EDA Calon Siswa SMK Wiworotomo 2026/2027</b>
</p>

---

<p align="center">
  <b>SMK WIWOROTOMO PURWOKERTO</b><br>
  <i>Exploratory Data Analysis | Tahun Ajaran 2026/2027</i>
</p>
