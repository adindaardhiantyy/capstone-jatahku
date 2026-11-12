# PRODUCT REQUIREMENTS DOCUMENT (PRD) — JATAHKU

**Nama Produk:** JatahKu (Personal Financial & Allowance Management App)  
**Versi Dokumen:** 1.0  
**Tim Penyusun:** Adinda Dewi Ardhianti dan Fadhillah Rizqia Arfin  
**Nama Tim:** Kelompok 8  
**Program:** Web UI/UX Developer — Studi Independen

---

# 1. PRODUCT OVERVIEW (PIC 1)

## 1.1 Latar Belakang dan Masalah

Banyak individu dan mahasiswa mengalami kesulitan dalam mengontrol pengeluaran harian sehingga uang bulanan yang dimiliki sering kali habis sebelum akhir bulan.

Masalah utama yang dihadapi meliputi:

1. Kurangnya visibilitas terhadap sisa jatah uang harian maupun bulanan secara real-time.
2. Pencatatan transaksi secara manual yang dianggap rumit dan kurang fleksibel.
3. Tidak adanya mekanisme peringatan atau pengaturan batas pengeluaran (limit) yang membantu pengguna mengontrol keuangan.

Aplikasi JatahKu hadir sebagai solusi berupa aplikasi web manajemen keuangan pribadi yang membantu pengguna mencatat pengeluaran, memantau riwayat transaksi, menetapkan batas pengeluaran, serta mengedit data transaksi secara intuitif.

## 1.2 Tujuan Produk

Tujuan pengembangan aplikasi JatahKu adalah:

1. Menyediakan dashboard visual (Beranda) yang menampilkan informasi sisa jatah uang secara transparan.
2. Memfasilitasi pengelolaan transaksi secara menyeluruh, mulai dari mencatat pengeluaran, melihat detail, mengedit data, hingga menghapus transaksi melalui halaman konfirmasi.
3. Menerapkan fitur pengaturan batas pengeluaran melalui fitur Atur Limit.
4. Membantu pengguna memahami dan mengontrol pola pengeluaran secara lebih teratur.

## 1.3 User Persona

| Atribut | Detail Target Pengguna |
|---|---|
| Nama (Fiktif) | Aditia Pratama |
| Usia / Pekerjaan | 21 Tahun / Mahasiswa & Freelancer |
| Perangkat Utama | Laptop / Mobile Browser (Web Responsive) |
| Kebutuhan | Mengetahui sisa uang bulanan dan mencatat pengeluaran dengan cepat |
| Tujuan | Mengelola keuangan pribadi agar pengeluaran tidak melebihi anggaran |
| Permasalahan | Sulit memantau sisa uang dan sering lupa mencatat transaksi |
| Ekspektasi | Tampilan sederhana, informatif, dan mudah digunakan |

### Kebutuhan Pengguna

Pengguna membutuhkan aplikasi yang dapat:

- Menampilkan sisa jatah uang secara jelas.
- Mempermudah pencatatan pengeluaran.
- Menampilkan riwayat transaksi.
- Mengubah dan menghapus transaksi.
- Mengatur limit pengeluaran sesuai kebutuhan.

---

# 2. FIGMA BREAKDOWN & USER FLOW (PIC 1)

## 2.1 Breakdown 12 Frame Figma

Berikut merupakan pembagian 12 frame pada desain prototipe Figma JatahKu:

| No. | Nama Frame | Fungsi |
|---|---|---|
| 1 | Home Page | Halaman awal aplikasi JatahKu. |
| 2 | Login Page | Halaman masuk bagi pengguna yang telah memiliki akun. |
| 3 | 01 - Beranda JatahKu | Menampilkan dashboard dan informasi keuangan pengguna. |
| 4 | 02 - Riwayat Pengeluaran | Menampilkan daftar riwayat transaksi pengeluaran. |
| 5 | 03 - Catat Pengeluaran | Memfasilitasi pengguna untuk mencatat transaksi baru. |
| 6 | 04 - Detail Pengeluaran | Menampilkan informasi detail transaksi yang dipilih. |
| 7 | 05 - Edit Pengeluaran | Memfasilitasi perubahan data transaksi. |
| 8 | 06 - Konfirmasi Hapus | Menampilkan konfirmasi sebelum transaksi dihapus. |
| 9 | Atur Limit Page | Memfasilitasi pengaturan batas pengeluaran. |
| 10 | Profile Page | Menampilkan informasi profil pengguna. |
| 11 | Error Page | Menampilkan informasi kesalahan, termasuk kesalahan username atau password. |
| 12 | Register Page | Halaman pendaftaran akun pengguna baru. |

## 2.2 User Flow Aplikasi

Alur penggunaan aplikasi JatahKu dirancang agar pengguna dapat mengakses fitur utama secara mudah dan terstruktur.

### A. Alur Registrasi dan Login

1. Pengguna membuka Home Page.
2. Pengguna memilih Login Page atau Register Page.
3. Pengguna memasukkan informasi akun.
4. Sistem melakukan validasi data.
5. Jika data benar, pengguna diarahkan menuju Beranda JatahKu.
6. Jika data salah, sistem menampilkan Error Page.

### B. Alur Pengelolaan Pengeluaran

1. Pengguna masuk ke halaman Beranda JatahKu.
2. Pengguna memilih menu Catat Pengeluaran.
3. Pengguna memasukkan informasi transaksi.
4. Pengguna menyimpan transaksi.
5. Transaksi ditampilkan pada Riwayat Pengeluaran.
6. Pengguna dapat membuka Detail Pengeluaran.
7. Pengguna dapat memilih Edit Pengeluaran untuk mengubah data.
8. Pengguna dapat memilih Hapus dan melakukan konfirmasi melalui Konfirmasi Hapus.

### C. Alur Pengaturan Limit

1. Pengguna membuka halaman Atur Limit.
2. Pengguna menentukan batas pengeluaran.
3. Pengguna menyimpan pengaturan limit.
4. Informasi batas pengeluaran digunakan sebagai acuan dalam mengontrol keuangan.

### D. Alur Profil Pengguna

1. Pengguna membuka menu Profile.
2. Sistem menampilkan informasi profil pengguna.

---

**Akhir Dokumen — Bagian 1 dan 2 (PIC 1)**