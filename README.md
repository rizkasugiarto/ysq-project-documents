# PROJEK MANAJEMEN YAYASAN SAHABAT QUR'AN

## Pendahuluan
Yayasan Sahabat Quran (YSQ) merupakan lembaga pendidikan yang berdedikasi tinggi dalam pengajaran Al-Quran. Seiring dengan perkembangannya, YSQ menghadapi tantangan dalam manajemen operasional karena sebagian besar proses masih dilakukan secara manual. Proses-proses kunci seperti pendaftaran siswa, penjadwalan kelas, pencatatan kehadiran, hingga pemantauan progres belajar masih bergantung pada pencatatan fisik dan aplikasi perkantoran standar (seperti Google Forms dan Spreadsheet). Ketergantungan pada metode manual ini tidak hanya memakan waktu tetapi juga rentan terhadap kesalahan manusia (human error), yang dapat menghambat efisiensi dan skalabilitas layanan pendidikan yang ditawarkan. Untuk mengatasi tantangan tersebut dan mendukung visi yayasan, diperlukan sebuah sistem manajemen terpusat berbasis teknologi. Proyek ini diusulkan untuk merancang dan membangun sebuah aplikasi manajemen berbasis web yang dapat mengotomatisasi dan mengintegrasikan proses-proses operasional utama di YSQ.

# Tujuan
Mengotomatisasi proses pendaftaran, penjadwalan, dan absensi.
Meningkatkan efisiensi pengelolaan data santri, pengajar, dan kelas.
Menyediakan platform yang mudah digunakan bagi semua pihak terkait.

# Fitur Utama
FR.001 – Manajemen Pengguna & Otentikasi Mencakup proses login, logout, dan manajemen hak akses berdasarkan peran (Admin, Staf, Pengajar, dan Santri).
FR.002 – Registrasi Peserta (Santri Baru) Fitur untuk pendaftaran santri melalui formulir publik serta verifikasi dan aktivasi akun oleh Admin.
FR.003 – Manajemen Kelas & Penempatan Santri Pengelolaan data kelas, penambahan, penghapusan, serta pemindahan santri antar kelas.
FR.004 – Manajemen Jadwal Pelajaran Fitur untuk membuat dan mengelola jadwal belajar mengajar berdasarkan kelas dan pengajar.
FR.005 – Manajemen Kehadiran (Absensi) Mencatat kehadiran santri dan pengajar dengan status Hadir, Izin, Sakit, atau Alpha, serta menghasilkan laporan kehadiran dasar.

# Fitur tambahan
FR.006 – Manajemen Tugas & Materi Ajar Pengunggahan materi ajar dan penugasan online untuk santri.
FR.007 – Pencatatan Nilai & Progres Belajar Input nilai ujian, rapor digital, dan pelacakan progres hafalan.
FR.008 – Manajemen Rapor Digital Pembuatan dan ekspor rapor otomatis dalam format PDF.
FR.009 – Manajemen Tagihan & Kas Iuran Pembuatan dan pengelolaan tagihan otomatis serta pencatatan iuran.
FR.010 – Verifikasi Pembayaran & Bukti Transfer Fitur upload bukti transfer dan validasi pembayaran oleh staf keuangan.
FR.011 – Perhitungan Gaji Pengajar Modul perhitungan honor pengajar berdasarkan jadwal dan kehadiran.
FR.012 – Laporan Keuangan Otomatis Laporan keuangan terintegrasi berdasarkan transaksi yang tercatat.
FR.013 – Manajemen Event Insidental Modul pengelolaan kegiatan non-rutin seperti parenting, seminar, dan lomba.

# Struktur Folder
📦 ysq-projek-document/
│
├── Administrasi/
│   ├── Surat-Proyek/
│   ├── Proposal/
│   ├── Kontrak-Kerja/ (opsional)
│   └── Anggaran/ (opsional)
│
├── Perencanaan/
│   ├── Timeline-Project/
│   ├── Requirement-Document/
│   │     ├── FR-TS-001-Login-Aplikasi.pdf
│   │     ├── FR-TS-002-Registrasi.pdf
│   │     └── ... dst
│   ├── Use-Case/
│   │     └── Usecase-Diagram-YSQ.png
│   ├── Flowchart/
│   └── Rencana-Risiko/
│
├── Analisis/
│   ├── Analisis-Kebutuhan/
│   ├── Analisis-Data/
│   │     ├── Data-Pengajar.csv
│   │     └── ... dst
│   ├── Spesifikasi-Sistem/
│   ├── Study-Literatur/
│   └── ERD-Analisis-YSQ.png
│
├── Desain/
│   ├── Wireframe/ (opsional)
│   ├── UI-UX/ (opsional)
│   ├── ERD/
│   ├── Database-Schema/
│   │     └── Database-Schema-YSQ.png
│   └── Arsitektur-Sistem/
│         └── Architecture-System-YSQ.png
│
└── 

# Teknologi yang digunakan
HTML
Tailwind CSS
JavaScript/React sederhana
PostgreSQL 17
Docker Compose Volume

# Struktur Tim
Project Manager & System Analyst (Rizka)
Back-end & Database Developer (Fikri)
Front-end & UI/UX Developer (Nisa)
Quality Assurance & Documentation (Jingga)
