Sistem Inventaris Kantor
Sistem manajemen inventaris kantor berbasis web yang komprehensif, dirancang untuk membantu organisasi melacak dan mengelola aset kantor mereka secara efisien.

Fitur Utama
Manajemen Barang Inventaris: Tambah, lihat detail, edit, dan hapus barang inventaris. Setiap barang memiliki kode unik, nama, kategori, jumlah, lokasi, status, deskripsi, dan gambar.
Kategori Barang: Mengelola kategori untuk mengelompokkan barang inventaris, seperti Elektronik, Furniture, Alat Kantor, dll.
Manajemen Pegawai: Mengelola data pegawai termasuk nama, departemen, jabatan, email, nomor telepon, dan alamat.
Sistem Peminjaman Barang: Mencatat dan melacak peminjaman barang oleh pegawai, termasuk tanggal pinjam, tanggal kembali, tujuan, dan status peminjaman (Dipinjam, Dikembalikan, Terlambat, Menunggu).
Dashboard dengan Statistik: Menyajikan ringkasan visual data inventaris dan peminjaman melalui grafik dan kartu informasi.
Pencarian dan Filter: Fungsionalitas pencarian dan filter yang kuat pada tabel data untuk memudahkan navigasi.
Ekspor Data: Kemampuan untuk mengekspor data tabel ke format Excel, PDF, dan CSV.
QR Code Generation: Otomatis menghasilkan QR Code untuk setiap barang inventaris, yang dapat diunduh atau dicetak untuk memudahkan pelacakan.
Notifikasi Toast: Memberikan umpan balik kepada pengguna melalui notifikasi toast yang muncul di layar.
Validasi Formulir: Validasi sisi klien untuk memastikan integritas data yang dimasukkan.
Desain Responsif: Antarmuka pengguna yang menyesuaikan dengan berbagai ukuran layar perangkat.
Teknologi
Proyek ini dibangun menggunakan teknologi web standar dan beberapa pustaka pihak ketiga untuk meningkatkan fungsionalitas dan pengalaman pengguna:

Frontend:
HTML5
CSS3 (dengan styling kustom dan Bootstrap 5)
JavaScript (Vanilla JS dan jQuery)
Framework/Library CSS:
Bootstrap 5: Untuk komponen UI yang responsif dan modern.
Bootstrap Icons: Untuk ikonografi.
Library JavaScript:
jQuery 3.7.0: Untuk manipulasi DOM yang lebih mudah dan penanganan event.
DataTables 1.13.6: Untuk tabel data interaktif dengan fitur pencarian, pengurutan, paginasi, dan ekspor.
Chart.js: Untuk visualisasi data pada dashboard (grafik area dan pie).
QRCode.js: Untuk menghasilkan QR Code secara dinamis.
html2canvas: Digunakan dalam fitur cetak QR untuk mengonversi elemen HTML menjadi gambar (meskipun dalam implementasi saat ini hanya ada alert simulasi).

Penggunaan
Setelah login, Anda akan diarahkan ke Dashboard. Dari sana, Anda dapat menavigasi melalui sidebar untuk mengakses berbagai modul:

Dashboard: Melihat ringkasan statistik inventaris dan peminjaman.
Barang Inventaris: Mengelola semua barang yang terdaftar.
Kategori: Mengelola jenis-jenis kategori barang.
Pegawai: Mengelola data karyawan yang terlibat dalam peminjaman.
Peminjaman: Mencatat dan melacak riwayat peminjaman barang.
Pengaturan: (Placeholder untuk pengaturan sistem).
Profil: (Placeholder untuk profil pengguna).
