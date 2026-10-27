Nama  : Sahat Maruli Hutagalung
Nim   : 41426010
Prodi : D-IV TRPL (1)

1. Menyiapkan Halaman

Saya sudah menyiapkan tiga halaman website, yaitu index.html sebagai halaman utama, Kegiatan.html sebagai halaman yang menampilkan jadwal kegiatan, dan pendaftaran.html sebagai halaman formulir pendaftaran.

2. Navigasi Konsisten

Saya sudah menambahkan navigasi untuk menghubungkan halaman Beranda, Kegiatan, dan Pendaftaran Navigasi ini bertujuan untuk memindahkan halaman yang satu ke halaman lainnya pada web. Saya perlu memastikan setiap tautan mengarah ke halaman yang benar dan menandai halaman yang sedang dibuka menggunakan aria-current="page".

3. Path dan Aset

Saya sudah menggunakan file CSS, JavaScript, dan gambar untuk melengkapi website. File style.css digunakan untuk mengatur tampilan, sedangkan main.js digunakan untuk menjalankan fungsi JavaScript.Saya juga menambahkan beberapa gambar pada halaman utama dan halaman lainnya

4.  Audit Keseluruhan

Saya akan membuka setiap halaman untuk memastikan struktur HTML, navigasi, gambar, tabel kegiatan, dan formulir pendaftaran berfungsi dengan baik. Saya juga akan menguji website menggunakan keyboard, memperbesar tampilan browser, serta memeriksa tampilan pada ukuran layar 320 px dan 1200 px.

5.  Latihan Mandiri dan Matriks Uji

Input/kondisi	Tindakan	Hasil aktual	Status/bukti
Kasus normal: Tautan Terbuka	
Tindakan : Membuka halaman dan mengeklik tautan Beranda, Kegiatan, dan Pendaftaran.	
Hasil aktual :Halaman dapat dibuka dan tautan navigasi mengarah ke halaman yang dituju.	
Status/bukti: bukti berupa screenshot.

Kasus batas: halaman dibuka pada ukuran layar 320 px.	
Tindakan :Membuka website pada layar berukuran 320 px 	
Hasil aktual :web masih bisa tetap terbaca dan tidak terpotong.	
Status/bukti: bukti berupa screenshot.

Kasus gagal: formulir dikirim ketika bagian wajib masih kosong.	
Tindakan : Mengosongkan salah satu kolom wajib, lalu menekan tombol Daftar.
Hasil aktual : form pendaftaran tidak dapat di daftar karena ada kolom kosong
Status/bukti: bukti berupa screenshot.

Validator :
error index :saya tidak membuat <li> pada navigasi beranda sehingga mengalami error, jadi saya menambahkan <li> di depannya sehingga tidak mengalami error

error kegiatan : Saya meletakkan tag </head> tidak sesuai posisi. Saya memindahkan </head> sebelum <body>.
                 Saya  menemukan tag <body> yang dibuka lebih dari satu kali, sehingga saya menggunakan satu tag.
                 saya meletakkan tag <figure> di dalam <table> secara tidak tepat, jadi saya memperbaiki nya.

error pendaftaran : Saya menemukan kesalahan pada width pada tag <img> karena saya menulis 300ss, sehingga saya      memperbaikinya menjadi 300
                    saya tidak membuat <li> pada navigasi beranda sehingga mengalami error, jadi saya menambahkan <li> di depannya sehingga tidak mengalami error