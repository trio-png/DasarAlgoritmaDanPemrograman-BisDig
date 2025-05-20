# Menghitung Faktorial Dengan Metode Rekursif 
# Jelaskan manfaat penggunaan fungsi dan bagaimana rekursi bekerja dalam menghitung faktorial!

## Manfaat Penggunaan Fungsi
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
jika dalam basis kasus untuk melakukan pemanggilan ulang 
   if n == 0 or n == 1:
       return 1     
maka hasil yang dihasilkan satu, jika dalam kasus mencari faktorial 5 
    return n * faktorial(n - 1)
    
jika kita ingin menghitung faktorial dari 5, prosesnya akan berjalan sebagai berikut:
  faktorial(5) memanggil 5 * faktorial(4)
  faktorial(4) memanggil 4 * faktorial(3)
  faktorial(3) memanggil 3 * faktorial(2)
  faktorial(2) memanggil 2 * faktorial(1)
  faktorial(1) mencapai basis kasus dan mengembalikan 1
ini sesuai denga rumus yang diatas.

hasilnya akan dikembalikan ke atas dalam tumpukan pemanggilan:
  faktorial(2) mengembalikan 2 * 1 = 2
  faktorial(3) mengembalikan 3 * 2 = 6
  faktorial(4) mengembalikan 4 * 6 = 24
  faktorial(5) mengembalikan 5 * 24 = 120
maka akhirnya, hasil faktorial dari 5 adalah 120.





# Sistem Input Nilai Dengan Menggunakan Perulangan Dan Array.
## Penjelasan Penggunaan Perulangan dan Array dan cara bekerjanya

## Perulangan 
dalam kasus ini perulangan digunakan dalam proses fungsi input nilai, perulangan digunakan untuk meminta input nilai dari sejumlah siswa yang ditentukan oleh pengguna.
      for i in range(jumlah_siswa):
       nilai_siswa = float(input(f"Masukkan nilai siswa ke-{i + 1}: "))
       nilai.append(nilai_siswa)
disini, range(jumlah_siswa) menghasilkan urutan angka dari 0 hingga jumlah_siswa - 1, dan setiap iterasi meminta nilai siswa ke-i. 
   
## array atau list
adalah metode untuk membuat kumpulan data atau list tadi, dalam kasus ini array atau list digunakan dalam konteks nilai yang harus dikumpulkan. 
  list nilai disimbolkan list kosong (nilai = []). Setiap kali pengguna memasukkan nilai siswa, nilai tersebut ditambahkan ke dalam list menggunakan metode append()
  sedangkan untuk mencari nilai tertinggi menerima list nilai sebagai argumen. menggunakan fungsi max() untuk menemukan nilai tertinggi dalam list.
   tertinggi = max(nilai)
   indeks = nilai.index(tertinggi) + 1
   
dengan begitu dapat dengan mudah mengelola dan memanipulasi sekumpulan nilai siswa. List memungkinkan kita untuk menyimpan data dalam format yang diperlukan. 





# Sistem Menghitung Diskon Dengan Metode Kontrol Percabangan.
## bagaimana struktur kontrol percabangan digunakan untuk logika pemberian diskon

## Percabangan 
biasa digunakan dalam program untuk mengambil keputusan berdasarkan kondisi tertentu dalam kasus yang dibuat untuk menentukan apakah total pembayaran memenuhi syarat untuk mendapatkan diskon atau tidaknya. 

## fungsi hitung bayar 
    total = harga * jumlah
   dengan mengalikan harga dengan jumlah barang yang dibeli 
## memasukan "if"
    if total >= 500000:
    diskon = total * 0.10
    total_bayar = total - diskon
     
  jika kondisi sesuai maka akan mendapatkan diskon 10%
  jika kondisi tidak sesuai maka 
    else:
    total_bayar = total
    
## Mengembalikan Nilai:
Setelah menentukan nilai total_bayar, fungsi mengembalikannya ke pemanggil:
     return total_bayar
     
  Dengan menggunakan struktur kontrol percabangan if, program dapat mengambil keputusan berdasarkan nilai total pembayaran. Jika total memenuhi syarat untuk mendapatkan diskon, maka diskon akan diterapkan; jika tidak, total pembayaran tetap sama. 




# Sistem Kasir Pada Toko
# Jelaskan langkah-langkah algoritma untuk menyelesaikan masalah tersebut

pada prrogram yang digunakan menggunakan fungsi-fungsi dasar dalam Python
# meminta input dari pengguna 
  harga_barang1 = float(input("Masukkan harga barang 1: "))
    fungsi input() digunakan untuk mengambil input dari pengguna dalam bentuk string.
    Kemudian, fungsi float() digunakan untuk mengubah input tersebut menjadi tipe data angka desimal (float), sehingga program dapat melakukan perhitungan matematis.
# menhitung total pembayaran 
total_pembayaran = harga_barang1 + harga_barang2 + harga_barang3
mengakumulasi dari harga barang 1 2 dan 3 
# menunjukan hasil 
print(f"Total pembayaran adalah: {total_pembayaran}")
  dengan fungsi print yang menunjukan total pembayaran 
  
  dengan begitu penggunaan fungsi input untuk mendapatkan data dari pengguna, menggunakan tipe data yang tepat (float) untuk melakukan perhitungan, menggunakan operasi matematis dasar (penjumlahan) untuk menghitung total.





# Sistem Membuat Rata Rata Untuk Nilai Kelulusan 
# Jelaskan peran tipe data dan operator dalam menyelesaikan perhitungan tersebut. 

# Tipe Data integer (int)
   digunakan untuk menyimpan data bulat. dalam kasus ini, jumlah_nilai diinput sebagai integer untuk menentukan berapa banyak nilai yang akan dimasukkan oleh pengguna.
       jumlah_nilai = int(input("Masukkan jumlah nilai: "))
# Float (float)
Tipe data ini digunakan untuk menyimpan nilai desimal. dalam kasus ini nilai_list digunakan untuk menyimpan semua nilai yang dimasukkan oleh pengguna.
    nilai_list = []
    
# Operator
Operator Penjumlahan (+) yang digunkana untuk menlahjumlahkan. dalam kasus ini menjumlahkan  untuk menjumlahkan semua nilai dalam nilai_list 
    rata_rata = sum(nilai_list) / jumlah_nilai
    
# Operator Perbandingan (>=):
Operator ini digunakan dalam percabangan if untuk membandingkan rata-rata dengan nilai kelulusan minimum (75) iika rata-rata lebih besar atau sama dengan 75, maka status kelulusan ditetapkan sebagai "LULUS" begitupun sebaliknya 
