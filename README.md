# JatahKu — Capstone Project Web UI/UX Developer

JatahKu adalah aplikasi web manajemen keuangan pribadi yang membantu pengguna mengatur jatah bulanan, mengontrol batas (limit) pengeluaran, dan memantau riwayat transaksi secara real-time.

Repositori ini berisi dokumentasi spesifikasi produk (PRD), design tokens, dan struktur kolaborasi Git sebagai fondasi sebelum tahap pengembangan kode (coding) pada Modul 7.

## Profil Kelompok & Pembagian Peran

- **Nama Tim:** Kelompok 8
- **Kelas / Program:** Web UI/UX Developer — Studi Independen

| Anggota | Peran / Jobdesk | Tanggung Jawab Utama | Akun GitHub |
|---|---|---|---|
| Adinda Dewi Ardhianti | PIC 1 - Repo Maintainer & Scope Author | Setup Repository, PRD Bagian 1 & 2, Review PR #2 | @adindaardhiantyy |
| Fadhillah Rizqia Arfin | PIC 2 - Tech Lead & Documentation | PRD Bagian 3, README.md, Review PR #1 | @Fadhillahrizqia |

## Aset Desain & Prototipe Figma

- **Figma Prototype (Modul 5):** Tugas4_Kelompok8_JatahKu
- **Figma Variables (Design Tokens):** Primitive & Semantics
- **Jumlah Layar / Frame:** 12 Frame (dari Home Page hingga 06 - Konfirmasi Hapus).
- **Design System:** Figma Variables dua lapis, yaitu koleksi Primitive (45 variabel) dan Semantics (41 variabel).

## Struktur Repositori

```text
capstone-jatahku/
├── .gitignore
├── PRD.md
├── README.md
└── docs/
    └── .gitkeep
```

## Standard Operating Procedure (Git Workflow)

1. Setiap penambahan dokumen atau fitur wajib dibuat melalui branch terpisah.
2. Tidak diperbolehkan melakukan push langsung ke branch main setelah commit inisialisasi.
3. Penggabungan perubahan ke branch main harus melalui Pull Request (PR).
4. Setiap PR wajib mendapatkan minimal satu komentar inline review dan approval dari rekan tim.
5. Commit menggunakan standar Conventional Commits, seperti `docs:`, `chore:`, `feat:`, dan `fix:`.
