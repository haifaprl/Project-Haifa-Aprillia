# Project-Haifa-Aprillia
Tugas kuliah Permrograman Berorientasi Object
O-DO LIST KULIAH (Python OOP)
Aplikasi berbasis Python untuk membantu mahasiswa mengelola daftar tugas kuliah dengan konsep Object Oriented Programming (OOP).
Aplikasi ini menyediakan fitur pengelolaan tugas, penandaan status, serta pengaturan prioritas tugas.

Fitur Aplikasi
Tambah Tugas Baru
Pengguna dapat menambahkan tugas baru dengan memasukkan nama mata kuliah, nama tugas, deadline, dan prioritas (tinggi, sedang, rendah).

Lihat Semua Tugas
Menampilkan seluruh daftar tugas yang sudah diinput beserta detailnya.

Tandai Tugas Selesai
Mengubah status tugas menjadi selesai berdasarkan ID tugas.

Hapus Tugas
Menghapus tugas dari daftar berdasarkan ID tugas.

Prioritas Tugas
Setiap tugas dapat diberi prioritas (1 = Tinggi, 2 = Sedang, 3 = Rendah) untuk membantu pengguna menentukan tugas mana yang harus didahulukan.

Struktur Folder & File
TUGAS OOP/
│
├── main.py                  # Program utama (menu interaktif)
├── tugas_manager.py         # Manajemen data tugas (CRUD)
├── Models/
│   ├── __init__.py          # Penanda package Models
│   ├── tugas.py             # Class dasar Tugas
│   └── tugas_prioritas.py   # Class turunan Tugas dengan prioritas
└── README.md                # Dokumentasi proyek

Penjelasan Kode
1. main.py
Berisi menu interaktif yang memungkinkan pengguna menambah, melihat, menandai selesai, dan menghapus tugas.
2. tugas_manager.py
Mengelola penyimpanan dan pengambilan data tugas, bisa dikembangkan untuk menggunakan database atau file.
3. tugas.py
Mendefinisikan class Tugas dengan atribut mata kuliah, nama tugas, deadline, dan status.
4. tugas_prioritas.py
Mendefinisikan class TugasPrioritas yang mewarisi Tugas dan menambahkan atribut prioritas serta method untuk menampilkan info tugas beserta prioritasnya.

Cara Menjalankan
Pastikan Python sudah terinstall di komputer Anda.
Pastikan struktur folder sudah sesuai.
Jalankan program dengan perintah berikut di terminal:
python main.py

Ikuti instruksi pada menu aplikasi.
Contoh Penggunaan
Pilih menu "Tambah Tugas" untuk memasukkan tugas baru.
Pilih menu "Lihat Semua Tugas" untuk melihat daftar tugas.
Pilih menu "Tandai Tugas Selesai" untuk mengubah status tugas menjadi selesai.
Pilih menu "Hapus Tugas" untuk menghapus tugas dari daftar.
Catatan
Jika terjadi error import, pastikan penulisan nama folder dan file pada bagian import sudah sesuai dengan struktur folder (huruf besar dan kecil harus sama persis).
Jika ingin mengembangkan aplikasi menggunakan database, sesuaikan konfigurasi pada file yang diperlukan.
