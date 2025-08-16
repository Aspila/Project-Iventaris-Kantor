@@ -1 +1,25 @@
# Project-Iventaris-Kantor
# Sistem Inventaris Kantor

Sistem manajemen inventaris kantor berbasis web dengan fitur lengkap.

## Fitur Utama
- Manajemen barang inventaris
- Kategori barang
- Manajemen pegawai
- Sistem peminjaman barang
- Dashboard dengan statistik

## Teknologi
- HTML5, CSS3, JavaScript
- Bootstrap 5
- DataTables
- Chart.js

## Instalasi
1. Clone repository ini
2. Buka file `login.html` di browser
3. Login dengan:
   - Username: `admin`
   - Password: `admin123`

## Struktur Folder
iventaris_kantor/
├── assets/
│   ├── css/
│   │   ├── custom.css      # Gaya CSS kustom aplikasi
│   │   └── style.css       # Gaya CSS utama aplikasi (termasuk variabel dan responsif)
│   ├── js/
│   │   ├── chart.js        # Skrip inisialisasi dan update Chart.js
│   │   ├── custom.js       # Skrip JavaScript kustom untuk fungsionalitas spesifik form
│   │   └── script.js       # Skrip JavaScript utama untuk fungsionalitas umum sistem
│   └── img/                # (Direktori placeholder untuk gambar, tidak ada di konteks)
├── categories/
│   ├── add.html            # Halaman untuk menambah kategori baru
│   ├── edit.html           # Halaman untuk mengedit kategori yang sudah ada
│   └── index.html          # Halaman daftar kategori
├── employees/
│   ├── add.html            # Halaman untuk menambah data pegawai baru
│   ├── edit.html           # Halaman untuk mengedit data pegawai yang sudah ada
│   └── index.html          # Halaman daftar pegawai
├── items/
│   ├── add.html            # Halaman untuk menambah barang inventaris baru
│   ├── edit.html           # Halaman untuk mengedit barang inventaris yang sudah ada
│   ├── index.html          # Halaman daftar barang inventaris
│   └── view.html           # Halaman detail barang inventaris
├── loans/
│   ├── add.html            # Halaman untuk menambah data peminjaman baru
│   ├── index.html          # Halaman daftar peminjaman
│   └── view.html           # Halaman detail peminjaman
├── profile/                # (Direktori placeholder untuk halaman profil, tidak ada di konteks)
├── settings/               # (Direktori placeholder untuk halaman pengaturan, tidak ada di konteks)
├── index.html              # Halaman dashboard utama
└── login.html              # Halaman login
