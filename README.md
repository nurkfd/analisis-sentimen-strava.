
# Analisis Sentimen Aplikasi Strava

## Deskripsi
Repository ini merupakan bagian dari penelitian analisis sentimen
terhadap ulasan pengguna aplikasi Strava yang diperoleh dari
Google Play Store.

Penelitian ini bertujuan mengklasifikasikan ulasan pengguna
ke dalam tiga kategori sentimen, yaitu:
- Positive
- Neutral
- Negative

## Sumber Data
- Platform: Google Play Store
- Aplikasi: Strava
- Package: com.strava
- Bahasa: Indonesia

## Dataset
Dataset yang digunakan merupakan hasil scraping dan preprocessing
ulasan pengguna aplikasi Strava.

File dataset:
`dataset_strava_clean.csv`

## Preprocessing
Tahapan pengolahan data meliputi:
1. Identifikasi missing values
2. Eliminasi data dengan teks kosong
3. Analisis statistik deskriptif
4. Transformasi dan scaling untuk analisis
5. Konversi label sentimen
6. Feature engineering
7. Analisis distribusi dan korelasi
8. Deteksi dan penanganan outlier

## Label Sentimen

| Rating | Sentimen |
|---|---|
| 1-2 | Negative |
| 3 | Neutral |
| 4-5 | Positive |

## Model
Model yang direkomendasikan untuk penelitian ini adalah
IndoBERT untuk klasifikasi sentimen teks berbahasa Indonesia.

## Repository
Dataset dan dokumentasi penelitian disimpan dalam repository ini.
