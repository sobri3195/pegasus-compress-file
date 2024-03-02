# pegasus-compress-file
mengkompresi direktori atau file individu menjadi format ZIP

# Deskripsi
Repository ini berisi skrip Python yang dapat digunakan untuk mengkompresi direktori atau file individu menjadi format ZIP. Fungsionalitas utama skrip ini mencakup:
Kompresi file individu.
Kompresi seluruh direktori, termasuk subdirektori dan file di dalamnya.
Pencarian rekursif semua jalur file dalam direktori yang diberikan.
Dengan menggunakan skrip ini, Anda dapat dengan mudah mengarsipkan file dan direktori untuk penyimpanan atau distribusi yang lebih efisien.

# Fitur
Kompresi File: Kompresi file tunggal menjadi format ZIP.
Kompresi Direktori: Kompresi direktori lengkap, termasuk semua subdirektori dan file, menjadi satu file ZIP.
Pencarian File: Mengidentifikasi semua file dalam direktori yang diberikan, siap untuk dikompresi.

# Persyaratan
Untuk menjalankan skrip ini, Anda memerlukan Python versi 3.x. Skrip ini menggunakan modul zipfile, sys, dan os yang sudah termasuk dalam instalasi Python standar, sehingga tidak diperlukan instalasi paket tambahan.

# Penggunaan
Skrip ini dapat dijalankan dari command line atau terminal. Berikut adalah cara menggunakan skrip:

# Kompresi File Tunggal:
sh
Copy code
python nama_skrip.py path_ke_file
Gantikan nama_skrip.py dengan nama file skrip ini dan path_ke_file dengan path lengkap ke file yang ingin Anda kompresi.

# Kompresi Direktori:
sh
Copy code
python nama_skrip.py path_ke_direktori
Gantikan nama_skrip.py dengan nama file skrip ini dan path_ke_direktori dengan path lengkap ke direktori yang ingin Anda kompresi.

# Contoh
Untuk mengkompresi file bernama contoh.txt yang berada di direktori saat ini:
sh
Copy code
python nama_skrip.py contoh.txt

# Untuk mengkompresi direktori folder_contoh:
sh
Copy code
python nama_skrip.py folder_contoh

# Catatan
Pastikan Anda memiliki hak akses yang sesuai untuk membaca file atau direktori yang ingin dikompresi.
Hasil kompresi akan disimpan di lokasi yang sama dengan file atau direktori sumber, dengan ekstensi .zip.

# Kontribusi
Kontribusi ke proyek ini sangat dianjurkan! Jika Anda memiliki saran, perbaikan bug, atau peningkatan, silakan fork repository ini, buat perubahan, dan kirimkan pull request. Kami sangat menghargai setiap kontribusi.
Muhammad Sobri Maulana

# Lisensi
Skrip ini disediakan "sebagaimana adanya", tanpa jaminan apa pun. Anda bebas menggunakan, memodifikasi, dan mendistribusikannya untuk keperluan pribadi maupun komersial.
