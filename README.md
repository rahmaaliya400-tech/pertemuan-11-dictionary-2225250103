# Pertemuan 11 - Dictionary/Map
Nama: Rahma Aliya
NIM: 2225250103
Kelas: 3F
## Tujuan
Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value.
## Struktur Data
Program menggunakan dictionary dengan NIM sebagai key utama. Setiap NIM menyimpan dictionary bersarang yang berisi nama mahasiswa, kelas, dan nilai.
Contohnya, NIM A001 menyimpan data mahasiswa bernama Ayu, kelas A, dengan nilai 85.
## Cara Menjalankan
Jalankan latihan melalui terminal VS Code dengan perintah berikut:

python latihan/01_dasar_dictionary.py
python latihan/02_akses_get.py
python latihan/03_manipulasi_dictionary.py
python latihan/04_iterasi_dictionary.py
python latihan/05_dictionary_bersarang.py
python latihan/06_fungsi_dictionary.py

Untuk menjalankan program praktik:
python praktik/data_mahasiswa.py
## Test Case ##
1.Mencari NIM A003 menampilkan data mahasiswa Citra.
2.Mencari NIM A999 menampilkan pesan bahwa data tidak ditemukan.
3.Menambahkan mahasiswa baru dengan NIM A006.
4.Mengubah nilai mahasiswa dengan NIM A002 menjadi 82.
5.Menampilkan seluruh data mahasiswa dan menghitung rata-rata nilai.

Hasil pengujian menunjukkan bahwa program dapat mencari, menambahkan, mengubah, dan menampilkan data mahasiswa menggunakan dictionary.
## Refleksi
Kesalahan akses key dapat terjadi ketika key yang dicari tidak tersedia dalam dictionary. Kesalahan tersebut dapat dihindari dengan menggunakan metode get() atau memeriksa keberadaan data sebelum mengaksesnya. Dengan demikian, program dapat menangani data yang tidak ditemukan dengan lebih aman.