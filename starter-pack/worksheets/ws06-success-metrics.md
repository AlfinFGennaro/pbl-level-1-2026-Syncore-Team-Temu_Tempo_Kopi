# WS06 — Success Metrics & Component Mapping

**Worksheet Number**: WS06  
**Title**: Metrik Keberhasilan (*Success Metric*) & Pemetaan Komponen SI  
**Mata Kuliah**: Konsep Sistem Informasi (KSI)  
**Kerangka Kerja**: Project-Based Learning (PBL) Level 1  
**Learning Moment**: Define (Minggu 3–4)  
**Penanggung Jawab Fase**: Phase Lead 3 (Define — Satria Ariya Prathama)  
**Tujuan**: Menentukan *success metric* solusi dan memetakan komponen sistem informasi yang terlibat (Input-Proses-Output-Data).  
**Related Learning Outcome**: CPMK-01; Sub-CPMK S-02.1 (I); SFIA BUSA L1, IRMG L1.  
**Related Deliverable**: D2 (System & Solution Design — TPL-02).  
**Related Module**: M04, M05.  

---

## 1. Identifikasi Tim & Objek Proyek

| Elemen Informasi | Rincian Identitas |
|---|---|
| **Nama Kelompok / Kelas** | Syncore Team / Kelas A |
| **Phase Lead 3 (Define)** | Satria Ariya Prathama — 2600016023 |
| **Nama UMKM Mitra** | Temu Tempo Kopi |
| **Pemilik / Kontak Mitra** | Mas Joy / +62882008806986 |

---

## 2. Activity

1. Tetapkan 2–3 *success metrics* utama untuk masalah terpilih (merujuk pada target To-Be di WS04).
2. Buat peta konsep komponen SI sederhana untuk solusi: *User - Input - Proses - Output - Data/Penyimpanan*.
3. Hubungkan setiap komponen ke kebutuhan D2.
4. Identifikasi peran pengguna (*User*) dari sistem solusi.

---

## 3. Workspace

### A. Tabel Target Metrik Keberhasilan (*Success Metrics*)

| # | Indikator Metrik | Baseline (Kondisi As-Is) | Target To-Be (Expected) | Cara Mengukur |
|---|---|---|---|---|
| 1 | Durasi Rekapitulasi Penjualan Mingguan | 60–90 menit / minggu (manual, menyita 1 hari libur) | < 5 menit / minggu | Uji waktu ekspor/rekapitulasi data menggunakan stopwatch |
| 2 | Pemisahan Kas Bisnis vs Pribadi | 0% (transaksi masih tercampur dan belum ada pemisahan) | 100% terpisah dan terdata rapi | Pemeriksaan laporan kas bisnis vs pribadi |
| 3 | Penyajian Visualisasi Menu Terlaris | Manual (tidak ada visualisasi) | Otomatis tersaji dalam dasbor grafik | Verifikasi tampilan grafik terhadap data riil |

### B. Pemetaan Komponen Sistem Informasi (Peta Konsep IPO)

```
[INPUT]                     [PROSES]                   [OUTPUT]
Data Transaksi     ──▶  Kategorisasi & Filter   ──▶  Ringkasan Rekap Harian
Data Pengeluaran        Kalkulasi Total               Laporan Cash Flow Bisnis/Pribadi
Kategori (Bisnis/Pribadi)                             Visualisasi Grafik Menu
       │                                                      ▲
       └──────────────▶   [DATA / PENYIMPANAN]  ──────────────┘
                          File CSV / Spreadsheet
```

- **User**: Pemilik dan Pengelola Temu Tempo Kopi (Mas Joy)
- **Input**: Data transaksi penjualan (tanggal, nama produk, harga, jumlah, metode bayar) & jenis transaksi (Bisnis/Pribadi)
- **Proses**: Pemilahan kategori transaksi, kalkulasi subtotal/omzet, dan agregasi data penjualan menu
- **Output**: Tabel rekapitulasi penjualan berkala, laporan saldo kas terpisah, serta grafik batang/lingkaran produk terlaris
- **Data / Penyimpanan**: File rekaman data terstruktur (`.csv` / spreadsheet) yang mudah dibaca ulang

---

## 4. Reflection

- Metrik mana yang paling dapat dibuktikan dan diukur dengan data riil di lapangan?
  - **Jawab**: _
- Bagian mana dari komponen SI (Input, Proses, Output, atau Penyimpanan) yang paling menantang untuk dirancang?
  - **Jawab**: _

---

## 5. Checklist Kelulusan WS06

- [ ] 2–3 *success metrics* ditetapkan dengan baseline dan target yang jelas.
- [ ] Peta komponen SI sederhana (Input - Proses - Output - Data) selesai dibuat.
- [ ] Hubungan komponen dengan kebutuhan solusi di D2 terpetakan.
- [ ] Dokumen siap disintesis ke Deliverable D2 (*Section 3 & 4*).

---

**Status**: ⬜ Draf → ⬜ Review Tim → ⬜ Validasi Pemilik → ⬜ Final (Gate 1)
