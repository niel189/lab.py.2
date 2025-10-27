NAMA:DANIEL MOHAMMED
NIM:(312510466)
Pembahasan Kondisi If

Pada praktikum ini, mahasiswa mempelajari cara menggunakan struktur kondisi if dalam bahasa pemrograman Python. Struktur kondisi if digunakan untuk membuat program yang mampu mengambil keputusan berdasarkan suatu kondisi tertentu. Dengan menggunakan if, program dapat menjalankan perintah tertentu jika kondisi tersebut bernilai benar (True), dan mengabaikannya jika bernilai salah (False).

Dalam Python, terdapat beberapa bentuk pernyataan kondisi yaitu if, if...else, if...elif...else, dan nested if (if di dalam if). Setiap bentuk memiliki fungsi berbeda sesuai dengan kebutuhan logika program. Bentuk dasar if hanya memeriksa satu kondisi, sedangkan if...else menambahkan pilihan alternatif apabila kondisi pertama tidak terpenuhi. Struktur if...elif...else digunakan ketika terdapat lebih dari dua kemungkinan keputusan, sedangkan nested if berguna untuk melakukan pemeriksaan berlapis di dalam kondisi utama.

Pada latihan pertama (latihan1.py), program dibuat untuk menentukan apakah angka yang dimasukkan oleh pengguna merupakan bilangan positif, negatif, atau nol. Program meminta input berupa angka, kemudian menggunakan pernyataan if, elif, dan else untuk memeriksa kondisinya. Jika angka lebih besar dari nol maka program akan menampilkan “bilangan positif”, jika lebih kecil dari nol maka “bilangan negatif”, dan jika sama dengan nol maka akan menampilkan “nol”. Melalui latihan ini, mahasiswa memahami cara kerja percabangan sederhana dalam Python.

Sedangkan pada latihan kedua (latihan2.py), program digunakan untuk menentukan nilai huruf atau grade berdasarkan nilai akhir yang dimasukkan pengguna. Program ini menggunakan konsep nested if, di mana terdapat if di dalam if. Pertama, program akan memeriksa apakah nilai yang dimasukkan berada dalam rentang 0 sampai 100. Jika valid, maka dilakukan pemeriksaan lebih lanjut untuk menentukan grade: A untuk nilai 90–100, B untuk 80–89, C untuk 70–79, D untuk 60–69, dan E untuk nilai di bawah 60. Program juga menampilkan pesan kesalahan apabila nilai yang dimasukkan tidak sesuai dengan batas yang ditentukan.

Melalui praktikum ini dapat disimpulkan bahwa penggunaan struktur kondisi if sangat penting dalam pemrograman karena memungkinkan program mengambil keputusan secara otomatis sesuai kondisi tertentu. Konsep ini menjadi dasar logika dalam berbagai aplikasi yang membutuhkan proses penentuan hasil berdasarkan input atau situasi yang berbeda.


Pembahasan Perulangan

Pada bagian praktikum ini, mahasiswa mempelajari konsep perulangan (looping) dalam bahasa pemrograman Python. Perulangan digunakan untuk menjalankan suatu perintah secara berulang tanpa perlu menulis perintah yang sama berkali-kali. Konsep ini sangat penting dalam pemrograman karena membuat kode menjadi lebih efisien, ringkas, dan mudah dibaca, terutama saat kita ingin melakukan operasi yang sama pada banyak data atau dalam rentang angka tertentu.

Dalam Python terdapat dua jenis perulangan utama, yaitu for dan while. Perulangan for digunakan ketika jumlah pengulangan sudah diketahui atau ditentukan sejak awal, misalnya untuk mencetak angka dari 1 sampai 10. Sementara itu, perulangan while digunakan ketika jumlah pengulangan belum pasti dan bergantung pada suatu kondisi tertentu; perulangan akan berhenti jika kondisi tersebut bernilai salah (False).

Pada latihan pertama (latihan1.py), program menggunakan perulangan for untuk menampilkan bilangan dari 1 hingga N. Pengguna diminta untuk memasukkan batas angka terakhir (N), kemudian program menggunakan fungsi range(1, n+1) untuk menghasilkan urutan angka dari 1 sampai N. Setiap iterasi menampilkan nilai i satu per satu ke layar. Dari latihan ini, mahasiswa dapat memahami bagaimana struktur dasar for bekerja dan bagaimana fungsi range() digunakan untuk menentukan banyaknya pengulangan.

Selanjutnya, pada latihan kedua (latihan2.py) digunakan perulangan while untuk menghitung jumlah dari bilangan 1 sampai N. Program meminta pengguna memasukkan batas akhir (N), lalu menggunakan variabel penghitung i dan variabel penampung hasil total. Selama nilai i masih lebih kecil atau sama dengan N, program akan menambahkan i ke dalam total dan menaikkan nilai i satu per satu. Setelah perulangan selesai, hasil penjumlahan seluruh bilangan ditampilkan. Latihan ini memperlihatkan bagaimana while bekerja berdasarkan kondisi logis, bukan jumlah pengulangan yang tetap.

Dari kedua latihan tersebut, dapat disimpulkan bahwa perulangan merupakan salah satu konsep penting dalam pemrograman karena memungkinkan proses otomatisasi dan efisiensi dalam penulisan kode. Perulangan for cocok digunakan ketika jumlah iterasi sudah pasti, sedangkan while digunakan untuk kondisi yang bergantung pada logika tertentu. Pemahaman terhadap kedua jenis perulangan ini sangat berguna sebagai dasar dalam pembuatan program yang lebih kompleks, seperti pengolahan data, pencarian, dan perhitungan matematis.
