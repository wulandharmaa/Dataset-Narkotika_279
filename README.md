<p align="center">
  <img src="https://img.icons8.com/color/150/000000/law.png" alt="Law Icon" width="100">
</p>

<h1 align="center">Dataset Putusan Pengadilan: Kasus Narkotika</h1>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Dataset-50_Dokumen-blue.svg" alt="Dataset"></a>
  <a href="#"><img src="https://img.shields.io/badge/Format-PDF%20%7C%20XLSX-success.svg" alt="Format"></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Completed-brightgreen.svg" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Lembaga_Peradilan-PN_Serang-orange.svg" alt="Lembaga"></a>
</p>

##  Tentang Dataset

**Dataset Putusan Pengadilan (Narkotika)** adalah kumpulan data historis yang memuat 50 dokumen putusan resmi dari Pengadilan Negeri Serang terkait tindak pidana penyalahgunaan dan peredaran gelap narkotika dalam rentang tahun 2023-2026. 

Dataset ini disusun untuk mempermudah peneliti, mahasiswa hukum, maupun praktisi data dalam melakukan analisis teks hukum (*Legal Tech*), ekstraksi informasi, atau studi komparatif mengenai amar putusan dan barang bukti pada kasus narkotika di Indonesia.

##  Struktur Direktori

Repositori ini disusun dengan struktur yang rapi agar mudah dipahami dan dinavigasi:

```text
 Nama-Repository
├──  Dataset/
│   └──  Narkotika.zip       # Berisi 50 dokumen putusan pengadilan asli dalam format *.pdf
├──  Overview/
│   └──  Overview.xlsx       # Ringkasan/Summary dari ke-50 putusan dalam format Excel
└──  README.md               # Dokumentasi dataset (file ini)
```

##  Struktur Data (Overview.xlsx)

File `Overview.xlsx`  menyajikan ringkasan informasi eksekutif dari 50 dokumen PDF. Data disusun dalam bentuk tabular dengan struktur kolom sebagai berikut:

| Nama Kolom | Tipe Data | Penjelasan |
| :--- | :---: | :--- |
| **No** | *Integer* | Nomor urut data (1 hingga 50). |
| **No Putusan** | *String* | Nomor register putusan resmi dari pengadilan. |
| **Lembaga Peradilan** | *String* | Nama institusi pengadilan yang mengeluarkan putusan. |
| **Barang Bukti** | *Text* | Rincian barang bukti yang disita dalam persidangan (seperti jenis narkotika, berat netto, dan barang elektronik yang disita). |
| **Amar Putusan** | *Text* | Keputusan akhir majelis hakim, meliputi durasi pidana penjara, besaran denda pidana, subsider, hingga status barang bukti. |

##  Cara Penggunaan Dataset

Anda dapat mengunduh atau melakukan *cloning* pada repositori ini untuk keperluan analisis data atau penelitian akademis.

### 1. Menggunakan Git
Jalankan perintah berikut di terminal Anda:
```bash
git clone [https://github.com/wulandharmaa/Dataset-Narkotika_279.git](https://github.com/wulandharmaa/Dataset-Narkotika_279.git)
```

### 2. Ekstraksi Dokumen PDF
* Masuk ke folder `Dataset/`
* Ekstrak file `Narkotika.zip` menggunakan *software* kompresi.
* 50 dokumen PDF putusan pengadilan siap untuk dibaca atau diolah menggunakan metode *Natural Language Processing* (NLP).

##  Disclaimer & Lisensi

Dataset ini merupakan kompilasi dari putusan pengadilan yang bersifat **informasi publik**. Seluruh data yang ada di dalam repositori ini dikumpulkan semata-mata untuk **tujuan akademis, penelitian, dan edukasi**. Pengguna diharapkan menggunakan data ini secara bijak dan bertanggung jawab.

---
<p align="center">
  Dibuat oleh <b>wulandharmaa</b> untuk keperluan penyelesaian tugas.
</p>
