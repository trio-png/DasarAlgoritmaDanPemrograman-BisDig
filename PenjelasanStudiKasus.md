# STUDI KASUS 1 
# Jelaskan manfaat penggunaan fungsi dan bagaimana rekursi bekerja dalam menghitung faktorial!
# Manfaat Penggunaan Fungsi

Penggunaan fungsi dalam pemrograman memiliki beberapa manfaat penting, antara lain:

- **Memudahkan Pemeliharaan**  
  Fungsi memudahkan dalam pemeliharaan program jika terdapat kesalahan. Karena kode dibagi menjadi bagian-bagian kecil yang terpisah, kesalahan dapat ditemukan dan diperbaiki cepat.

- **Memecah Program Menjadi Bagian Kecil**  
  Fungsi memungkinkan pemecahan program menjadi bagian yang lebih kecil. Hal ini membuat program lebih terstruktur dan mudah dipahami.

- **Penggunaan Ulang Kode (Reusability)**  
  Fungsi dapat dipanggil berulang kali di berbagai bagian program tanpa perlu menulis ulang kode yang sama, sehingga menghindari duplikasi kode.

- **Menghindari Ketidakterbacaan dan Duplikasi Kode**  
  Dengan fungsi, kode menjadi lebih rapi dan terorganisir, sehingga meningkatkan keterbacaan dan mengurangi risiko duplikasi kode.

## Rekursi dalam Penghitungan Faktorial

Cara kerja rekursi pada faktorial adalah sebagai berikut:

1. Fungsi `faktorial` dipanggil dengan nilai `n`.
2. Fungsi memanggil dirinya sendiri dengan nilai yang lebih kecil, yaitu `n-1`.
3. Proses ini berlanjut hingga mencapai kasus dasar, biasanya `faktorial(0) = 1`.
4. Nilai hasil perkalian dikembalikan secara berantai hingga hasil akhir faktorial `n` diperoleh.


# STUDI KASUS 2
# Penjelasan Penggunaan Perulangan dan Array

- Array/List: Digunakan untuk menyimpan kumpulan nilai yang dimasukkan oleh pengguna. Dalam Python, struktur data yang umum digunakan adalah list, yang bisa menampung banyak nilai sekaligus.

- Perulangan: Digunakan untuk mengulangi proses input nilai sebanyak jumlah siswa yang diinginkan. Dengan perulangan, kita bisa meminta input nilai satu per satu dan menyimpannya ke dalam list.

- Setelah semua nilai dimasukkan, kita bisa menggunakan fungsi built-in seperti max() untuk mencari nilai tertinggi.

- Untuk mengetahui siswa ke berapa yang mendapat nilai tertinggi, kita bisa menggunakan metode list.index() untuk mendapatkan indeks dari nilai tertinggi tersebut.

## Cara Kerja Program
Program meminta jumlah siswa.
1. Program melakukan perulangan sebanyak jumlah siswa untuk memasukkan nilai masing-masing.
2. Nilai-nilai tersebut disimpan dalam list nilai_siswa.
3. Program mencari nilai tertinggi menggunakan max().
4. Program mencari posisi siswa yang mendapat nilai tertinggi menggunakan index().
5. Program menampilkan nilai tertinggi dan nomor siswa yang mendapatkannya.


# STUDI KASUS 3
# Program Pemberian Diskon dengan Struktur Kontrol Percabangan

## Deskripsi
Program ini memberikan diskon berdasarkan total belanja pelanggan. Jika total belanja lebih dari Rp500.000, pelanggan mendapatkan diskon 10%. Jika total belanja lebih dari Rp100.000 namun kurang dari atau sama dengan Rp500.000, tidak ada diskon.

## Cara Kerja
Program menggunakan struktur kontrol percabangan if-elif-else untuk menentukan besaran diskon berdasarkan kondisi total belanja.

## Penjelasan
- Jika total belanja lebih dari 500.000, diskon 10% diberikan.
- Jika total belanja lebih dari 100.000 tapi tidak lebih dari 500.000, tidak ada diskon. 
- Jika total belanja kurang dari atau sama dengan 100.000, tidak ada diskon.

Struktur percabangan ini memudahkan pengambilan keputusan secara otomatis berdasarkan kondisi yang diberikan. 




