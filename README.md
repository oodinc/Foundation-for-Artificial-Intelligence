# Ch. 1: Foundation on Artificial Intelligence (team task at Google Colab only)

README ini menjelaskan deliverables dari tugas Bab 1 tentang dasar-dasar kecerdasan buatan. Tugas ini adalah kerja kelompok yang dilakukan hanya di Google Colab. Tugas ini mencakup pembuatan kode Python untuk kalkulasi pecahan uang tunai dan analisis data menggunakan pustaka pandas serta visualisasi data.

## Isi

1. [Kalkulasi Pecahan Uang Tunai (01_Kelompok_B_2.ipynb)](#1-kalkulasi-pecahan-uang-tunai-01_kelompok_b_2ipynb)
2. [Analisis Data & Visualisasi (01_Kelompok_B_3.ipynb)](#2-analisis-data--visualisasi-01_kelompok_b_3ipynb)

## 1. Kalkulasi Pecahan Uang Tunai (`01_Kelompok_B_2.ipynb`)

### Ringkasan Tugas
Tugas ini melibatkan pembuatan program Python yang menerima input berupa integer untuk simpanan nasabah (dari Rp 0 hingga Rp 1 miliar) dan menghitung jumlah setiap jenis uang kertas dan koin Indonesia yang diperlukan untuk penarikan.

### Persyaratan
- **Input**: Integer untuk simpanan nasabah.
- **Output**: Jumlah setiap pecahan uang yang diperlukan dan informasi jika ada sisa yang tidak bisa dicairkan.

### Aturan
1. Mengutamakan pecahan terbesar terlebih dahulu.
2. Beri informasi jika ada sisa saldo yang tidak dapat dicairkan.
3. Hitung jumlah uang kertas dan koin secara terpisah.
4. Penarikan maksimal sebesar Rp 1 miliar.

### Struktur Kode
- **Penanganan Input**: Memastikan bahwa input integer berada dalam rentang yang valid.
- **Kalkulasi Pecahan Uang**: Menggunakan loop untuk menghitung jumlah setiap pecahan yang dibutuhkan.
- **Output**: Menampilkan jumlah uang kertas dan koin yang diperlukan, total uang kertas, koin, serta saldo yang tidak bisa dicairkan jika ada.

---

## 2. Analisis Data & Visualisasi (`01_Kelompok_B_3.ipynb`)

### Ringkasan Tugas
Tugas ini mencakup penggunaan pustaka `pandas` untuk analisis data dan pustaka `matplotlib` serta `seaborn` untuk visualisasi data pada dataset HRDataset.

### Pertanyaan Analisis
1. **Minimum, Median, Maksimum, dan Rata-rata Gaji Berdasarkan Status Pernikahan dan Jenis Kelamin**
   - Menggunakan fungsi `groupby` dan `agg` untuk mendapatkan statistik yang diinginkan.

2. **Top-5 Alasan Pemutusan Hubungan Kerja (PHK)**
   - Dihitung menggunakan `value_counts`.

3. **Jumlah Tertinggi dari Skor Kinerja 'Exceeds' Berdasarkan Sumber Rekrutmen**
   - Difilter menggunakan `PerformanceScore == 'Exceeds'` dan dikelompokkan berdasarkan `RecruitmentSource`.

4. **Jumlah Manajer di Setiap Departemen**
   - Menggunakan `groupby` dan `nunique` untuk mendapatkan jumlah unik manajer.

5. **Rasio Pemutusan Hubungan Kerja Berdasarkan Jenis Kelamin**
   - Menggunakan `value_counts` dengan normalisasi untuk menghitung rasio.

### Visualisasi Data
1. **Rasio PHK Berdasarkan Jenis Kelamin** - Bar chart yang menunjukkan rasio PHK berdasarkan jenis kelamin.
2. **Scatter Plot** - Menampilkan plot antara "Salary" dan "EngagementSurvey" dengan warna berbeda berdasarkan status `Termd`.
3. **Jumlah PHK Berdasarkan Departemen** - Bar chart yang menunjukkan jumlah PHK karyawan berdasarkan departemen.
4. **Persentase Karyawan yang Di-PHK Berdasarkan Posisi (Pie Chart)** - Menampilkan persentase karyawan yang di-PHK berdasarkan posisi.
5. **Boxplot Gaji Berdasarkan Status Pernikahan dan Status PHK** - Boxplot yang membandingkan distribusi gaji.
6. **Pairplot** - Menunjukkan hubungan antara "Salary," "EngagementSurvey," "EmpSatisfaction," dan "Absences," dengan kategori `Termd`.

### Pertanyaan Wawasan
1. **Apakah Ada Hubungan Antara Manajer dan Skor Kinerja?**
   - Dianalisis menggunakan skor kinerja rata-rata berdasarkan manajer.

2. **Sumber Rekrutmen Terbaik untuk Menjamin Rasio PHK Rendah**
   - Memeriksa rasio PHK berdasarkan sumber rekrutmen.

---

## Cara Menjalankan Kode

1. Buka Google Colab.
2. Unggah file `01_Kelompok_B_2.ipynb` dan `01_Kelompok_B_3.ipynb`.
3. Untuk `01_Kelompok_B_3.ipynb`, pastikan dataset HR dapat diakses melalui URL yang tersedia atau dengan mengunggahnya langsung.

## Kesimpulan

Tugas ini mencakup manipulasi data, analisis, dan visualisasi menggunakan alat Python untuk memperoleh wawasan dari data finansial dan HR.
