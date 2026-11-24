# Exploratory Data Analysis (EDA) Calon Siswa SMK Wiworotomo 2026/2027

## Gambaran Proyek
Proyek ini melakukan Exploratory Data Analysis (EDA) terhadap dataset pendaftaran calon siswa SMK Wiworotomo tahun ajaran 2026/2027. Analisis bertujuan memahami pola pendaftaran, minat calon siswa terhadap program keahlian, asal sekolah, komposisi jenis kelamin, serta kondisi kualitas data.

## Tujuan
- Mengetahui distribusi calon siswa pada setiap program keahlian.
- Mengidentifikasi sekolah asal dengan jumlah pendaftar terbanyak.
- Mengamati komposisi jenis kelamin calon siswa.
- Memeriksa kelengkapan, konsistensi, dan potensi masalah data.
- Menyusun insight awal yang dapat mendukung evaluasi penerimaan siswa baru.

## Dataset
- Sumber: data pendaftaran calon siswa SMK Wiworotomo tahun ajaran 2026/2027 (data internal).
- Ukuran dataset awal: **654 baris dan 37 kolom**.
- Program keahlian: TPm, TKR, TKJ, TSM, dan TITL (total 5 kategori).
- Data yang dianalisis mencakup program keahlian, sekolah asal, jenis kelamin, pekerjaan orang tua, tempat lahir, serta beberapa atribut numerik yang tersedia.

> **Privasi:** Dataset mentah memuat data pribadi. Jangan mengunggah CSV mentah ke repository publik. Gunakan data agregat atau dataset yang sudah dianonimkan dan mendapat izin.

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Analisis yang dilakukan
1. Memuat dataset dan memeriksa ukuran serta struktur data.
2. Memeriksa kolom kosong dan kolom tambahan yang tidak memiliki nama jelas.
3. Mengamati distribusi calon siswa per program keahlian.
4. Menganalisis distribusi jenis kelamin.
5. Menganalisis sekolah asal pendaftar.
6. Mengamati kategori pekerjaan orang tua.
7. Meninjau tempat lahir dan atribut numerik yang tersedia.
8. Membuat tabulasi silang jurusan dan jenis kelamin.

## Hasil utama
- Total record pendaftaran yang dianalisis: **654**.
- TPm menjadi program keahlian dengan jumlah pendaftar terbanyak (**205**).
- TKR berada pada urutan kedua (**161**).
- TKJ mencatat **103** pendaftar, TSM **96**, dan TITL **89**.
- Jenis kelamin terisi untuk 617 record: 566 laki-laki dan 51 perempuan.
- Pada kolom sekolah asal, notebook mencatat **275 nama sekolah berbeda**; perlu normalisasi penulisan sebelum analisis lanjutan agar nama sekolah yang sama tidak terhitung sebagai kategori berbeda.
- Dataset mengandung missing values yang cukup banyak pada beberapa atribut. Notebook juga mencatat 36 baris duplikat pada dataframe analisis setelah kolom tertentu dikeluarkan; angka ini bukan duplikat seluruh baris data mentah.

## Kesimpulan singkat
Pendaftar paling banyak memilih TPm, diikuti TKR. Distribusi pendaftar menunjukkan ketertarikan yang berbeda antarprogram keahlian. Data asal sekolah memiliki variasi penulisan yang perlu dibersihkan, sedangkan sejumlah atribut masih banyak kosong. Analisis ini bersifat deskriptif dan belum dapat menjelaskan penyebab pilihan jurusan maupun memprediksi jumlah siswa yang benar-benar melakukan daftar ulang.
