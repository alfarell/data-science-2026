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
8. **Pertemuan 9** - [Pertemuan9_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan9_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Klasifikasi Supervised: Logistic Regression vs Decision Tree (Breast Cancer dataset), Confusion Matrix, evaluasi metrik (Precision, Recall, F1-Score), visualisasi pohon keputusan.
9. **Pertemuan 10** - [Pertemuan10_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan10_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Klasifikasi Imbalanced Data & Random Forest (Telco Customer Churn), pembobotan `class_weight='balanced'`, evaluasi ROC-AUC score, dan estimasi probabilitas churn.
10. **Pertemuan 11** - [Pertemuan11_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan11_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Unsupervised Learning: Segmentasi Pelanggan dengan K-Means Clustering, Elbow Method (WCSS), Silhouette Score, serta Hierarchical Clustering (Dendrogram & Ward's Linkage).
11. **Pertemuan 12** - [Pertemuan12_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan12_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Market Basket Analysis & Sistem Rekomendasi: Algoritma Apriori & Association Rules (`mlxtend`) dengan metrik Support, Confidence, Lift, serta Content-Based Filtering menggunakan Cosine Similarity.
12. **Pertemuan 13** - [Pertemuan13_Alfarell_Muchamad_Yuwanto_240401010037.ipynb](Pertemuan13_Alfarell_Muchamad_Yuwanto_240401010037.ipynb) - Klasifikasi Non-Linear & NLP: Membangun Multi-Layer Perceptron (MLP) Neural Network dengan TensorFlow/Keras pada dataset non-linear `make_moons`, serta Analisis Sentimen teks ulasan produk dengan TF-IDF Vectorizer + Logistic Regression.

## Tools & Library

- **Bahasa Pemrograman:** Python 3.x
- **Library utama:** pandas, numpy, matplotlib, seaborn, scikit-learn, scipy, mlxtend, tensorflow
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
pip install pandas numpy matplotlib seaborn scikit-learn scipy mlxtend tensorflow jupyter
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

## Kesimpulan singkat (Pertemuan 1-13)

Selama 13 pertemuan ini saya mempraktikkan alur kerja Data Science yang menyeluruh:
- **Fondasi & Eksplorasi (P1–P5):** Pemrograman Python dasar, pemuatan data, pembersihan data (*missing values, duplicates, outliers*), eksplorasi statistik, dan perancangan *dashboard* visualisasi statis.
- **Preprocessing & Machine Learning Klasik (P6–P10):** Penskalaan fitur, *encoding* data kategorikal, pemodelan Regresi Linear, Klasifikasi (Logistic Regression, Decision Tree, Random Forest), penanganan *imbalanced data*, dan evaluasi komprehensif (MAE, RMSE, $R^2$, Precision, Recall, F1-Score, ROC-AUC).
- **Unsupervised Learning & Data Mining (P11–P12):** Segmentasi klaster pelanggan dengan K-Means dan Hierarchical Clustering, penentuan klaster optimal via Elbow Method dan Silhouette Score, *Market Basket Analysis* dengan algoritma Apriori & Association Rules, serta sistem rekomendasi *Content-Based Filtering*.
- **Deep Learning & NLP (P13):** Jaringan saraf tiruan (*Multi-Layer Perceptron / MLP*) dengan Keras/TensorFlow untuk pemisahan data non-linear, serta pemrosesan bahasa alami (NLP) untuk analisis sentimen ulasan produk menggunakan TF-IDF dan Logistic Regression.
