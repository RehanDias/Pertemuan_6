# Proyek Analisis Data

Repository ini berisi dua proyek analisis data yang diimplementasikan menggunakan Python dalam format Jupyter Notebook.

## Proyek 1: Analisis Data Survival Kanker (TUGAS_1)

Analisis pola kelangsungan hidup pasien kanker payudara menggunakan Dataset Haberman.

### Informasi Dataset

-   Sumber: Dataset Haberman's Survival
-   Fitur-fitur:
    -   Usia: Usia pasien saat operasi
    -   Tahun Operasi: Tahun dilakukannya operasi
    -   Jumlah Node Aksila: Jumlah node aksila positif yang terdeteksi
    -   Status Survival: Status kelangsungan hidup (1 = bertahan > 5 tahun, 2 = meninggal dalam 5 tahun)

### Analisis yang Dilakukan

1. Memuat dan Eksplorasi Data Awal

    - Memuat dataset menggunakan pandas
    - Inspeksi data dasar dan statistik ringkasan

2. Visualisasi
    - Distribusi Usia berdasarkan Status Survival (Histogram dengan KDE)
    - Distribusi Tahun Operasi (Histogram)
    - Analisis PDF dan CDF
    - Distribusi Usia (Box Plot)
    - Distribusi Tahun Operasi (Violin Plot)
    - Pairplot untuk Analisis Multivariat (dengan style whitegrid)
        - Visualisasi hubungan antar semua variabel
        - Pewarnaan berdasarkan status survival
        - Menggunakan palette Set2 untuk diferensiasi visual yang jelas

### Library yang Digunakan

-   pandas: Manipulasi data
-   numpy: Komputasi numerik
-   matplotlib: Visualisasi dasar
-   seaborn: Visualisasi statistik lanjutan

## Proyek 2: Analisis Data Eksploratori - Data NSFG dan BRFSS (TUGAS_2)

Analisis komprehensif dataset National Survey of Family Growth (NSFG) dan Behavioral Risk Factor Surveillance System (BRFSS).

### Komponen Analisis

1. Operasi DataFrame dan Series

    - Memuat dan memeriksa data NSFG
    - Pembersihan data dasar dan validasi

2. Pembersihan dan Validasi Data

    - Penanganan nilai yang hilang
    - Perhitungan dan transformasi variabel

3. Teknik Visualisasi

    - Pembuatan histogram
    - Penyaringan data
    - Analisis berat lahir

4. Analisis Statistik
    - Analisis korelasi
    - Regresi linear sederhana
    - Analisis distribusi

### Analisis Hubungan

1. Analisis Pendapatan dan Tinggi Badan

    - Box plot untuk tinggi berdasarkan tingkat pendapatan
    - Violin plot untuk visualisasi distribusi

2. Studi Distribusi Pendapatan

    - Analisis PMF (Probability Mass Function)
    - Perhitungan korelasi

3. Analisis Regresi
    - Implementasi regresi linear sederhana
    - Visualisasi hasil regresi

### Teknologi yang Digunakan

-   Python 3.x
-   Library:
    -   pandas
    -   numpy
    -   matplotlib
    -   seaborn
    -   scipy.stats
    -   empiricaldist

## Cara Penggunaan

1. Clone repository ini
2. Instal package yang diperlukan:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

3. Jalankan Jupyter Notebook:

```bash
jupyter notebook
```

4. Buka salah satu notebook:
    - TUGAS_1_PERT6_RehanDiasPratama_41822110045.ipynb
    - TUGAS_2_PERT6_RehanDiasPratama_41822110045.ipynb

## Penulis

Rehan Dias Pratama (41822110045)
