Jelaskan manfaat penggunaan fungsi dan bagaimana rekursi bekerja dalam menghitung faktorial!

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




