# **WS04: Problem Identification & Scope**

**Mata Kuliah**: Konsep Sistem Informasi (KSI)  
**Kerangka Kerja**: Project-Based Learning (PBL) Level 1  
**Fase Learning Spine**: **Fase 2 — Frame (Problem Discovery & Scope)**  
**Minggu / Alokasi Waktu**: Minggu 2 / 14 Jam Belajar  
**Sub-CPMK / SFIA**: S-01.1 (Introduce - Problem Framing) | SFIA BUSA L1 (_Business Analysis_), IRMG L1  
**Penanggung Jawab Fase**: **Phase Lead 2 (Frame — Mahasiswa B)**  
**Keterkaitan Deliverable**: Sumber Utama Penyusunan **Deliverable D1 (Problem Brief - TPL-01)**

## **1\. Identifikasi Tim & Objek Proyek**

| **Elemen Informasi**          | **Rincian Identitas Kelompok & Mitra**        |
| ----------------------------- | --------------------------------------------- |
| **Nama Kelompok / Kelas**     | \[ Syncore Team / Kelas A \]                  |
| **Phase Lead 2 (Frame - M2)** | \[ Muhammad Rasikh Zakki Aufa — 2600016028 \] |
| **Nama UMKM Mitra Lapangan**  | \[ Temu Tempo Kopi \]                         |
| **Pemilik / Kontak Mitra**    | \[ Mas Joy / +62882008806986 \]               |

## **2\. Matriks Problem Framing & Analisis Akar Masalah (Root Cause Analysis)**

Gunakan temuan kuantitatif dari WS03 untuk memisahkan antara **Gejala Permukaan (_Symptoms_)** dan **Akar Masalah Utama (_Root Cause_)** operasional bisnis mitra:

