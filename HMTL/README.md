# HTML: Struktur dari Halaman Web

## Basic HTML structure: 
``` <html>: Merupakan tag pembuka dan penutup utama dari sebuah dokumen HTML. Ini menandakan awal dan akhir dari seluruh kode HTML dalam halaman web. 
<head>: agian kepala dari dokumen HTML. Di sini kita meletakkan informasi meta tentang halaman, seperti judul, deskripsi, stylesheet, dan script. Informasi ini tidak langsung ditampilkan di halaman web, tetapi digunakan oleh browser dan mesin pencari. <body>: Bagian tubuh dari dokumen HTML. Di sinilah kita meletakkan semua konten yang akan ditampilkan di halaman web, seperti teks, gambar, tabel, dan formulir.
```
## Common HTML elements: 
``` <h1>: Digunakan untuk membuat judul. Tag <h1> adalah judul paling besar, dan <h6> adalah yang terkecil. 
<p>: Digunakan untuk membuat paragraf.
<a>: Digunakan untuk membuat tautan (link) ke halaman lain atau bagian lain dalam halaman yang sama.
<img>: Digunakan untuk menyisipkan gambar ke dalam halaman web.
<ul>: Digunakan untuk membuat daftar yang tidak berurutan (unordered list).
<ol>: Digunakan untuk membuat daftar yang berurutan (ordered list).
```

- Semantic HTML adalah konsep dalam pengembangan web yang berfungsi menyediakan makna atau arti lebih dalam kode HTML. Dalam semantic HTML, masing-masing elemen memiliki nama yang mencerminkan arti dari kontennya, bukan hanya presentasinya. Semantic membantu mesin pencari dan perangkat pembaca layar (screen reader) untuk memahami struktur dan konten dari halaman web dengan lebih maksimal.
Artinya,  jika kamu ingin membuat kode yang mudah dipahami, tidak hanya oleh manusia tapi juga oleh mesin, semantic HTML adalah solusi yang tepat.

## Perbedaan semantic dan non-semantic HTML
Mungkin kamu bertanya-tanya, “Apa perbedaan antara semantic HTML dan non-semantic HTML?”

## Perbedaan keduanya cukup sederhana.
Semantic HTML menggunakan elemen yang menggambarkan arti dari konten, seperti < article >, < section >, dan < nav >. Sedangkan non-semantic HTML menggunakan elemen seperti < div > dan < span > yang tidak mengungkapkan informasi apa pun tentang kontennya.

Untuk memahami lebih jelas, mari kita lihat contoh kode berikut:

## Semantic HTML:
```
<nav>
  <ul>
    <li><a href="home.html">Beranda</a></li>
    <li><a href="about.html">Tentang</a></li>
  </ul>
</nav>
```
## Non-semantic HTML:
```
  <ul>
    <li><a href="home.html">Beranda</a></li>
    <li><a href="about.html">Tentang</a></li>
  </ul>
</div>
```
Pada contoh semantic HTML, kita menggunakan tag < nav > yang secara eksplisit menunjukkan ini adalah bagian navigasi. Sedangkan pada contoh non-semantic HTML, kita menggunakan tag < div > yang tidak memberikan informasi apa pun tentang kontennya.

## Jenis-jenis Elemen Semantic HTML
``` <header>: Digunakan untuk menandai bagian kepala atau header dari sebuah halaman atau seksi. Biasanya berisi judul, logo, navigasi utama.
<nav>: Digunakan untuk menandai bagian navigasi utama dalam sebuah halaman.
<main>: Digunakan untuk menandai konten utama dari sebuah halaman.
<section>: Digunakan untuk menandai seksi-seksi dalam sebuah halaman.
<article>: Digunakan untuk menandai konten yang mandiri, seperti artikel, posting blog, atau komentar.
<aside>: Digunakan untuk menandai konten yang bersifat sampingan atau tambahan, seperti sidebar atau widget.
<footer>: Digunakan untuk menandai bagian kaki halaman, biasanya berisi informasi seperti copyright, kontak, atau tautan ke halaman lain.
```
## Tambahan
``` <figure>: Digunakan untuk menandai konten media (gambar, diagram) yang mungkin disertai dengan caption.
<figcaption>: Digunakan untuk menandai caption dari elemen <figure>.
<details>: Digunakan untuk membuat konten yang dapat diperluas atau disembunyikan.
<summary>: Digunakan sebagai judul atau label untuk elemen <details>.
```
## Semantic HTML untuk teks
Elemen untuk Menandai Teks 
``` <header>: Selain digunakan untuk header halaman, juga bisa digunakan untuk header pada bagian-bagian tertentu dalam konten.
<footer>: Selain digunakan untuk footer halaman, juga bisa digunakan untuk footer pada bagian-bagian tertentu dalam konten.
<address>: Digunakan untuk menandai informasi kontak, seperti alamat, nomor telepon, atau email.
<cite>: Digunakan untuk menandai judul karya (buku, artikel, film, dll.).
Elemen untuk Menandai Teks dengan Jenis
<code>`: Digunakan untuk menandai potongan kode komputer.
<pre>`: Digunakan untuk menampilkan teks yang telah diformat sebelumnya, seperti puisi atau kode yang ingin dipertahankan format spasi dan barisnya.
<kbd>`: Digunakan untuk menandai teks yang mewakili input dari keyboard.
<samp>`: Digunakan untuk menandai contoh output dari program komputer.
```