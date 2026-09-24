# Data Entry & Data Cleaning

## Deskripsi Proyek

Proyek ini merupakan simulasi pekerjaan **Data Entry dan Data Cleaning** untuk mengelola data pelanggan sebuah perusahaan.

Dataset terdiri dari **515 data pelanggan sintetis** yang sengaja dibuat dengan beberapa permasalahan umum pada data, seperti data duplikat, informasi yang kosong, format nomor telepon yang tidak konsisten, serta perbedaan format tanggal dan penulisan kota.

Tujuan proyek ini adalah menunjukkan kemampuan dalam **memasukkan, memeriksa, membersihkan, menstandarkan, dan memvalidasi data** menggunakan Microsoft Excel.

> Seluruh data dalam proyek ini merupakan data sintetis dan tidak menggunakan informasi pribadi dari individu sebenarnya.

---

## Tujuan

Proyek ini dibuat untuk mensimulasikan proses pengelolaan data pelanggan sebelum data digunakan untuk kebutuhan administrasi atau operasional.

Proses yang dilakukan meliputi:

* Memeriksa kelengkapan dan konsistensi data
* Mengidentifikasi data duplikat
* Menemukan data yang kosong atau tidak valid
* Menstandarkan format data
* Melakukan validasi data
* Melakukan pemeriksaan kualitas sebelum data difinalisasi

---

## Struktur Data

Dataset memiliki 9 kolom utama:

| Kolom             | Keterangan             |
| ----------------- | ---------------------- |
| Customer ID       | ID unik pelanggan      |
| Full Name         | Nama lengkap pelanggan |
| Email             | Alamat email           |
| Phone             | Nomor telepon          |
| City              | Kota pelanggan         |
| Registration Date | Tanggal registrasi     |
| Gender            | Jenis kelamin          |
| Customer Type     | Jenis pelanggan        |
| Status            | Status pelanggan       |

---

## Permasalahan pada Data

Data mentah sengaja dibuat menyerupai kondisi yang dapat ditemukan dalam pekerjaan administrasi sehari-hari, antara lain:

* Data pelanggan duplikat
* Email yang kosong atau tidak valid
* Nomor telepon dengan format berbeda
* Nama kota dengan penulisan yang tidak konsisten
* Format tanggal yang berbeda
* Spasi yang tidak diperlukan pada data teks
* Beberapa field yang tidak terisi

Contoh:

```text
Data Mentah
jakarta
JAKARTA
DKI Jakarta

        ↓

Data Setelah Standardisasi
Jakarta
```

Contoh lainnya:

```text
Data Mentah
0812-3456-789
+628123456789
0812 3456 789

        ↓

Data Setelah Standardisasi
08123456789
```

---

## Proses Pengerjaan

Proses pengolahan data dilakukan melalui tahapan berikut:

```text
Data Mentah
    ↓
Pemeriksaan Data
    ↓
Identifikasi Kesalahan
    ↓
Cleaning & Standardisasi
    ↓
Validasi
    ↓
Quality Control
    ↓
Data Final
```

Setiap tahap dilakukan untuk memastikan data yang dihasilkan memiliki format yang konsisten, lengkap, dan siap digunakan.

---

## Tools yang Digunakan

* **Microsoft Excel**
* **CSV**
* Data Validation
* Filtering & Sorting
* Conditional Formatting
* Excel Formulas

---

## Struktur Repository

```text
customer-data-entry-project/
│
├── README.md
│
├── data/
│   ├── raw_customer_data.csv
│   └── cleaned_customer_data.csv
│
├── excel/
│   └── customer_data_cleaning.xlsx
│
├── documentation/
│   └── data_quality_checklist.pdf
│
└── screenshots/
    ├── raw_data.png
    ├── cleaning_process.png
    └── final_result.png
```

### Keterangan File

**`raw_customer_data.csv`**
Data pelanggan sebelum dilakukan proses cleaning.

**`customer_data_cleaning.xlsx`**
File utama yang digunakan untuk melakukan pemeriksaan, cleaning, standardisasi, dan validasi data.

**`cleaned_customer_data.csv`**
Dataset setelah proses cleaning dan validasi selesai.

**`data_quality_checklist.pdf`**
Checklist yang digunakan untuk memastikan data telah melalui pemeriksaan kualitas.

---

## Hasil yang Diharapkan

Setelah proses cleaning selesai, dataset diharapkan memiliki:

* Format data yang konsisten
* Data duplikat yang telah ditangani
* Data kosong dan tidak valid yang telah diidentifikasi
* Format nomor telepon dan tanggal yang seragam
* Penulisan data yang lebih terstandarisasi
* Struktur data yang siap digunakan untuk kebutuhan administrasi atau operasional

---

## Keahlian yang Ditunjukkan

**Data Entry · Data Cleaning · Data Validation · Data Standardization · Quality Control · Microsoft Excel · Data Management · Attention to Detail**

---

### Catatan

Proyek ini merupakan **dummy project/simulasi** yang dibuat untuk kebutuhan portofolio. Seluruh data pelanggan bersifat sintetis dan tidak mewakili individu atau organisasi sebenarnya.
