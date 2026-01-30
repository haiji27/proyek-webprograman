# proyek-webprograman

'<!DOCTYPE html>'
'<html lang="id"> baris ini digunakan untuk mendefinisikan dokumen sebagai HTML5. Dimana Atribut lang="id" menandakan bahwa bahasa yang digunakan pada halaman adalah Bahasa Indonesia.
Selanjutnya, <head> ini berfungsi untuk menyimpan informasi tentang halaman web, bukan untuk ditampilkan langsung di layar. <meta charset="UTF-8"> berfungsi agar karakter (huruf, simbol) dapat ditampilkan dengan benar. <title>Profil Diri</title> ini berfungsi menentukan judul halaman yang muncul pada tab browser. </head> ini berfungsi sebagai penutup tag <head> yang menandakan akhir dari bagian pengaturan halaman web sebelum masuk ke bagian konten utama (<body>). Serta <style> ini digunakan untuk menambahkan CSS jika ingin mempercantik tampilan website.

Judul dan Navigasi Halaman
<h1>Profil Diri</h1> Digunakan untuk menampilkan judul utama dan deskripsi singkat halaman, jadi h1 sebagai judul utama halaman. <p> Halaman profil pribadi menggunakan HTML </p>, jadi <p> sebagai paragraf penjelasan singkat, sedangkan </p> berfungsi untuk menutup paragraf teks yang dibuat dengan tag <p> sehingga struktur teks pada halaman web menjadi rapi dan mudah dibaca.
Lalu code a href="#tentang">Tentang Saya</a | Bagian ini merupakan menu navigasi yang menghubungkan ke bagian tertentu pada halaman menggunakan anchor link (id). Dimana <a href="#...."> ini merupakan link ke bagian dengan id="...". lalu tanda | sebagai pemisah visual. Code ini disebut navigasi internal halaman
hr ini berfungsi sebagai pemisah antar bagian

Bagian Tentang Saya
Code <h2 id="tentang">Tentang Saya</h2> ini sebagai judul bagian dan target navigasi, id="tentang" digunakan agar menu navigasi dapat menuju bagian ini. <img src="hajibday.jpeg" alt="Foto Profil" width="250">, <img> digunakan untuk menampilkan foto profil dari file lokal. Lalu src untuk nama file gambar, alt untuk teks alternatif, dan width untuk ukuran gambar
Halo, nama saya <b>Tri Haiji Januarli</b> panggil aja Haiji. Saya adalah mahasiswa <i>Informatika</i> universitas Bengkulu, mahasiswa semester 4 yang sedang mempelajari materi pengembangan web. Dimana <b> ini berfungsi agar teks menjadi bold, lalu <i> untuk membuat teks menjadi teks miring, serta <br> agar dapat berpindah baris

Riwayat Pendidikan
<table border="1"> dimana <table> ini untuk membuat tabel dan border="1" untuk membuat garis tabel
Code diatas digunakan untuk menampilkan data pendidikan dalam bentuk tabel yang terdiri dari:
Tahun - Institusi - Jurusan
<tr> untuk membuat baris tabel
    <th>Tahun</th> untuk membuat header tabel (tebal & rata tengah)
    <th>institusi</th>
    <th>Jurusan</th>
</tr>
<tr>
    <td>2024-Sekarang</td>
    <td>Universitas Bengkulu</td>
    <td>Informatika</td>
</tr>
dan <td> digunakan untuk membuat isi tabel

Keahlian dan Hobi
<ul> digunakan untuk daftar tidak berurutan (keahlian).
    <li>HTML</li>  berfungsi sebagai item list
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
<ol> sebagai ordered list
    <li>Travelling</li>
    <li>Bersepada</li>
    <li>Berenang</li>
</ol> digunakan untuk daftar berurutan (hobi).

Form Kontak
  <h2 id="kontak">Kontak Saya</h2>
    <form>
        <label>Nama:</label>
        <br>
        <input type="text" placeholder="Masukkan nama"><br>
    <br>
        <label>Email:</label>
        <br>
        <input type="email" placeholder="Masukkan email"><br>
    <br>
        <label form="">Password</label>
    <br>
        <input type="password"><br>
    <br>
        <label>Pesan:</label><br>
        <textarea rows="4" cols="30"></textarea><br>
    <br>
        <button type="submit">submit</button>
    </form>
     <form>  ini berfungsi sebagai formulir input data
    <input type="text"> ini untuk menginput teks
    <input type="email"> ini untuk menginput email (ada validasi)
    <input type="password"> ini untuk menginput password
   <textarea rows="4" cols="30"></textarea> ini berfungsi untuk menginput teks panjang (pesan)
   placeholder="Masukkan nama"> digunakan untuk menampilkan teks petunjuk sementara di dalam kolom input. Dimana tulisan “Masukkan nama” akan hilang otomatis saat pengguna mulai mengetik, ini berguna sebagai  petunjuk agar user tahu apa yang harus diisi
   <br> berfungsi untuk membuat baris baru setelah kolom input, supaya elemen berikutnya tampil di bawahnya
   <button type="submit">submit</button> ini berfungsi agar ada tombol submit di form
</form> ini berfungsi untuk menutup form dan menandakan akhir dari elemen-elemen input yang digunakan untuk mengisi data oleh pengguna
Form digunakan untuk menginput data seperti:
Nama
Email
Password
Pesan
Form ini bersifat statis dan digunakan sebagai tampilan antarmuka (belum terhubung ke backend).

Video Profil
<video width="320" height="240" controls>
    <source src="haijivdo.mp4" type="video/mp4">
</video>
code ini berfungsi untuk menampilkan video di halaman web. Dimana <video> digunakan untuk menampilkan video profil yang dapat diputar langsung di halaman web, <source> sebagai file video lalu width="320" menunjukkan lebar video (320 pixel) dan height="240" menunjukkan tinggi video (240 pixel), lalu controls untuk menampilkan tombol play, pause, volume, fullscreen. serta </video> menandakan akhir dari elemen video.
<source src="haijivdo.mp4" type="video/mp4"> yang berfungsi untuk menentukan file video yang diputar dan src="haijivdo.mp4" → nama file video harus sesuai, serta type="video/mp4" menunjukkan format video

Footer dan Link Sosial Media
 <p>© 2026 Nama Mahasiswa</p>
<p> digunakan untuk menampilkan teks paragraf, dimana bagian ini digunakan untuk menampilkan hak cipta (copyright) sebagai identitas pemilik website, dan </p> berfungsi untuk menutup paragraf teks yang dibuat dengan tag <p>.
    <p>
        Kunjungi:
        <a href="https://github.com/haiji27/proyek-webprograman">GitHub</a> |
        <a href="https://www.instagram.com/withjiji_?igsh=bXo5b3U5bjB6Mzhn&utm_source=qr">Instagram</a>
      Bagian ini berfungsi untuk menautkan website ke akun GitHub dan Instagram, dimana <p> digunakan untuk membuat paragraf, <a> digunakan untuk membuat link, lalu href berisi alamat tujuan link, serta tanda | sebagai pemisah antar link
    <p>
    Contact me:
     <a href="mailto:thaijijanuarli@gmail.com">Email</a> |
    </p>
    Bagian ini untuk menampilkan kontak email, dimana mailto: memungkinkan pengguna langsung membuka aplikasi email. Code ini digunakan agar pengunjung dapat menghubungi pemilik website melalui email

</body> menandakan akhir dari seluruh konten halaman, setelah code ini tidak ada lagi elemen yang ditampilkan ke browser
</html> ini berfungsi untuk menutup dokumen HTML dan menandakan bahwa struktur halaman web telah selesai

