# Tugas
1. Buatlah repository baru dengan nama Lab1Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus.

# Pertama buatlah sebuah file dan masukan code seperti dibawah ini  :
![Screenshot (10)](https://github.com/MIGHTY-LANTERN/praktikum-11/assets/115616713/c27133f0-3698-47de-9aa5-c608b7347202)  

`Lalu simpan file tersebut dengan shourcut CTRL+S,setelah disimpan buka dokumen dan klik kanan pada folder htmlnya,lalu klik open with dengan browser kesukaan kalian.seperti contoh Mozila,Crohome,dan Edge`

`Seperti gambar dibawah ini`

![Screenshot (9)](https://github.com/MIGHTY-LANTERN/praktikum-11/assets/115616713/44f4b980-277d-4666-b01f-6a150e1f8a2b)



# Selanjutnya Membuat Paragraf

`Selanjutnya buatlah paragraf sederhana sebagai berikut  :`

```html
<!-- Ini adalah kalimat paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
HTML.</p>
<!-- Ini adalah kalimat paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
tag dasar html.</p>
```
`Dan hasilnya akan seperti ini  :`

![screenshot(16) - Copy](https://github.com/MIGHTY-LANTERN/praktikum-11/assets/115616713/3b725aa4-df1b-4df8-8fca-d989454b741c)


`Selanjutnya atur atribut paragraf dan Menambahkan Judul seperti berikut  :`

```html
<!-- Ini adalah kalimat pada paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
tag-tag dasar HTML.</p>
<!-- Ini adalah kalimat pada paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa
kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
dengan menggunakan tag dasar html.</p>
```
`Dan untuk hasil menambahkan judul dan Atribut paragraf akan seperti ini  :`

![Screenshot (12)](https://github.com/MIGHTY-LANTERN/praktikum-11/assets/115616713/2d0e6616-bd7a-4104-a112-b1b29de38f78)

`Selanjutnya Menyisipkan gambar`

Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian
simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan
gambar dari website external.

`Selanjutnya tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3
sebelumnya.menggunakan code seperti dibawah ini  :`

```html
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="Logo_UPB.png" title="Logo Univeritas Pelita Bangsa">

`Dan hasilnya akan seperti ini  :`

![Screenshot (14)](https://github.com/MIGHTY-LANTERN/praktikum-11/assets/115616713/13c859e5-3d56-42ed-a80c-6c1c48ad800c)

`Selanjutnya Menambahkan Hyperlink, Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut`

```html
<!-- menambahkan link navigasi -->
<nav>
<a href="lab1_tag_dasar.html">Dasar HTML</a>
<a href="lab1_halaman2.html">Halaman 2</a>
<a href="http://www.google.com">Halaman Web Eksternal Google</a>
</nav>
<hr>
```

`Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag
html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya`

`Dan hasilnya akan seperti ini  :`

![Screenshot (16)](https://github.com/MIGHTY-LANTERN/praktikum-11/assets/115616713/0f2838e7-d913-40f6-8957-86879ce1527e)

# Jawab Pertanyaan Berikut

2.Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
   
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

# Jawab


2Perbedaan antara tag <p> dan tag <br> adalah sebagai berikut:

`Tag <p> (paragraph) digunakan untuk membuat paragraf teks, dan secara otomatis menambahkan jarak vertikal (baris baru) sebelum dan setelah paragraf. Ini adalah elemen blok dan biasanya digunakan untuk mengelompokkan teks.`

`Tag <br> (line break) digunakan untuk membuat jarak vertikal (baris baru) dalam teks, tetapi tidak membentuk paragraf baru. Ini adalah elemen inline dan digunakan untuk mengatur pemisahan dalam teks, seperti dalam alamat atau stihiran.`

3.Perbedaan antara atribut title dan alt pada tag <img> adalah sebagai berikut:

`Atribut alt: Atribut ini digunakan untuk memberikan teks alternatif untuk gambar. Ini penting untuk aksesibilitas web, karena akan menampilkan teks jika gambar tidak dapat dimuat atau jika pembaca layar digunakan. Teks alternatif ini juga membantu mesin pencari memahami isi gambar.`

`Atribut title: Atribut ini digunakan untuk memberikan judul atau informasi tambahan tentang gambar saat pengguna mengarahkan kursor mouse ke gambar tersebut (tooltip). Ini adalah informasi tambahan dan tidak ditampilkan jika gambar tidak dimuat. Ini dapat membantu dalam memberikan keterangan atau deskripsi singkat tentang gambar.`

4.`Untuk mengatur ukuran gambar agar tampilan gambar proporsional, sebaiknya kedua atribut width dan height diisi. Ini karena ketika hanya satu atribut diisi, gambar mungkin menjadi terdistorsi dan tidak proporsional. Jika Anda hanya mengisi salah satu atribut (misalnya, hanya width atau hanya height), browser akan secara otomatis menghitung nilai atribut yang lain agar gambar tetap proporsional. Tetapi, lebih baik mengisi keduanya dengan nilai yang sesuai agar hasilnya lebih dapat diprediksi dan sesuai dengan desain yang diinginkan.`

5.Atribut target digunakan untuk mengendalikan perilaku hyperlink. Berikut adalah penjelasan untuk nilai-nilai atribut target yang berbeda:

`_blank: Jika menggunakan _blank, tautan akan membuka halaman yang terhubung dalam tab atau jendela browser yang baru. Ini memungkinkan pengguna tetap berada di halaman asal.`

`_self: Ini adalah perilaku default. Jika menggunakan _self, tautan akan membuka halaman yang terhubung di jendela atau tab yang sama di mana tautan itu ada.`

`_top: Jika menggunakan _top, tautan akan membuka halaman yang terhubung di jendela atau tab utama (paling atas) dan menggantikan semua bingkai (frames) jika ada.`

`_parent: Jika menggunakan _parent, tautan akan membuka halaman yang terhubung di jendela atau tab yang menggantikan bingkai (frame) yang berisi tautan tersebut, jika ada bingkai yang digunakan dalam halaman.
Pilihan nilai atribut target ini memberikan kontrol atas cara halaman web yang terhubung dibuka dan memengaruhi pengalaman pengguna.`



