# FORWARD CHAINING AND BACKWARD CHAINING 

Nama	: Anisa Rosalina

NPM	: 1184016

Kelas	: D4 Teknik Informatika

Mata Kuliah	: Sistem Pakar

Dosen Pengampu	:  M. Nurkamal Fauzan, S.T., M.T.


Ada 2 tugas: Forward Chaining dan Backward Chaining,. Rincian masing-masing adalah sebagai berikut: 

1) Forward Chaining: Di sini kita diberikan basis pengetahuan yang mencakup aturan dan fakta. Ide dasar dibalik rangkaian maju adalah itu
dari fakta kita mempelajari aturan dan melihat mana di antara mereka yang bisa dipecat. Aturan yang dipecat, konsekuensinya ditambahkan ke daftar fakta. Kemudian daftar fakta kolektif kemudian digunakan untuk memberlakukan aturan lebih lanjut.

2) Rantai Mundur: Dalam hal ini kita memiliki kesimpulan dan kita harus membuktikan bahwa itu dapat diturunkan dengan mundur, yaitu dari aturan ke fakta. Jadi, pada setiap iterasi, kami memperoleh daftar tujuan (yang merupakan daftar tempat) dan menggunakan tempat ini kami mencoba untuk mencapai fakta. Kalau bisa, berarti kesimpulannya bisa diturunkan dari fakta-fakta itu. Jika tidak, maka kesimpulan tidak dapat dibuktikan dari fakta-fakta yang ada.


(A v B) (-B v C) akan menghasilkan (A v C).
Saat mengikuti aturan ini, ada dua hal yang perlu diperhatikan. Pertama adalah kita harus menghapus duplikat literal yang mungkin muncul saat kita menyelesaikan file
ayat. Kedua, dan yang paling penting, jika klausa memiliki literal sehingga ada tipe positif dan negatif dari literal tersebut (Misalnya, katakanlah A v B v C v -A), maka kami tidak menyertakan klausa ini. Ini karena, nilainya akan dihitung menjadi 1.

Kompilasi dan Instruksi Menjalankan
1) Kompilasi program: javac pl.java
2) Jalankan program: java pl -t 1 -kb kb2.txt -q q2.txt -oe output.txt -ol logs.txt

Waktu yang dibutuhkan untuk menjalankan resolusi untuk kasus I: 35-40 detik pada mesin aludra
Waktu yang dibutuhkan untuk menjalankan resolusi untuk kasus II: 2:30 hingga 3 menit pada mesin aludra.

# Persamaan / Perbedaan antara Tugas 1 dan 2

Dari log program, terbukti bahwa forward chaining adalah yang terbaik karena membutuhkan waktu yang lebih singkat dibandingkan dengan pendekatan lainnya. Dalam siklus rantai mundur terdeteksi yang menyebabkan penundaan dalam output. Perangkaian maju dan mundur hanya berfungsi untuk klausa klausa. Tetapi resolusi dapat berfungsi untuk semua jenis klausa tetapi masalah utamanya adalah bahwa resolusi membutuhkan banyak waktu dibandingkan dengan apporach lainnya. Log resolusi jauh lebih besar dibandingkan dengan teknik perangkaian maju dan mundur. Subuset klausa menjadi lebih besar karena lebih banyak jumlah klausa yang diselesaikan.


# Pengertian Forward Chaining and Backward Chaining

Forward chaining adalah strategi implementasi yang populer untuk sistem pakar, sistem aturan bisnis dan produksi. Forward chaining dimulai dengan data driven. Artinya pada forward Chaining semua data dan aturan akan ditelusuri untuk mencapai tujuan yang diinginkan. sedangkan Backward chaining merupakan metode inferensi yang dilakukan untuk bidang kecerdasan buatan yang dimulai dengan pendekatan tujuan atau goal oriented atau hipotesa.

perbedaan dari Forward Chaining dan Backward Chaining terletak dari caranya dalam menyelesaikan permasalahan. Yaitu Forward Chaining merupakan metode pencarian yang memulai prosesnya dari sekumpulan data atau fakta dan dari fakta-fakta tersebut didapatkan kesimpulan yang dijadikan solusi dari permasalahan sedangkan Backward Chaining merupakan metode pencarian yang dimulai dari tujuan yaitu kesimpulan yang menjadi solusi dari permasalahan yang dihadapi.
