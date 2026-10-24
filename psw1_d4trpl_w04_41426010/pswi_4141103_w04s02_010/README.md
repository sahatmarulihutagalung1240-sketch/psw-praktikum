laporan praktikum PSW

nama :Sahat Hutagalung
NIM  :41426010
Prodi : DIV - TRPL (1)

Cara Menjalankan

1. Membuka folder project menggunakan Visual Studio Code.
2. terdapat file:
   - `index.html`
   - `style.css`
   - `main.js`
   - `README.md`
3. Membuka file `index.html`.
4. Menjalankan halaman menggunakan Live Server.
5. Membuka halaman melalui browser.
6. Menggunakan DevTools untuk memeriksa HTML dan CSS

Persiapan Stylesheet:Saya menghubungkan file CSS dengan file HTML menggunakan:
<link rel="stylesheet" href="css/style.css">

Selector dan class:
saya menambahkan pada style css saya form.card { padding: 1rem; background: white; }
.notice { color: #175cd3; } yang berfungsi untuk mengubah warna pada background di web, supaya bisa  warna pada backgrundnya terlihat di web saya menambahkan <form class="card"> pada index html saya tepat nya di bagian atas <h1>. Saya membuat percobaan dengan mengubah nama class, saya membuka web nya hasilnya warna pada background yang ada pada web saya tidak ada warna lagi atau warna yang saya buat bdi web saya tidak ada lagi. Bukti bisa dilihat dari browser web nya. 

KONFLIK SPECIFICITY:
Pada percobaan ini, saya menggunakan dua aturan CSS yang diterapkan pada elemen yang sama, yaitu .card p dan .notice. Saya mecoba menukar urutan kedua aturan CSS tersebut untuk melihat apakah hasilnya berubah.Setelah dicoba, ternyata warnanya tetap ungu walaupun urutan CSS sudah ditukar.

UKURAN KOTAK:
Pada percobaan ini saya memasukkan .card { width: 240px; padding: 16px;
 border: 2px solid #445; margin: 12px; } pada style css saya, saya membuka web saya posisi pada web saya berada di pinggir, saya membuat menghitung percobaan  lebar tanpa margin: 240+32+4, saya memasukkan 240 + 32 + 4 pada width, padding dan border. ketika saya memasukkanya hasilnya menjadi posisi dari card pada web saya berada di tengah, itu yang menjadi perubahan ketika saya mengubah nya.

Latihan Mandiri : 
menambahkan satu data panjang, kosong, atau invalid yang relevan dengan materi.Jadi saya disini membuat suatu program yang dimana saya membuat dengan judul " Alasan mendaftar kegiatan " yang isinya saya meminta pertanya kenapa mau mendaftar kegiatan pada melakukan latihan mandiri.

Input/Kondisi	   
Kasus Normal          
Tindakan	  : Menjalankan index.html melalui Live Server               
Hasil Aktual : Halaman dapat dibuka dan CSS diterapkan                                           
Status/Bukti : Screenshot hasil pengujian disimpan pada folder bukti
	  
Kasus Batas          
Tindakan	  :  menguji input yang memiliki panjang berbeda pada form, terutama
pada bagian nama, email, telepon, dan catatan.
Hasil Aktual : Input tetap dapat dimasukkan ke dalam form dan ukuran elemen mengikuti
aturan CSS yang telah diberikan.
Status/Bukti : Screenshot hasil pengujian disimpan pada folder bukti

Kasus Gagal 
Tindakan : Mengganti secara sengaja nama dari class awalnya card menjadi bous(tidak memiliki arti/fungsi)
Hasil Aktual : Card pada web awalnya ada di pinggir, karena di gandi berubah menjadi ke tengah 
status/bukti : Screenshot hasil pengujian disimpan pada folder bukti

Validator:
1. error pertama saya menambahkan string pada <br> yang embuat kode saya menjadi error, jadi saya memperbaikinya kembali dengan menghapus string pada <br>
2. error kedua saya membuat Penulisan <input> sebelumnya belum benar/kurang >, jadi saya memperbaikinya dengan Periksa tag sebelum baris 62
3. error ketiga pada requaired saya salah membuat atau memasukkan string juga pada requared, sehingga saya memperbaiki nya dan kembali normal 
4. Pada error ke empat saya salah membuat tag saya membuat tiga tetapi yang di butuhkan dua  pada, saya memperbaiki nya dan hasil nya menjadi normal kembali. 
AI STATEMENT :
saya menggunakan ai untuk memeriksa error di program saya dan mencari titik kesalahannya setelah itu saya memperbaikinya.

