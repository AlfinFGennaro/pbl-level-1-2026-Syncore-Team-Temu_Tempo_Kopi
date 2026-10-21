# **WORKBOOK: LEMBAR KERJA MAHASISWA (WS07)**

## **Simple Solution Design — IPO, Flowchart & Pseudocode**

---

### **INFORMASI UTAMA**

* **Mata Kuliah**: Konsep Sistem Informasi (KSI)
* **Kerangka Kerja**: Project-Based Learning (PBL) Level 1
* **Learning Moment**: Fase 4: Design (Minggu 5–6)
* **Sub-CPMK / SFIA**: S-03.1 (Intermediate) | SFIA ARCH L2, DESN L2
* **Keterkaitan Deliverable**: Sumber utama pembuatan Deliverable D2 (System & Solution Design - TPL-02)
* **Phase Lead**: Mahasiswa D (Phase Lead 4 — Design)

---

### **RUANG KERJA TIM (WORKSPACE)**

#### **1. IDENTIFIKASI KELOMPOK & SOLUSI**

* **Nama Tim**: __________________________________________________
* **Nama UMKM Mitra**: __________________________________________________
* **Judul Solusi SI**: __________________________________________________
* **Phase Lead 4 (Design)**: __________________________________________________

#### **2. PEMETAAN ARSITEKTUR 4 LAPISAN SI (M05)**

Petakan solusi Anda ke dalam 4 lapisan arsitektur terintegrasi:

| Lapisan Arsitektur | Komponen Solusi Tim | Keterangan & Batasan |
| --- | --- | --- |
| 1. Process Layer (Alur Kerja To-Be) | __________________________________________________ | Alur transaksi kasir To-Be yang lebih efisien dibanding As-Is. |
| 2. Data Layer (Struktur Data Logis) | __________________________________________________ | Entitas data: Tabel Menu/Produk, Tabel Transaksi, & Tabel Stok. |
| 3. Application Layer (Modul Program) | __________________________________________________ | Modul Utama: Login, Input Transaksi, Hitung Total/Diskon, & Rekap. |
| 4. Infrastructure Layer (Perangkat Fisik) | __________________________________________________ | Hardware: Laptop/Tablet POS; Net: Wi-Fi/4G; OS: Windows/Android. |

#### **3. SPESIFIKASI IPO (INPUT - PROCESSING - OUTPUT - STORAGE - CONTROL)**

##### **Fitur Fungsional Utama 1: [Tuliskan Nama Fitur, misal: Pencatatan Transaksi Penjualan]**

* **Input**: __________________________________________________
* **Processing**: __________________________________________________
* **Output**: __________________________________________________
* **Storage**: __________________________________________________
* **Control (Error Handling)**: __________________________________________________

##### **Fitur Fungsional Utama 2: [Tuliskan Nama Fitur, misal: Rekapitulasi Laporan Laba Harian]**

* **Input**: __________________________________________________
* **Processing**: __________________________________________________
* **Output**: __________________________________________________
* **Storage**: __________________________________________________
* **Control (Error Handling)**: __________________________________________________

#### **4. DIAGRAM ALIR (FLOWCHART) LOGIKA PROGRAM**

Petunjuk: Gambarkan diagram alir terstruktur menggunakan simbol standar (Persegi Panjang = Proses, Belah Ketupat = Keputusan IF-ELSE, Jajar Genjang = Input/Output, Oval = Start/End). Lampirkan hasil gambaran digital/foto kertas A3 di bawah ini.

```text
[ TEMPELKAN GAMBAR DIAGRAM FLOWCHART DIGITAL / FOTO DRAF A3 DI SINI ]
```

#### **5. PSEUDOCODE TERSTRUKTUR (INDEPENDEN TEKNOLOGI)**

Tuliskan kode semu terstruktur (pseudocode) untuk modul logika utama solusi Anda:

```text
ALGORITMA Transaksi_Kasir_Teguk
KAMUS DATA:
   kode_produk, nama_produk : STRING
   harga, jumlah, subtotal, total_bayar, uang_tunai, kembalian : REAL
   stok_tersedia : INTEGER

ALUR LOGIKA:
   START
   READ kode_produk, jumlah
   
   IF stok_tersedia >= jumlah THEN
      subtotal = harga * jumlah
      total_bayar = subtotal
      PRINT total_bayar
      
      READ uang_tunai
      IF uang_tunai >= total_bayar THEN
         kembalian = uang_tunai - total_bayar
         stok_tersedia = stok_tersedia - jumlah
         PRINT "Transaksi Sukses", kembalian
         UPDATE Tabel_Stok, Tabel_Transaksi
      ELSE
         PRINT "ERROR: Uang tunai kurang!"
      ENDIF
   ELSE
      PRINT "ERROR: Stok tidak mencukupi!"
   ENDIF
   END
```

---

### **CHECKLIST REFLEKSI & PENGESAHAN WS07**

* [ ] Arsitektur 4 lapisan SI telah terdefinisi konsisten.
* [ ] Tabel IPO mencakup kriteria Storage dan Control (penanganan eror).
* [ ] Flowchart menggambarkan logika percabangan (IF-ELSE) dan perulangan (Loops) tanpa infinite loop.
* [ ] Pseudocode terstruktur dengan rapi dan independen terhadap bahasa pemrograman.
* [ ] Form TPL-07 (AI Usage Disclosure & Verification Note) telah dilampirkan.

```text
Tanggal Pengesahan: ____________________
Tanda Tangan Phase Lead 4 (Design): ____________________
Tanda Tangan Dosen Pembimbing / Coach: ____________________
```