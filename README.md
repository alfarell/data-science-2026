# Data Science - Alfarell Muchamad Yuwanto

Nama : Alfarell Muchamad Yuwanto

NIM : 240401010037

Kelas : IF401

Program Studi : PJJ Informatika

## Deskripsi

Halo, saya Alfarell Muchamad Yuwanto, mahasiswa Program Studi PJJ Informatika (Kelas IF401). Repositori ini merupakan catatan praktikum dan portofolio kecil untuk mata kuliah Data Science. Tujuan saya adalah membangun pemahaman praktis tentang alur kerja Data Science: memuat data, eksplorasi, visualisasi, preprocessing, hingga model sederhana.

Di dalam repo ini Anda akan menemukan notebook hands-on yang digunakan pada setiap pertemuan, dataset pendukung (folder `datasets/`) dan hasil ekspor (folder `exports/`). Setiap notebook berisi penjelasan singkat, kode yang dapat dijalankan ulang, dan visualisasi hasil eksperimen.

## Daftar Pertemuan (Notebook)

1. **Pertemuan 1** - [Pertemuan1_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan1_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Pengantar Python: variabel, tipe data, fungsi, perulangan.
2. **Pertemuan 2** - [Pertemuan2_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan2_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Memuat & inspeksi dataset (`pd.read_csv`), EDA dasar (contoh: Titanic).
3. **Pertemuan 3** - [Pertemuan3_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan3_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Pembersihan data (duplikat, missing, normalisasi) pada dataset perumahan.
4. **Pertemuan 4** - [Pertemuan4_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan4_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Eksplorasi statistik dan visualisasi dataset Iris (deskriptif, korelasi, heatmap).
5. **Pertemuan 5** - [Pertemuan5_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan5_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Dashboard visualisasi statis (dataset `tips`), pembuatan subplot 2×2 dan ekspor gambar ke `./exports/dashboard_tips.png`.
6. **Pertemuan 6** - [Pertemuan6_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan6_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Preprocessing (handling missing, encoding, scaling) dan persiapan train/test (Titanic).
7. **Pertemuan 7** - [Pertemuan7_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan7_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Prediksi Gaji (dataset sintetis), regresi linear, evaluasi model.

## Tools & Library

- **Bahasa Pemrograman:** Python 3.x
- **Library utama:** pandas, numpy, matplotlib, seaborn, scikit-learn, scipy
- **Environment / Tools:** Jupyter Notebook / JupyterLab, Google Colab, Git & GitHub

## Menjalankan notebook

1. Clone atau buka folder repository ini di komputer Anda.
2. (Opsional tapi direkomendasikan) buat virtual environment dan install dependensi:

```bash
python -m venv .venv
# Windows (PowerShell):
.\.venv\Scripts\Activate.ps1
# Atau Windows (cmd):
.\.venv\Scripts\activate
# macOS/Linux:
# source .venv/bin/activate
pip install --upgrade pip
pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
```

3. Jalankan Jupyter Lab/Notebook dan buka file `.ipynb` yang diinginkan:

```bash
jupyter lab
# atau
jupyter notebook
```

4. (Google Colab) Anda juga dapat mengunggah file `.ipynb` ke Google Colab atau membuka langsung dari GitHub (jika Anda push repository ini ke GitHub): Open Colab -> File -> Upload notebook, atau Open notebook -> GitHub.

## Catatan terkait ekspor gambar (Pertemuan 5)

- Jika hasil gambar yang diekspor kosong/blank, cek hal berikut:
  - Jalankan semua sel dari atas (Restart kernel -> Run All) agar semua objek `fig` dan `axes` terbentuk sebelum menyimpan.
  - Gunakan `fig.savefig(...)` (menyimpan objek figure langsung) atau pastikan menyimpan setelah semua plotting selesai.
  - Tambahkan `fig.tight_layout()` sebelum menyimpan untuk memperbaiki tata letak.

## Kesimpulan singkat (Pertemuan 1-7)

Selama 7 pertemuan ini saya mempraktikkan alur dasar Data Science: pemrograman Python dasar, pemuatan dan EDA dataset, pembersihan data, teknik visualisasi, pra-pemrosesan untuk machine learning, serta pelatihan dan evaluasi model sederhana. Materi ini membentuk fondasi yang kuat untuk praktik lanjutan seperti feature engineering, model tuning, dan deployment.
