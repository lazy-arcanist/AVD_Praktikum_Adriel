# 📊 Tugas Analisis & Visualisasi Data (AVD)

Koding dan Kecerdasan Artifisial (KKA) – Rekayasa Perangkat Lunak, Fase F Kelas XI.
Repository ini berisi **Praktikum 1-6** (dataset Nusantara Mart) dan **Tugas Proyek** (dataset Kaggle) dengan Python (Pandas, Matplotlib, Seaborn).

## 👤 Identitas
| | |
|---|---|
| **Nama** | Adriel Winston Tjahja |
| **Kelas** | XI RPL 8 |
| **No. Absen** | 2 |

## 🔗 Notebook
| Tugas | Buka di Colab | Dataset |
|---|---|---|
| Praktikum 1-6 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vKfQ1ZZOes7M-kgym5EwUGxkd4raBQTP?usp=sharing) | `penjualan_nusantaramart.csv` |
| Tugas Proyek | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16Xg4r9ReY8sxOSHeMZRJ8NiXWueWMNjK?usp=sharing) | `kaggle_chess-text_leaderboard.csv` |

## 📁 Isi Repository
```
├── Praktikum1-6_AVD_Nusantara_Mart_Terjawab.ipynb
├── Proyek_AVD_Ringkas_SMK.ipynb
├── penjualan_nusantaramart.csv
├── kaggle_chess-text_leaderboard.csv
└── README.md
```

## 🧪 Praktikum 1-6: Nusantara Mart
| Latihan | Topik | Teknik |
|---|---|---|
| 1 | Eksplorasi data | `head`, `info`, `describe`, `groupby` |
| 2 | Perbandingan kategori | Bar chart |
| 3 | Tren penjualan | Line chart |
| 4 | Hubungan dua variabel | Scatter plot |
| 5 | Distribusi & outlier | Histogram, boxplot, IQR |
| 6 | Ringkasan visual | Dashboard (subplot 2×2) |

**Temuan singkat:** Fashion dan Elektronik menyumbang ±67% penjualan; penjualan memuncak di Mei 2026 lalu turun di Juni; lonjakan dipengaruhi pesanan borongan (outlier).

## 🏆 Tugas Proyek: Leaderboard Catur Model AI (Kaggle)
Menganalisis 42 model AI pada benchmark *chess-text*. *Produk* = model AI, *performa* = skor, *harga* = biaya per giliran (sen).

| Ketentuan | Isi |
|---|---|
| Pembersihan data | Cek kosong & duplikat, ubah format long → wide |
| Statistik | Rata-rata, median, korelasi, efisiensi, dan lainnya |
| Visualisasi | Bar, Line, Scatter, Histogram, Boxplot |
| Outlier | Aturan IQR pada biaya |
| Dashboard | 4 grafik dalam 1 figure |
| Laporan | Rekomendasi bisnis (±210 kata) |

**Temuan singkat:** korelasi skor dan biaya hanya 0,07, jadi model mahal tidak otomatis lebih baik. Contoh: `gemini-3.7-flash` berskor ±1.397 dengan biaya ±1,19 sen, sedangkan `gpt-5.5-2026-04-23` berskor ±1.244 dengan biaya ±40,3 sen.

## ▶️ Cara Menjalankan
1. Klik tombol **Open in Colab**.
2. Jalankan sel upload dan pilih berkas CSV yang sesuai.
3. Pilih **Runtime → Run all**.

## 🤖 Penggunaan AI
AI digunakan sebagai alat bantu belajar (menyusun format notebook, kode, dan insight). Penjelasannya ada di bagian **Penjelasan Penggunaan AI** pada masing-masing notebook.
