# WS07 — Simple Solution Design (IPO, Flowchart & Pseudocode)

**Worksheet Number**: WS07  
**Title**: Desain Solusi Sederhana (Input-Proses-Output, Flowchart & Pseudocode)  
**Mata Kuliah**: Konsep Sistem Informasi (KSI) & Dasar Pemrograman  
**Kerangka Kerja**: Project-Based Learning (PBL) Level 1  
**Learning Moment**: Design (Minggu 5–7)  
**Penanggung Jawab Fase**: Phase Lead 4 (Design — Satria Ariya Prathama)  
**Tujuan**: Merancang alur logika solusi sederhana secara terstruktur sebelum penulisan kode program dimulai.  
**Related Learning Outcome**: CPMK-01; Sub-CPMK S-01.1, S-03.1 (I); SFIA PROG L1.  
**Related Deliverable**: D2 (bagian desain) → fondasi D3.  
**Related Module**: M06.  

---

## 1. Identifikasi Tim & Objek Proyek

| Elemen Informasi | Rincian Identitas |
|---|---|
| **Nama Kelompok / Kelas** | Syncore Team / Kelas A |
| **Phase Lead 4 (Design)** | Satria Ariya Prathama — 2600016023 |
| **Nama UMKM Mitra** | Temu Tempo Kopi |
| **Pemilik / Kontak Mitra** | Mas Joy / +62882008806986 |

---

## 2. Activity

1. Tulis spesifikasi Input-Proses-Output (IPO) untuk modul/fitur utama sistem.
2. Gambarkan *flowchart* alur program sederhana (Mulai → Input → Proses/Keputusan → Output → Selesai).
3. Tuliskan *pseudocode* terstruktur untuk setiap alur utama program.
4. Review desain bersama tim dan siapkan untuk sesi *critique* (WS08).

---

## 3. Workspace

### A. Spesifikasi Komponen IPO Fitur Utama

- **Input**:
  - `tanggal_transaksi` (string / datetime)
  - `kategori_transaksi` ("Bisnis" / "Pribadi")
  - `nama_item` (string: nama produk minuman / makanan)
  - `harga_satuan` (float / integer)
  - `jumlah_terjual` (integer)
- **Proses**:
  - Validasi kelengkapan data masukan
  - Hitung total transaksi: `total = harga_satuan * jumlah_terjual`
  - Tambahkan baris data baru ke file penyimpanan
  - Perbarui kalkulasi omzet harian dan saldo kas terpisah
- **Output**:
  - Konfirmasi penyimpanan data sukses
  - Tampilan ringkasan transaksi baru
  - Laporan rekapitulasi data dan grafik visualisasi menu

### B. Flowchart Alur Program

*(Simpan file diagram/gambar visual di folder `assets/flowchart-desain.png`)*

```
[Mulai]
   │
   ▼
[Tampilkan Menu Utama]
   │
   ├──▶ 1. Input Transaksi Penjualan ──▶ Pilih Kategori (Bisnis/Pribadi) ──▶ Simpan ke CSV
   │
   ├──▶ 2. Lihat Rekap Penjualan     ──▶ Filter Periode & Hitung Total   ──▶ Tampilkan Rekap
   │
   ├──▶ 3. Tampilkan Grafik Menu     ──▶ Agregasi Data Penjualan Menu   ──▶ Render Visual
   │
   └──▶ 0. Keluar Program
```

### C. Pseudocode Program Utama

```text
ALGORITMA Pengelolaan_Transaksi_Temu_Tempo
DEKLARASI:
    pilihan : integer
    kategori, nama_item : string
    harga, jumlah, subtotal : real
    lanjut : boolean

DESKRIPSI:
    lanjut <- TRUE
    SELAMA lanjut = TRUE LAKUKAN
        TAMPILKAN "=== SISTEM PENCATATAN & REKAP TEMU TEMPO KOPI ==="
        TAMPILKAN "1. Tambah Transaksi Penjualan"
        TAMPILKAN "2. Rekap Penjualan & Laporan Kas (Bisnis vs Pribadi)"
        TAMPILKAN "3. Visualisasi Grafik Penjualan Menu"
        TAMPILKAN "0. Keluar"
        INPUT pilihan

        JIKA pilihan = 1 MAKA
            INPUT kategori  // "Bisnis" atau "Pribadi"
            INPUT nama_item, harga, jumlah
            subtotal <- harga * jumlah
            SIMPAN_KE_CSV(tanggal_hari_ini, kategori, nama_item, harga, jumlah, subtotal)
            TAMPILKAN "Data berhasil disimpan!"
        LAIN JIKA pilihan = 2 MAKA
            BACA_DATA_CSV()
            HITUNG_TOTAL_DAN_PISAHKAN_KAS()
            TAMPILKAN_LAPORAN_REKAP()
        LAIN JIKA pilihan = 3 MAKA
            BUAT_GRAFIK_PRODUK_TERLARIS()
        LAIN JIKA pilihan = 0 MAKA
            lanjut <- FALSE
            TAMPILKAN "Terima kasih."
        LAIN
            TAMPILKAN "Pilihan tidak valid!"
        AKHIR JIKA
    AKHIR SELAMA
AKHIR ALGORITMA
```

---

## 4. Reflection

- Bagian mana dari rancangan logika alur program yang paling berisiko menimbulkan kesalahan (*bug*) saat implementasi?
  - **Jawab**: _
- Bagaimana desain alur ini memastikan pemenuhan kriteria penerimaan yang telah dirumuskan pada WS05?
  - **Jawab**: _

---

## 5. Checklist Kelulusan WS07

- [ ] Spesifikasi Input-Proses-Output (IPO) terdokumentasi lengkap.
- [ ] Flowchart alur program telah digambar dan disimpan di folder `assets/`.
- [ ] Pseudocode logika program telah disusun secara terstruktur.
- [ ] Desain siap dipresentasikan pada sesi *Peer Critique I* (WS08).

---

**Status**: ⬜ Draf → ⬜ Review Tim → ⬜ Sesi Critique → ⬜ Final (Gate 1)