| **No** | **Kategori Observasi**      | **Gejala Permukaan (_Symptoms_)**                                                                                                                                                                                                                                                                                                                                                                                                                              | **Akar Masalah Operasional (_Root Cause_)**                                                                                                                                                                                                                                                                                                                                                                                                      | **Bukti Kuantitatif (_Baseline Data_)**                                                                                                                                                                                                                                                               |
| ------ | --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1**  | **Proses Transaksi Kasir**  | Pada periode jam sibuk (*peak hour*), pelanggan berdatangan secara berkelompok sehingga menimbulkan penumpukan antrean, keterlambatan waktu penyajian pesanan, serta meningkatkan risiko terjadinya kesalahan pencatatan transaksi (*miss order*). | Keterlambatan pelayanan dan kesalahan transaksi terjadi akibat beban kerja ganda pemilik yang mengelola kasir dan meracik pesanan secara mandiri tanpa staf operasional. Kondisi ini diperparah oleh keterbatasan aplikasi kasir pada smartphone yang tidak menyediakan fitur koreksi atau edit transaksi, sehingga apabila terjadi salah klik varian produk saat kondisi kedai ramai, pemilik terpaksa menghapus seluruh transaksi dan menginput ulang dari awal yang mengakibatkan antrean pelayanan semakin tersendat. | Waktu penyajian minuman berada di bawah lima menit per pesanan sedangkan makanan berat membutuhkan sepuluh hingga lima belas menit pada jam sibuk. Kesalahan pemilihan varian pesanan terjadi sebanyak satu hingga tiga kali per minggu saat kedai ramai, dengan kondisi aplikasi kasir sama sekali tidak memiliki fitur edit transaksi. |
| **2**  | **Pengelolaan Stok Barang** | Pembelian bahan baku terutama biji kopi tidak terencana dan terjadwal secara sistematis karena hanya dilakukan saat persediaan fisik habis, serta pengambilan barang dilakukan secara mandiri tanpa layanan pengiriman dari pemasok. | Pengelolaan persediaan bahan baku belum memiliki pencatatan digital terstruktur (*stock opname*) dan hanya mengandalkan pengecekan fisik harian menjelang penutupan kedai yang kemudian dicatat pada aplikasi ponsel. Kondisi ini terjadi karena pemilik menangani seluruh operasional kedai seorang diri sehingga tidak memungkinkan melakukan rekapitulasi persediaan barang secara komprehensif setiap hari. | Pencatatan stok bahan baku saat ini belum terdigitalisasi dan masih bergantung pada pencatatan daftar belanja manual di ponsel pemilik setelah pengecekan fisik malam hari, dengan pasokan biji kopi dibeli putus rata-rata dua kilogram per minggu ke kawasan Bumijo. |
| **3**  | **Rekapitulasi Keuangan**   | Pekerjaan administrasi rekapitulasi penjualan tidak dilakukan secara harian melainkan menumpuk setiap hari Minggu, sehingga menciptakan pekerjaan berulang untuk meninjau kembali transaksi hari-hari sebelumnya dan menyita waktu libur operasional pemilik. Di samping itu, muncul masalah berupa tercampurnya transaksi keuangan operasional kedai dengan pengeluaran pribadi pemilik. | Format lembar kerja Microsoft Excel yang digunakan saat ini belum terintegrasi otomatis dan hanya memuat tabel baris angka mentah tanpa formula perhitungan otomatis. Data transaksi harus diunduh dan dipindahkan dari aplikasi kasir ke Excel, kemudian pemilik menghitung arus kas dan margin operasional secara manual. Selain itu, belum tersedianya modul atau fasilitas pencatatan transaksi pribadi yang terpisah menyebabkan dana pribadi tercampur dengan kas usaha kedai, yang diakui langsung oleh pemilik sebagai kendala operasional terbesar saat ini. | Satu hari libur operasional pemilik tersita untuk melakukan rekapitulasi dan evaluasi mingguan dengan durasi sekitar satu jam per minggu untuk memindahkan data serta menghitung margin di Excel. Berdasarkan pengakuan langsung pemilik, belum ada fasilitas pencatatan terpisah sehingga seluruh pengeluaran pribadi saat ini masih tercampur dalam kas kedai. |
| **4**  | **Analisis & Evaluasi Penjualan Menu** | Volume penjualan produk minuman kopi lebih mendominasi dibandingkan makanan berat dengan rasio harian rata-rata tiga berbanding dua. Pemilik belum memiliki visualisasi tren perbandingan penjualan antar-kategori produk untuk mengevaluasi menu terlaris seperti Nasi Goreng terhadap varian lainnya, sehingga mengalami kesulitan dalam merancang paket promosi penjualan yang tepat sasaran. | Format Microsoft Excel yang digunakan Mas Joy untuk rekap mingguan hanya berupa baris angka mentah tanpa rumus otomatis, tabel pivot, maupun visualisasi grafik perbandingan menu kopi dan makanan. Ketiadaan fitur visual ini diperberat oleh beban kerja pemilik yang mengelola kedai seorang diri selama tujuh belas jam per hari, sehingga waktu istirahat di hari Minggu telah habis untuk rekap manual dan tidak menyisakan waktu untuk mengolah grafik analitik. Akibatnya, pemilik tidak dapat memetakan jam ramai penjualan makanan berat untuk merancang strategi promosi yang efektif. | Format rekapitulasi saat ini sepenuhnya berupa tabel baris angka mentah tanpa grafik visualisasi pada lembar kerja Excel. Volume transaksi harian berada pada rasio rata-rata tiga minuman berbanding dua makanan berat berdasarkan konfirmasi observasi kedua, dengan alokasi waktu pemilik sebesar nol jam per minggu untuk melakukan evaluasi tren menu secara analitis. |

## **3\. Perumusan Problem Statement Kontekstual**

