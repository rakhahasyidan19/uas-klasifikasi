# Prediksi Status Pinjaman Pelanggan Menggunakan Metode Klasifikasi

## Deskripsi Project
Project ini merupakan tugas UAS Data Mining dengan metode **Klasifikasi**. Tujuan project adalah membangun model machine learning untuk memprediksi `status_pinjaman` pelanggan berdasarkan data profil dan informasi finansial pelanggan.

## Dataset
- Nama file: `data.csv`
- Jumlah data: 50.000 baris
- Jumlah kolom: 20 kolom
- Target klasifikasi: `status_pinjaman`
- Sumber dataset: [Isi link dataset publik asli dari Kaggle/UCI/Google Dataset Search/Data.gov]

## Kolom Dataset
Dataset memiliki kolom:
- `id_pelanggan`
- `usia`
- `status_pekerjaan`
- `lama_bekerja_tahun`
- `pendapatan_tahunan`
- `skor_kredit`
- `lama_riwayat_kredit_tahun`
- `aset_tabungan`
- `hutang_saat_ini`
- `gagal_bayar_tercatat`
- `tunggakan_2thn_terakhir`
- `catatan_negatif`
- `tipe_produk`
- `tujuan_pinjaman`
- `jumlah_pinjaman`
- `suku_bunga`
- `rasio_hutang_terhadap_pendapatan`
- `rasio_pinjaman_terhadap_pendapatan`
- `rasio_pembayaran_terhadap_pendapatan`
- `status_pinjaman`

## Framework CRISP-DM
Analisis dilakukan menggunakan tahapan CRISP-DM:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

## Algoritma yang Digunakan
- Decision Tree
- Random Forest
- Logistic Regression
- K-Nearest Neighbor

## Hasil Evaluasi
Model terbaik berdasarkan hasil evaluasi adalah **Random Forest**.

| Metrik | Nilai |
|---|---:|
| Accuracy | 91.23% |
| Precision | 0.9123 |
| Recall | 0.9123 |
| F1-Score | 0.9122 |
| Cross Validation Mean | 91.39% |

## Kesimpulan
Model Random Forest berhasil memenuhi kriteria sukses evaluasi minimal 80%. Dengan accuracy sebesar 91.23%, model dapat digunakan untuk membantu memprediksi status pinjaman pelanggan berdasarkan data keuangan dan profil pelanggan.

## Link Project
- Google Sites:(https://sites.google.com/view/portofolio-rakha-shidqi/project/deployment)]
- YouTube Presentasi: (https://youtu.be/aQSDGpBS5jo?si=OY6Vndg5evbcoW6l)]


## Cara Menjalankan Notebook
1. Pastikan Python dan Jupyter Notebook/Google Colab sudah tersedia.
2. Pastikan file `data.csv` berada pada folder yang sama dengan file notebook.
3. Buka file `UAS_Data_Mining_Klasifikasi_Status_Pinjaman.ipynb`.
4. Jalankan seluruh cell dari atas ke bawah.
5. Upload file notebook, dataset, dan README ini ke GitHub.
