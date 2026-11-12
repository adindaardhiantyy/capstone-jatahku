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

# 3. TECH STACK PLAN, TOKENS & COMPONENTS (PIC 2)

## 3.1 Rencana Teknologi (Modul 7 Prep)

- **Markup:** HTML5 Semantik (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`).
- **Styling:** CSS3 Murni dengan Pendekatan BEM / Modular CSS dan Sistem Kisi 8-Piksel (8pt Grid System).
- **Scripting / Logika:** JavaScript ES6+ (DOM Manipulation, State Management sederhana, Event Listeners).
- **Aksesibilitas Target:** Lolos Standar WCAG 2.2 AA (rasio kontras warna minimal 4.5:1 untuk teks normal).

## 3.2 Design Tokens (Dipetakan dari Figma Variables)

Figma JatahKu memakai dua koleksi variabel: Primitive (nilai mentah, 45 variabel) dan Semantics (peran/penggunaan, 41 variabel yang merujuk ke Primitive). Struktur dua lapis yang sama akan digunakan pada CSS di Modul 7.

### A. Koleksi Primitive

| Grup | Token | Nilai |
|---|---|---|
| color/neutral | 0, 50, 100, 200, 300 | #FFFFFF, #F8FAFC, #F1F5F9, #E2E8F0, #CBD5E1 |
| color/neutral | 400, 500, 600, 700, 800, 900 | #94A3B8, #64748B, #475569, #334155, #1E293B, #0F172A |
| color/blue | 50, 100, 600, 700, 800 | #EFF6FF, #DBEAFE, #2563EB, #1D4ED8, #1E40AF |
| color/red | 50, 100, 700, 800 | #FEF2F2, #FEE2E2, #B91C1C, #991B1B |
| color/green | 50, 100, 700, 800 | #F0FDF4, #DCFCE7, #15803D, #166534 |
| color/amber | 50, 100, 700, 800 | #FFFBEB, #FEF3C7, #B45309, #92400E |
| space | 0, 4, 8, 12, 16, 24, 32, 40, 48, 64, 80 | Dalam px |
| radius | 4, 8, 12, 18, full | 4, 8, 12, 16, 999 px |
| shadows | default | #FFFFFF |

### B. Koleksi Semantics (41 variabel, alias ke Primitive)

| Grup | Token = Alias ke Primitive |
|---|---|
| color/bg | page = neutral/50; surface = neutral/0; subtle = neutral/100; inverse = neutral/900 |
| color/text | primary = neutral/900; secondary = neutral/600; placeholder = neutral/500; inverse = neutral/0; on-action = neutral/0; link = blue/700 |
| color/border | default = neutral/200; input = neutral/500; focus = blue/600 |
| color/action | primary = blue/600; primary-hover = blue/700; primary-pressed = blue/800; disabled-bg = neutral/100; disabled-text = neutral/500 |
| color/feedback | danger = red/700; danger-text = red/700; danger-bg = red/50; success-text = green/800; success-bg = green/100; success-icon = green/700; warning-text = amber/800; warning-bg = amber/100; warning-icon = amber/700 |
| space/padding | xs = space/4; sm = space/8; md = space/16; lg = space/24; xl = space/32 |
| space/gap | xs = space/4; sm = space/8; md = space/16; lg = space/24; section = space/40 |
| radius | control = radius/8; card = radius/12; modal = radius/16 (nama Figma: 18); fill = radius/full |

### C. Implementasi Design Tokens di CSS (:root)

```css
:root {
  /* PRIMITIVE - warna */
  --color-neutral-0: #FFFFFF;
  --color-neutral-50: #F8FAFC;
  --color-neutral-100: #F1F5F9;
  --color-neutral-200: #E2E8F0;
  --color-neutral-300: #CBD5E1;
  --color-neutral-400: #94A3B8;
  --color-neutral-500: #64748B;
  --color-neutral-600: #475569;
  --color-neutral-700: #334155;
  --color-neutral-800: #1E293B;
  --color-neutral-900: #0F172A;

  --color-blue-50: #EFF6FF;
  --color-blue-100: #DBEAFE;
  --color-blue-600: #2563EB;
  --color-blue-700: #1D4ED8;
  --color-blue-800: #1E40AF;

  --color-red-50: #FEF2F2;
  --color-red-100: #FEE2E2;
  --color-red-700: #B91C1C;
  --color-red-800: #991B1B;

  --color-green-50: #F0FDF4;
  --color-green-100: #DCFCE7;
  --color-green-700: #15803D;
  --color-green-800: #166534;

  --color-amber-50: #FFFBEB;
  --color-amber-100: #FEF3C7;
  --color-amber-700: #B45309;
  --color-amber-800: #92400E;

  /* PRIMITIVE - space (px) */
  --space-0: 0;
  --space-4: 4px;
  --space-8: 8px;
  --space-12: 12px;
  --space-16: 16px;
  --space-24: 24px;
  --space-32: 32px;
  --space-40: 40px;
  --space-48: 48px;
  --space-64: 64px;
  --space-80: 80px;

  /* PRIMITIVE - radius */
  --radius-4: 4px;
  --radius-8: 8px;
  --radius-12: 12px;
  --radius-16: 16px;
  --radius-full: 999px;

  /* SEMANTICS - warna */
  --color-bg-page: var(--color-neutral-50);
  --color-bg-surface: var(--color-neutral-0);
  --color-bg-subtle: var(--color-neutral-100);
  --color-bg-inverse: var(--color-neutral-900);

  --color-text-primary: var(--color-neutral-900);
  --color-text-secondary: var(--color-neutral-600);
  --color-text-placeholder: var(--color-neutral-500);
  --color-text-inverse: var(--color-neutral-0);
  --color-text-on-action: var(--color-neutral-0);
  --color-text-link: var(--color-blue-700);

  --color-border-default: var(--color-neutral-200);
  --color-border-input: var(--color-neutral-500);
  --color-border-focus: var(--color-blue-600);

  /* SEMANTICS - action */
  --color-action-primary: var(--color-blue-600);
  --color-action-primary-hover: var(--color-blue-700);
  --color-action-primary-pressed: var(--color-blue-800);
  --color-action-disabled-bg: var(--color-neutral-100);
  --color-action-disabled-text: var(--color-neutral-500);

  /* SEMANTICS - feedback */
  --color-feedback-danger: var(--color-red-700);
  --color-feedback-danger-text: var(--color-red-700);
  --color-feedback-danger-bg: var(--color-red-50);
  --color-feedback-success-text: var(--color-green-800);
  --color-feedback-success-bg: var(--color-green-100);
  --color-feedback-success-icon: var(--color-green-700);
  --color-feedback-warning-text: var(--color-amber-800);
  --color-feedback-warning-bg: var(--color-amber-100);
  --color-feedback-warning-icon: var(--color-amber-700);

  /* SEMANTICS - space */
  --padding-xs: var(--space-4);
  --padding-sm: var(--space-8);
  --padding-md: var(--space-16);
  --padding-lg: var(--space-24);
  --padding-xl: var(--space-32);

  --gap-xs: var(--space-4);
  --gap-sm: var(--space-8);
  --gap-md: var(--space-16);
  --gap-lg: var(--space-24);
  --gap-section: var(--space-40);

  /* SEMANTICS - radius */
  --radius-control: var(--radius-8);
  --radius-card: var(--radius-12);
  --radius-modal: var(--radius-16);
  --radius-fill: var(--radius-full);
}
```

**Catatan Pemetaan ke Desain:** Tombol utama memakai action/primary (hover dan pressed memakai blue/700 dan blue/800), tombol nonaktif memakai disabled-bg dan disabled-text, serta field fokus memakai border/focus. Warna cokelat-oranye pada Pengeluaran Bulan Ini, border Error Page, dan teks tombol Hapus sesuai dengan palet feedback/warning (amber), sedangkan tombol Ya, Hapus memakai warning-bg (amber/100). Palet feedback/danger (red/700) disiapkan untuk status error yang sebenarnya.

## 3.3 Komponen Reusable (Target Implementasi Modul 7)

1. **Button Component:** Varian primary (action/primary, state :hover dan :active memakai primary-hover dan primary-pressed), secondary (abu, misalnya Batal), outline (Hapus), warning (Ya, Hapus), dan disabled (action/disabled-bg dan disabled-text).
2. **Form Input Group:** Form field dengan state default (border/input), focus (border/focus), dan error (disertai pesan pembantu).
3. **Transaction Card:** Kartu ringkasan transaksi dengan slot dinamis untuk nama transaksi, tanggal, dan nominal.
4. **Confirmation Card:** Kartu konfirmasi reusable untuk layar 06 - Konfirmasi Hapus (pertanyaan, teks peringatan, serta tombol Batal dan Ya, Hapus).
5. **Summary Card:** Kartu ringkasan angka (Total Pengeluaran, Jumlah Transaksi, Sisa Saldo) yang dipakai di 02 - Riwayat Pengeluaran dan panel saldo di Beranda.

## 3.4 Standardisasi Pesan Commit (Conventional Commits)

- **feat:** Penambahan fitur baru / section dokumen baru.
- **docs:** Perubahan atau penambahan pada dokumentasi (PRD.md, README.md).
- **chore:** Pengaturan repositori (.gitignore, struktur folder).
- **fix:** Perbaikan kesalahan penulisan atau bug pada repositori.

**Akhir Dokumen — Bagian 1, 2, dan 3 (PIC 1 & PIC 2)**