Berdasarkan analisis di atas, rumuskan **Problem Statement** utama dalam 1–2 paragraf terstruktur.  
_Petunjuk_: Hindari mendefinisikan masalah sebagai _"Mitra belum memiliki aplikasi Python/komputer"_. Definisikan dari hambatan bisnis nyata mitra!

**Rumusan Problem Statement Kelompok**:  
_"Proses operasional dan tata kelola administrasi pada **Temu Tempo Kopi** (kondisi As-Is) saat ini mengalami hambatan akibat ketergantungan penuh pada pengelolaan secara mandiri oleh pemilik tunggal (solo operator) serta ketiadaan sistem pencatatan data yang terintegrasi secara otomatis. Pada aspek pelayanan, kondisi ini menimbulkan kendala operasional berupa waktu pelayanan yang meningkat pada jam ramai (12.00–15.00 WIB dan > 20.00 WIB), terutama pada pesanan makanan berat yang membutuhkan waktu **10–15 menit**, serta risiko kesalahan pemilihan varian menu saat rombongan pelanggan datang bersamaan. Pada aspek persediaan, pembelian bahan baku utama seperti biji kopi masih dilakukan secara beli putus tanpa pencatatan stok (*stock opname*) digital, di mana kebutuhan bahan baru dicatat pada aplikasi ponsel setelah pengecekan fisik saat penutupan kedai._

_Pada aspek pencatatan keuangan dan evaluasi bisnis, ketiadaan integrasi otomatis antara aplikasi kasir dan lembar kerja Microsoft Excel memaksa pemilik mengunduh dan memindahkan data transaksi untuk dikalkulasi secara manual setiap hari Minggu. Proses berulang ini tidak hanya menyita waktu istirahat pada **1 hari libur operasional** pemilik dengan durasi **± 1 jam per minggu**, tetapi juga memicu ketidakjelasan arus kas (*cash flow*) akibat **tercampurnya transaksi bisnis kedai dengan transaksi pribadi** yang menjadi permasalahan operasional terbesar mitra. Selain itu, format pencatatan di Microsoft Excel saat ini belum menyediakan fitur dasbor visualisasi grafik tren penjualan produk, sehingga pemilik kesulitan mengevaluasi perbandingan penjualan antara minuman kopi dan makanan berat (rasio rata-rata **3 : 2 per hari**), yang menghambat perancangan strategi promosi menu secara efektif. Akibatnya, keterbatasan ini menghambat efisiensi operasional harian, mengurangi waktu istirahat pemilik, dan membatasi pengembangan bisnis mitra."_

## **4\. Menetapkan Batasan Sistem (System Boundary / Scope Alignment)**

