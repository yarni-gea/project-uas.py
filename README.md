# project-uas.py

# Struktur Program
1. Class Book

 
Menyimpan informasi dasar tentang buku:

Atribut:

title: Judul buku

author: Pengarang buku

year: Tahun terbit

Metode:

            __init__(self, title, author, year): Konstruktor untuk inisialisasi atribut.

# 2. Class View

Mengelola input/output dari pengguna:

Metode:

       display_menu(): Menampilkan menu utama.

      get_book_input(): Meminta input data buku dengan validasi.

     display_books(books): Menampilkan data buku dalam format tabel.

 # 3. Class BookManager
 
Mengelola daftar buku:


Atribut:

       books: Daftar buku yang disimpan.

Metode:

       add_book(title, author, year): Menambahkan buku ke daftar.

       get_all_books(): Mengembalikan semua data buku yang disimpan.

# 4. Class Main

Mengelola alur utama program:

Atribut:

      manager: Objek dari class BookManager.

     view: Objek dari class View.

Metode:

     run(): Menjalankan program dalam loop hingga pengguna keluar.



