# Praktikum5
Tugas Praktikum
Buat program sederhana yang akan menampilkan daftar nilai
mahasiswa, dengan ketentuan

- Program dibuat dengan menggunakan Dictionary
- Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md.
- Commit dan push repository ke github.

#### PENJELASAN~~~~~
Mulai
1. Pertama anda menginputkan data={ }, diisi dengan sesuai kenginan anda, dengan format dictionary
2. Gunakanlah perulangan While True untuk menampilkan data sebanyak banyaknya
3. lalu Masukan perintah g = input("(T)ambah, (U)bah, (H)apus, (L)ihat,(C)ari, (K)eluar: "),untuk mendapatkan perintah Tambah, Ubah, Hapus,Lihat,Cari,Keluar.
4. Untuk menambahkan data gunakan fungsi elif, lalu masukan nama, nim, tugas, uts, uas, nilaiakhir, nilai akhir didapat dari = ((tugas)*30/100+(uts)*35/100+(uas)*35/100)
5. Lalu jika ingin memilih  "lihat" gunakan fungsi 'elif' dan gunakan fungsi 'for x in data.items():' untuk memasukan data kedalam tabel data yang kita inputkan, dengan perintah "l". jika data yang tidak terdaftar = 0
6. Untuk menampilkan pilihan "hapus"gunakan fungsi 'elif' kemudian gunakan fungsi 'if nama in data.keys():' kemudian fungsi'del.data[nama] jika nama yang kita hapus tidak ada dalam tabel maka gunakan fungsi 'else' untuk menampilkan data tidak ada.
7. lalu untuk menampilan pilihan "cari"" gunakan fungsi 'elif' kemudian gunakan fungsi if nama in data.keys():' untuk mencari data nama kemudian gunakan fungsi 'else' untuk menampilkan data nama yang kita cari tidak ada.
8. lalu jika ingin keluar dari program  gunakan fungsi 'if' kemudian gunakan fungsi break untuk keluar dari data nilai/menghentikan program
9. Seleseai

#### PROGRAM~~~~~
![Gambar 1](gambar/ss1.png)
![Gambar 2](gambar/ss2.png)
![Gambar 3](gambar/ss3.png)

#### HASIL PROGRAMNYA~~~
![Gambar 4](gambar/ss4.png)
![Gambar 5](gambar/ss5.png)
![Gambar 6](gambar/ss6.png)

####  FLOWCHART~~~
![Gambar 7](flowchart/flowchart%205.jpg)