Website Majelis Ta'lim Anwarul Musyaffa' — Prototipe

Cara menjalankan


Buka index.html menggunakan Chrome, Edge, atau browser modern lain.

Tekan Login Anggota untuk mencoba area anggota.

Pilih salah satu akun demo untuk memeriksa menu dan hak akses.

Di area anggota, coba Arus Kas, Kegiatan Rutin, Donatur, Generator Surat, Kartu Anggota, dan (khusus Ketua) Kelola Role.


Website prototipe ini mandiri: CSS, JavaScript, ilustrasi logo, dan QR demo telah ditanam di file HTML. Tidak membutuhkan Tailwind CDN atau pustaka eksternal.


Akun demo


Ketua: Muhammad Bagas Nugraha

Pimpinan: Al Habib Segaf bin Husin Assegaff

Bendahara: Zihabul Asy'ari

Jama'ah: Septiawan Nur Yahya


Login demo hanya berupa pemilih profil, tanpa verifikasi kata sandi.


Fitur yang tersedia dalam prototipe


Landing page publik dan profil pengurus.

Jadwal kegiatan contoh.

Rekap arus kas pemasukan, pengeluaran, dan saldo dengan data ilustrasi; tambah, edit, hapus, dan ekspor CSV sesuai izin demo.

Form pendaftaran jama'ah dan minat donatur.

Menu yang menyesuaikan role, plus pembuat role kustom dengan checkbox izin.

Generator Surat Tugas, Surat Jalan, dan Surat Pemberitahuan/Undangan; cetak atau Simpan sebagai PDF melalui dialog cetak browser, serta ekspor TXT.

Kartu anggota digital dengan QR ID demo; unggah foto profil, unduh PNG, atau cetak/Simpan sebagai PDF.

Tata letak responsif desktop, tablet, dan ponsel.


Batasan sebelum dipakai resmi

Ini adalah prototipe frontend, bukan sistem produksi. Transaksi, agenda, donatur, role, foto, dan pengajuan formulir sebagian disimpan menggunakan localStorage pada browser yang sedang dipakai; data tersebut tidak tersinkron antarperangkat dan bukan database bersama. Angka kas, statistik publik, dan jadwal awal merupakan data demo yang perlu diganti/diverifikasi.


Role-based access control pada file ini hanya simulasi UI/JavaScript. Jangan gunakan untuk menyimpan informasi keuangan atau data pribadi yang sebenarnya sebelum menambahkan backend dan memvalidasi izin di server.


Agar siap digunakan secara resmi, hubungkan aplikasi ke backend (misalnya Google Apps Script + Google Spreadsheet atau server/database), buat autentikasi dan otorisasi server-side, aktivasi email/WhatsApp reset lewat penyedia resmi, validasi dan pencatatan audit, HTTPS, backup, serta kebijakan privasi. Kop surat perlu dilengkapi alamat dan kontak resmi; jadwal perlu dikonfirmasi pengurus.

