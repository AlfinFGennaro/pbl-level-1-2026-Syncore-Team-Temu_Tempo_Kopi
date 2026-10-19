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
| **1**  | **Proses Transaksi Kasir**  | Pada jam sibuk atau _peak hour_ pelanggan berdatangan secara berkelompok dan bersamaan sehingga memungkinkan untuk terjadi keterlambatan pelayanan dan potensi kesalahan pesanan (_miss order_).                                                                                                                                                                                                                                                               | Penanganan transaksi dan pembuatan pesanan sebagian besar ditangani, dikelola, dan dikerjakan sendiri oleh pemilik, sehingga ketika tiba – tiba ada pelanggan yang datang langsung dalam jumlah banyak pasti akan kewalahan yang memungkinkan terjadinya kesalahan pesanan dan waktu tunggu pesanan menjadi cukup lama.                                                                                                                          | Rata-rata waktu transaksi = **5 - 10 menit / orang** bisa jauh lebih lama ketika semakin banyak pelanggan atau konsumen yang datang. antrean pesanan akan menumpuk saat rombongan (~10 orang) datang bersamaan.                                                                                       |
| **2**  | **Pengelolaan Stok Barang** | Pembelian bahan baku terutama biji kopi tidak terencana dan terjadwal (hanya dilakukan saat persediaan habis) dan pengambilan barang dilakukan mandiri tanpa pengiriman dari supplier.                                                                                                                                                                                                                                                                         | Belum ada pencatatan stok (stock opname) secara terstruktur dan otomatis serta rekap stok barang dilakukan secara mingguan. Ini juga terjadi karena pemilik masih mengurus semua operasional secara sendiri sehingga rekap stok tidak akan memungkinkan jika dilakukan setiap hari setelah kedai tutup.                                                                                                                                          | Pencatatan dan rekap stok bahan baku (stock opname) masih belum sama sekali terdigitalisasi dan sistematis. Pemilik masih mengandalkan ingatan dan mendata langsung dikepala sehingga apabila sekiranya bahan baku sudah mau habis, ia baru melakukan stok ulang pemesanan.                           |
| **3**  | **Rekapitulasi Keuangan**   | Pekerjaan administrasi seperti rekapitulasi penjualan tidak dilakukan secara harian melainkan mingguan pada setiap hari Minggu, ini membuat adanya pekerjaan yang bersifat berulang karena harus mereview dan meninjau kembali setiap transaksi penjualan di hari – hari sebelumnya, serta waktu hari libur tersita untuk melakukan evaluasi mingguan.Ditambah lagi terdapat gejala yang timbul berupa tercampurnya transaksi bisnis dengan transaksi pribadi. | Data dari aplikasi kasir tidak terintegrasi otomatis, sehingga harus diketik ulang secara manual ke Ms.Excel. Dengan rekapitulasi masih manual dan dilakukan secara mingguan, proses atau sistem kerja seperti ini menambah pekerjaan administrasi dan berpotensi menimbulkan kesalahan input. Untuk masalah tercampurnya transaksi bisnis dan pribadi disebabkan karena belum terdapat pemisaha antara pencatatan transaksi bisnis dan pribadi. | **1 hari libur operasional** tersita untuk rekapitulasi dan evaluasi mingguan secara manual.Waktu yang diperlukan setiap minggu untuk rekapitulasi penjualan kurang lebih 1 jam berdasarkan kesaksian pemilik. Dari kesakisan pemilik atau pengelola ia tidak melakukan pencatatan transaksi pribadi. |

## **3\. Perumusan Problem Statement Kontekstual**

Berdasarkan analisis di atas, rumuskan **Problem Statement** utama dalam 1–2 paragraf terstruktur.  
_Petunjuk_: Hindari mendefinisikan masalah sebagai _"Mitra belum memiliki aplikasi Python/komputer"_. Definisikan dari hambatan bisnis nyata mitra!

**Rumusan Problem Statement Kelompok**:  
_"Proses operasional dan administrasi pada_ **_Temu Tempo Kopi_** _(kondisi As-Is) saat ini mengalami kendala akibat ketergantungan penuh pada pengelolaan secara mandiri oleh pemilik usaha serta ketiadaan sistem pencatatan yang terintegrasi secara otomatis. Pada aspek pelayanan, hal ini menciptakan bottleneck berupa durasi transaksi yang lambat (_ **_5–10 menit per orang_** _) dan penumpukan antrean pesanan yang membuat waktu tunggu pesanan cukup lama saat rombongan pelanggan (_ **_~10 orang_** _) datang bersamaan, yang berpotensi memicu kesalahan pesanan ( miss order ). Di samping itu, pembelian bahan baku khususnya biji kopi masih dilakukan secara spontan atau mendadak ketika barang habis saja, tanpa adanya pencatatan stok (stock opname) secara digital dan sistematis dan hanya mengandalkan ingatan, sehingga jadwal pembelian bahan baku menjadi tidak terencana._