Untuk mencegah terjadinya pembengkakan fitur (_Scope Creep_) yang membahayakan penyelesaian proyek dalam 1 semester, tentukan secara tegas apa yang **Masuk Cakupan (_In-Scope_)** dan apa yang **Di Luar Cakupan (_Out-of-Scope_)**:

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│                       SYSTEM BOUNDARY (BATASAN SISTEM)                      │
├─────────────────────────────────────────────────────────────────────────────┤
│ [ IN-SCOPE: Fitur yang Akan Dibangun ]                                      │
│ 1. Simplifikasi rekapitulasi data transaksi penjualan harian.               │
│ 2. Modul pemisah pencatatan transaksi bisnis vs pribadi (arus kas/cashflow).│
│ 3. Dasbor visualisasi produk terjual & grafik perbandingan kopi vs makanan. │
├─────────────────────────────────────────────────────────────────────────────┤
│ [ OUT-OF-SCOPE: Di Luar Cakupan Proyek ]                                    │
│ 1. Pembuatan atau perombakan total aplikasi kasir utama (POS).              │
│ 2. Otomasi pemesanan stok ke supplier luar (auto-order biji kopi).          │
│ 3. Integrasi payment gateway / QRIS otomatis langsung ke perbankan.         │
└─────────────────────────────────────────────────────────────────────────────┘
```

### **Tabel Penegasan Cakupan Proyek (*Scope Alignment Table*)**

| **No** | **Modul / Fitur Sistem**                                                          | **Status Cakupan (_In-Scope / Out-of-Scope_)** | **Alasan Pertimbangan Kelayakan (O'Brien)**                                                                                                                                                                                                    |
| ------ | --------------------------------------------------------------------------------- | ---------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1**  | Simplifikasi rekapitulisasi data transaksi                             | **IN-SCOPE**                                   | Kelayakan Ekonomi dan Operasional: Menyederhanakan proses rekapitulasi manual yang selama ini menyita **1 hari libur operasional** (~1 jam/minggu) yang dilakukan oleh pemilik usaha.                                                            |
| **2**  | Modul Pemisah Transaksi Bisnis dan Transaksi Pribadi                              | **IN-SCOPE**                                   | Kelayakan Operasional: Menyelesaikan akar masalah tercampurnya transaksi pribadi dan bisnis yang merusak pencatatan arus kas (_cash flow)._                                                                                                    |
| **3**  | Dasbor Visualisasi & Grafik Produk Terjual serta Grafik Perbandingan Antar Produk | **IN-SCOPE**                                   | Kelayakan Informasi (Value of Information): Menyediakan grafik penjualan menu (kopi dan makanan) untuk membantu pemilik mengevaluasi strategi promosi yang sudah mereka lakukan selama ini. Menyediakan grafik mengenai trend penjualan dan alur masuknya keuangan(cashflow).                                                    |
| **4**  | Pengembangan Aplikasi Kasir / POS Baru                                            | **OUT-OF-SCOPE**                               | **Keterbatasan Waktu:** Mitra tetap akan menggunakan aplikasi kasir yang sudah ada, sedangkan proyek berfokus pada pengolahan data dan integrasi _output_ ke Spreadsheet.                                                                      |
| **5**  | Payment Gateway & Pemesanan Supplier Otomatis                                     | **OUT-OF-SCOPE**                               | **Kompleksitas PBL Level 1:** Membatasi risiko keterlambatan proyek 1 semester.Transaksi dan pembelian bahan baku akan tetap dilakukan secara terpisah oleh pemilik tanpa adanya campur tangan dari Solusi yang nantinya akan kami kembangkan. |

## **5\. Target Metrik Keberhasilan Solusi (To-Be Targets)**

Tentukan target kuantitatif perbaikan yang ingin dicapai melalui solusi sistem informasi To-Be:

| **Indikator Kinerja**                                             | **Kondisi As-Is (Baseline)**                                                                                                                                                                                         | **Target To-Be (Expected)**                                                                           | **Estimasi Persentase Peningkatan**                                                                                                                                                                |
| ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Durasi Rekapitulasi & Evaluasi Penjualan**                      | **± 60 menit / minggu** _(Data kasir dipindahkan dan dihitung margin operasional secara manual di Excel; menyita 1 hari libur operasional)_                                                                                                                 | **< 5 menit / minggu** _(Menyederhanakan proses pemindahan dan kalkulasi data transaksi di spreadsheet)_ | **Penghematan Waktu > 90%** _(Mengembalikan waktu istirahat pada hari libur pemilik serta menyajikan hasil rekapitulasi penjualan harian secara otomatis)._                        |
| **Akurasi Keberhasilan Pemisahan Transaksi Bisnis & Pribadi**     | **Belum adanya pemisahan transaksi** _(Transaksi pribadi belum dicatat dan masih tercampur dengan transaksi bisnis)_                                                                                                 | Transaksi bisnis dan pribadi dapat terpisah secara rapi lewat pilihan kategori di Spreadsheet         | Arus kas (cash flow) kedai jadi lebih jelas dan tidak terdapat adanya kebocoran dana                                                                                                               |
| **Akurasi & Respon Analisis Penjualan Menu dan Bisnis** | **Manual & Belum Ada Grafik Visual di Excel** _(Format Microsoft Excel pemilik saat ini hanya berupa tabel baris angka mentah tanpa grafik terstruktur untuk melihat tren produk terlaris atau perbandingan penjualan kopi vs makanan. Belum ada visualisasi kondisi arus kas bisnis.)_ | **Visualisasi Otomatis & Terstruktur** _(Grafik tren produk terjual dan perbandingan kopi vs makanan disajikan otomatis dalam Dasbor Spreadsheet)_ | Pemilik bisa langsung menganalisis perbandingan menu terlaris secara visual tanpa perlu mengolah data manual di Excel. Ini membantu pemilik mengevaluasi dan merancang ulang strategi promosi atau paket bundling. |
| **Tingkat Kesalahan Input Data Keuangan (** **Human Error** **)** | **Kemungkinan terjadinya cukup tinggi** _(Berpotensi timbul sebuah kesalahan akibat rekap berulang secara manual)_                                                                                                   | **Akurasi Data Meningkat** _(Penginputan data transaksi dilakukan secara lebih sederhana dan mudah.)_                    | Penurunan Risiko Kesalahan Input Keuangan secara Signifikan                                                                                                                                        |

## **6\. Refleksi & Lembar Pengesahan Phase Lead**

### **A. Pertanyaan Refleksi Tim**

1. _Bagaimana tim memastikan bahwa batasan proyek yang ditetapkan realistis untuk diselesaikan dalam 16 minggu?_
   - **Jawab**: Tim menerapkan prinsip *Problem Framing* dan kerangka kelayakan O'Brien dengan membatasi ruang lingkup pada masalah operasional yang paling mendesak, yaitu efisiensi rekapitulasi data penjualan harian/mingguan dan pemisahan pencatatan kas bisnis vs pribadi. Fitur-fitur berisiko tinggi seperti pembuatan aplikasi POS baru dari awal, integrasi *payment gateway*, dan otomasi supplier secara tegas dinyatakan *Out-of-Scope*. Dengan memfokuskan solusi pada pengolahan data pasca-transaksi dan penyajian dasbor analitik berbasis spreadsheet terstruktur, alokasi waktu 16 minggu sangat realistis untuk diselesaikan hingga tahap pengujian UAT mitra.
2. _Apakah pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok?_
   - **Jawab**: Ya, pemilik usaha (Mas Joy) telah menyetujui batasan sistem ini dalam sesi wawancara dan observasi lapangan. Pemilik sangat mendukung pembuatan alat bantu rekapitulasi penjualan serta modul pemisahan keuangan bisnis dan pribadi yang selama ini menyita waktu libur operasional hari Minggunya, tanpa harus merombak aplikasi kasir yang saat ini sudah berjalan.

### **B. Tanda Tangan Pengesahan Phase Lead 2**

Disusun oleh Phase Lead 2 (Frame): Muhammad Rasikh Zakki Aufa — 2600016028

```
Tanggal Penyusunan: 14 Oktober 2026
Tanda Tangan Phase Lead 2: ____________________
Diverifikasi oleh Dosen Pengampu / Coach:
Tanggal: [ Tanggal ] | Status Checkpoint: [ APPROVED / REVISION NEEDED ]
Catatan Dosen: __________________________________________________
```


---

## **7. Bukti Lapangan**

Seluruh bukti visual proses diskusi kelompok dalam perumusan lingkup masalah dan batasan sistem disimpan pada Google Drive dan folder lokal assets sebagai bukti autentik:

| No | Jenis Bukti | Tautan |
|:---:|---|---|
| 1 | **Foto Dokumentasi Diskusi Tim (Problem Framing & Scope)** | [Tautan Google Drive](https://drive.google.com/file/d/19rnISSlrCiLKP37QYFv9CBwdRUbRdj2H/view?usp=sharing) <br> [File Lokal](../assets/foto_diskusi_ws04.jpg) |
