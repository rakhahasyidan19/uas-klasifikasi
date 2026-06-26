# Template Konten Google Sites

## 1. Judul Project
**Prediksi Status Pinjaman Pelanggan Menggunakan Metode Klasifikasi**

## 2. Identitas Mahasiswa
- Nama: [Isi Nama Mahasiswa]
- NIM: [Isi NIM]
- Kelas: SI 24 SIM
- Program Studi: Sistem Informasi
- Mata Kuliah: Konsep Data Warehouse & Mining
- Dosen: Agus Rifaldi, S.Kom

## 3. Deskripsi Studi Kasus
Project ini membahas penerapan data mining dengan metode klasifikasi untuk memprediksi `status_pinjaman` pelanggan. Dataset berisi informasi profil pelanggan dan kondisi finansial, seperti usia, pekerjaan, pendapatan, skor kredit, jumlah pinjaman, suku bunga, rasio hutang, serta riwayat tunggakan.

## 4. Dataset
- Nama file: `data.csv`
- Jumlah data: 50.000 baris
- Jumlah kolom: 20 kolom
- Target klasifikasi: `status_pinjaman`
- Sumber dataset: [Isi link dataset publik asli]

## 5. Tahapan CRISP-DM

### A. Business Understanding
Tujuan project adalah membuat model klasifikasi untuk memprediksi status pinjaman pelanggan. Kriteria sukses model adalah accuracy minimal 80%.

### B. Data Understanding
Dataset dianalisis untuk mengetahui struktur data, tipe data, statistik deskriptif, missing values, duplikat, distribusi target, dan korelasi antar fitur.

### C. Data Preparation
Tahapan yang dilakukan:
- Data cleaning
- Hapus duplikat
- Handling missing values
- Membersihkan data kategorikal
- Deteksi outlier
- Encoding data kategorikal
- Normalisasi data untuk model tertentu
- Split data training dan testing 80:20

### D. Modeling
Algoritma yang dibandingkan:
- Decision Tree
- Random Forest
- Logistic Regression
- K-Nearest Neighbor

### E. Evaluation
Model terbaik adalah **Random Forest** dengan hasil:
- Accuracy: 91.23%
- Precision: 0.9123
- Recall: 0.9123
- F1-Score: 0.9122
- Cross Validation Mean: 91.39%

Hasil ini sudah memenuhi kriteria sukses minimal 80%.

### F. Deployment
Project dipublikasikan melalui Google Sites, GitHub, dan video presentasi YouTube.

## 6. Visualisasi Hasil Analisis
Masukkan gambar/screenshot berikut:
1. Distribusi target `status_pinjaman`
2. Histogram kolom numerik
3. Heatmap korelasi
4. Confusion matrix
5. Perbandingan performa model
6. Feature importance

## 7. Screenshot Coding
Masukkan screenshot bagian:
1. Import library
2. Load dataset
3. Data Understanding
4. Data Preparation
5. Modeling
6. Evaluation
7. Kesimpulan

## 8. Kesimpulan
Berdasarkan hasil evaluasi, model Random Forest menjadi model terbaik dalam memprediksi `status_pinjaman` pelanggan. Nilai accuracy sebesar 91.23% menunjukkan bahwa model sudah memenuhi kriteria sukses minimal 80% dan dapat membantu proses analisis status pinjaman pelanggan secara lebih cepat dan berbasis data.

## 9. Link Pendukung
- Link GitHub: [Isi link GitHub]
- Link YouTube: [Isi link YouTube]