_Pada aspek keuangan, belum terintegrasi secara otomatis antara data aplikasi kasir dan Ms. Excel, memaksa pemilik melakukan rekapitulasi penjualan secara manual setiap minggu. Proses manual yang berulang dengan meninjau ulang setiap transaksi di hari-hari sebelumnya tidak hanya memicu risiko kesalahan input data, tetapi juga menyita_ **_1 hari libur operasional_** _pemilik dengan durasi rekapitulasi_ **_~1 jam/minggu_** _serta memicu ketidakjelasan arus kas (Cash Flow) akibat belum terpisahnya pencatatan transaksi bisnis dan pribadi. Akibatnya, keterbatasan ini menghambat efisiensi operasional harian, mengurangi waktu istirahat pemilik, dan membatasi potensi pertumbuhan dan perkembangan bisnis mitra."_

## **4\. Menetapkan Batasan Sistem (System Boundary / Scope Alignment)**

Untuk mencegah terjadinya pembengkakan fitur (_Scope Creep_) yang membahayakan penyelesaian proyek dalam 1 semester, tentukan secara tegas apa yang **Masuk Cakupan (_In-Scope_)** dan apa yang **Di Luar Cakupan (_Out-of-Scope_)**:

 ┌───────────────────────────────────────────┐

│ SYSTEM BOUNDARY (BATASAN SISTEM) │

│ │

│ \[ IN-SCOPE: Fitur yang Akan Dibangun \] │

│ 1. Mempermudah mitra dalam rekapitulisasi data transaksi. │

│ 2. Modul pemisah transaksi antara transaksi bisnis dan pribadi untuk menjaga arus kas (cash flow). │

│ 3. Dasbor visulisasi penjualan,dapat berupa grafik produk terjual / perbandingan penjualan kopi dan makanan. │

│─────────────────────────────────────────── │

│ │

│ \[ OUT-OF-SCOPE: Di Luar Cakupan Proyek \] │

│ 1. Pengubahan / pembuatan ulang aplikasi kasir utama (POS). │

│ 2. Pemesanan stok secara otomatis (auto order) ke supplier luar atau supplier bahan baku (biji kopi). │

│ 3. Integrasi payment gateway / QRIS otomatis di dalam spreadsheet. │ └────────────────────────────────────────────┘

### **Tabel Penegasan Cakupan Proyek (*Scope Alignment Table*)**

