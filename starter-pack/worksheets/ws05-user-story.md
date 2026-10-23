# **WORKBOOK: LEMBAR KERJA MAHASISWA WS05**

## **Formulasi Kebutuhan Fungsional: User Story & Acceptance Criteria**

* **Mata Kuliah**: Konsep Sistem Informasi (KSI)
* **Kerangka Kerja**: Project-Based Learning (PBL) Level 1
* **Fase Learning Spine**: Fase 3 — Define (Minggu 3)
* **Sub-CPMK / SFIA**: S-01.1 (Intermediate - Problem Framing) & S-03.1 (Intermediate - Pemetaan SI) | SFIA BUSA L1, REQM L2
* **Keterkaitan Deliverable**: Bahan Utama Deliverable D2 (System & Solution Design - TPL-02)

---

### **1. Identifikasi Kelompok & Rotasi Kepemimpinan**

* **Nama Kelompok**: Syncore Team
* **Objek UMKM Mitra**: Temu Tempo kopi
* **Phase Lead 3 (Define)**: Satria Ariya Prathama (Mahasiswa C)
* **Anggota Tim**: 1. Muhammad Rasikh Zakki Aufa, 2. Ananta Rizqi Fadhlurrohman, 3. Muhammad Dhiyauddin Nur, 4. Alfin Farrel Gennaro
---

### **2. Landasan Konseptual: Analisis Sistem "What" vs "How"**

Dalam tahap Systems Analysis, fokus utama tim adalah menentukan APA (What) yang dibutuhkan pengguna bisnis untuk memecahkan masalahnya, BUKAN BAGAIMANA (How) sistem dibangun secara teknis (Marakas & O'Brien, 2013).

User Story merepresentasikan kebutuhan fungsional dari sudut pandang pengguna bisnis dengan pola:
$$\text{"Sebagai [], Saya ingin [], Sehingga []"}$$
Acceptance Criteria (Given-When-Then) mendefinisikan batas kondisi kapan sebuah fitur dinyatakan selesai dan memenuhi syarat penerimaan pengguna (Rainer et al., 2021).

---

### **3. Workspace A: Formulasi User Story Fungsional**

Petakan minimal 3 User Story Utama yang langsung menjawab akar masalah pada D1 / WS04:

#### **User Story 1 (Prioritas Utama / Rekapitulasi Otomatis)**

* **Sebagai (As a)**: Pemilik Temu Tempo Coffe(Mas joy) (misal: Kasir Toko Kelontong)
* **Saya ingin (I want to)**: Mengunggah rekap data transaksi harian dari aplikasi kasir ke spreadsheet dalam halaman transaksi agar di rekapitulisai secara otomatis tanpa rumus manual excel. (misal: mencatat transaksi penjualan dengan memilih barang dari daftar dan menghitung total otomatis)
* **Sehingga (So that)**: Dalam proses rekapitulasi dapat dilakukan lebih cepat dan mengurangi potensi terjadinya kesalahan dalam menghitung margin. (misal: waktu transaksi berkurang dan tidak terjadi kesalahan hitung uang kembalian)

#### **User Story 2 (Pemisahan Kas Usaha vs Kas Pribadi)**

* **Sebagai (As a)**: Pemilik Temu Tempo Coffe(Mas joy) (misal: Pemilik Usaha UMKM)
* **Saya ingin (I want to)**: Fasilitas untuk mencatat dan memisahkan keuangan bisnis dengan pribasi sebagai prive. (misal: melihat jumlah stok barang yang tersisa secara real-time dan mendapatkan peringatan stok menipis)
* **Sehingga (So that)**: Arus kas usaha dapat dipantau secara akurat. (misal: saya dapat melakukan pemesanan ulang barang tepat waktu sebelum stok habis)

#### **User Story 3 (Visualisai grafik dalam evaluasi)**

* **Sebagai (As a)**: Pemilik Temu Tempo Coffe(Mas joy) (misal: Pemilik Usaha UMKM)
* **Saya ingin (I want to)**: Melihat kondisi usaha dalam bentuk grafik/chart juga ringkas. (misal: melihat ringkasan total pendapatan harian dan daftar 3 barang terlaris)
* **Sehingga (So that)**: Evaluasi jauh lebih mudah dilakukan dan dapat melihat kondisi bisnis hanya dengan melihat grafik tanpa banyak angka. (misal: saya tidak perlu menghitung nota fisik secara manual selama 1.5 jam setiap malam)

---

### **4. Workspace B: Acceptance Criteria Berbasis Skenario (Given-When-Then)**

Susun kriteria penerimaan terstruktur untuk User Story 1 (mencakup Skenario Sukses dan Skenario Penanganan Eror):

#### **Skenario 1A: Transaksi Penjualan Berhasil (Happy Path)**

* **Diberikan (Given)**: Pemilik memiliki file data transaksi yang valid dalam aplikasi kasir. (misal: Kasir berada di layar utama transaksi dan stok produk "Teguk Boba" tersedia sebanyak 10 unit)
* **Ketika (When)**: Pemilik men-drag file data transaksi ke spreadsheat dalam halaman transaksi (misal: Kasir memasukkan jumlah pesanan 2 unit dan mengklik tombol bayar dengan nominal pas)
* **Maka (Then)**: Sistem merekap secara otomatis dan menampilkan keuntungan, total omzet, dan status 'Rekapitulasi Berhasil'.(misal: Sistem menampilkan bukti transaksi sukses, menghitung kembalian Rp 0, dan mengurangi stok otomatis menjadi 8 unit)

#### **Skenario 1B: Penanganan Pembayaran Kurang / Eror (Exception Path)**

* **Diberikan (Given)**: File data transaksi rusak, salah format, atau kosong. (misal: Total belanja transaksi adalah Rp 35.000)
* **Ketika (When)**: Pemilik selesai men-drag file transaksi dari aplikasi kasir dan data transaksi tercatat di colom sheet. (misal: Kasir memasukkan nominal pembayaran Rp 30.000)
* **Maka (Then)**:Sistem menolak proses, menampilkan pesan 'VALUE' dalam colom sheet, dan tidak merusak data yang sudah ada. (misal: Sistem menolak transaksi, menampilkan pesan eror "Nominal pembayaran kurang Rp 5.000", dan stok barang tidak berkurang)

---

### **5. Workspace C: Catatan Validasi Kebutuhan dengan Mitra (Field Confirmation)**

* **Tanggal Validasi**: 21 Oktober 2026 | Narahubung: Mas Joy (Pemilik)
* **Narahubung Mitra**: Pemilik (Pemilik / Staf Kasir)
* **Hasil Konfirmasi User Story**:
  - [ ] Seluruh User Story disetujui mitra
  - [ ] Terdapat penyesuaian/revisi kebutuhan (Tuliskan revisi jika ada):
    __________________________________________________________________

---

### **6. Verifikasi Integritas AI (TPL-07) & Pengesahan**

**Penggunaan AI Co-pilot:
Apakah tim menggunakan AI untuk membantu merumuskan skenario Given-When-Then? [ ] Ya  [ ] Tidak
(Jika Ya, wajib melampirkan formulir TPL-07: AI Usage Disclosure & Verification Note).**

Tanda Tangan Tim & Pengesahan Dosen:

```text
Phase Lead 3: _______________________ (Tanggal: __________)
```
```text
Dosen Coach: _______________________ (Tanggal: __________)  [ ] Approved
```