| **No** | **Modul / Fitur Sistem**                                                          | **Status Cakupan (_In-Scope / Out-of-Scope_)** | **Alasan Pertimbangan Kelayakan (O'Brien)**                                                                                                                                                                                                    |
| ------ | --------------------------------------------------------------------------------- | ---------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1**  | Integrasi & Sinkronisasi Data Kasir ke Spreadsheet                                | **IN-SCOPE**                                   | Kelayakan Ekonomi dan Operasional: Mengeliminasi proses rekapitulasi manual yang selama ini menyita **1 hari libur operasional** (~1 jam/minggu) yang dilakukan oleh pemilik usaha.                                                            |
| **2**  | Modul Pemisah Transaksi Bisnis dan Transaksi Pribadi                              | **IN-SCOPE**                                   | Kelayakan Operasional: Menyelesaikan akar masalah tercampurnya transaksi pribadi dan bisnis yang merusak pencatatan arus kas (_cash flow)._                                                                                                    |
| **3**  | Dasbor Visualisasi & Grafik Produk Terjual serta Grafik Perbandingan Antar Produk | **IN-SCOPE**                                   | Kelayakan Informasi (Value of Information): Menyediakan grafik penjualan menu (kopi dan makanan) untuk membantu pemilik mengevaluasi strategi promosi yang sudah mereka lakukan selama ini.                                                    |
| **4**  | Otomatisasi Rekap Penjualan & Stok                                                | **IN-SCOPE**                                   | Kelayakan Teknis: Mengurangi _human error_ berupa kesalahan input maupun adanya transaksi yang terlewat untuk didata akibat masih dilakukan secara ketik manual dan memperbaiki pencatatan stok yang sebelumnya hanya mengandalkan ingatan     |
| **5**  | Pengembangan Aplikasi Kasir / POS Baru                                            | **OUT-OF-SCOPE**                               | **Keterbatasan Waktu:** Mitra tetap akan menggunakan aplikasi kasir yang sudah ada, sedangkan proyek berfokus pada pengolahan data dan integrasi _output_ ke Spreadsheet.                                                                      |
| **6**  | Payment Gateway & Pemesanan Supplier Otomatis                                     | **OUT-OF-SCOPE**                               | **Kompleksitas PBL Level 1:** Membatasi risiko keterlambatan proyek 1 semester.Transaksi dan pembelian bahan baku akan tetap dilakukan secara terpisah oleh pemilik tanpa adanya campur tangan dari Solusi yang nantinya akan kami kembangkan. |

## **5\. Target Metrik Keberhasilan Solusi (To-Be Targets)**

Tentukan target kuantitatif perbaikan yang ingin dicapai melalui solusi sistem informasi To-Be:

| **Indikator Kinerja**                                             | **Kondisi As-Is (Baseline)**                                                                                                                                                                                         | **Target To-Be (Expected)**                                                                           | **Estimasi Persentase Peningkatan**                                                                                                                                                                |
| ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Durasi Rekapitulasi & Evaluasi Penjualan**                      | **60–90 menit / minggu** _(Diketik manual satu per satu ke Excel; menyita 1 hari libur operasional)_                                                                                                                 | **< 5 menit / minggu** _(dapat merekap secara otomatis saat Spreadsheet dibuka / sudah disinkronkan)_ | **Penghematan Waktu > 90%** _(Mengembalikan waktu istirahat atau hari libur pemilik secara penuh serta pemilik bisa langsung melihat hasil rekap penjualan setiap harinya._                        |
| **Akurasi Keberhasilan Pemisahan Transaksi Bisnis & Pribadi**     | **Belum adanya pemisahan transaksi** _(Transaksi pribadi belum dicatat dan masih tercampur dengan transaksi bisnis)_                                                                                                 | Transaksi bisnis dan pribadi dapat terpisah secara rapi lewat pilihan kategori di Spreadsheet         | Arus kas (cash flow) kedai jadi lebih jelas dan tidak terdapat adanya kebocoran dana                                                                                                               |
| **Akurasi & Respon Analisis Penjualan Menu (Kopi dan Makanan)**   | **Manual & belum terdapat visual atau grafiknya** _(Masih dilakukan secara manual serta tidak ada grafik terstruktur untuk melihat produk mana yang paling laku dan perbandingan antara penjualan makanan dan kopi)_ | **Real-Time & Otomatis** _(Grafik produk terjual disajikan otomatis dalam Dasbor Spreadsheet)_        | Pemilik bisa menganalisis menu paling laku yang dilihat secara langsung tanpa adanya rekap manual.Ini juga akan membantu pemilik Menyusun ulang strategi promosi yang sudah diterapkan sebelumnya. |
| **Tingkat Kesalahan Input Data Keuangan (** **Human Error** **)** | **Kemungkinan terjadinya cukup tinggi** _(Berpotensi timbul sebuah kesalahan akibat rekap berulang secara manual)_                                                                                                   | **Akurasi Data > 99%** _(Data ditarik otomatis dari kasir tanpa pengetikan ulang)_                    | Penurunan Risiko Kesalahan Input Keuangan secara Signifikan                                                                                                                                        |

## **6\. Refleksi & Lembar Pengesahan Phase Lead**

### **A. Pertanyaan Refleksi Tim**

1. _Bagaimana tim memastikan bahwa batasan proyek yang ditetapkan realistis untuk diselesaikan dalam 16 minggu?_
   - **Jawab**: \[ Jelaskan analisis kelayakan teknis dan kemampuan tim \]
2. _Apakah pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok?_
   - **Jawab**: \[ Jelaskan hasil konfirmasi awal ke mitra \]

### **B. Tanda Tangan Pengesahan Phase Lead 2**

Disusun oleh Phase Lead 2 (Frame): \[ Nama Mahasiswa B — NIM \]

```
Tanggal Penyusunan: [ 14 Oktober 2026 ]
Tanda Tangan Phase Lead 2: ____________________
Diverifikasi oleh Dosen Pengampu / Coach:
Tanggal: [ Tanggal ] | Status Checkpoint: [ APPROVED / REVISION NEEDED ]
Catatan Dosen: __________________________________________________
```


