# Laporan Praktikum 4 — CSS Layout

## Identitas Mahasiswa

* **Nama:** [Nama Mahasiswa]
* **NIM:** [NIM]
* **Kelas:** [Kelas]
* **Mata Kuliah:** Pemrograman Web
* **Praktikum:** 4 — CSS Layout

## 1. Tujuan Praktikum

1. Memahami struktur dasar pembuatan layout.
2. Memahami konsep box element.
3. Memahami CSS Floating.
4. Memahami HTML5 Semantic Element.
5. Membuat layout web sederhana.

## 2. Persiapan Praktikum

Pada praktikum ini, perangkat lunak yang digunakan adalah Visual Studio Code sebagai text editor dan browser untuk menampilkan hasil halaman web.

Folder utama dibuat dengan nama `Lab4Web`. Di dalam folder tersebut dibuat file `lab4_box.html` dan folder `lab4_layout` yang berisi file `home.html` serta `style.css`.

## 3. Langkah-Langkah Praktikum

### 3.1 Membuat Dokumen HTML

Langkah pertama adalah membuat file `lab4_box.html` dengan struktur dasar HTML. Dokumen berisi deklarasi HTML, bagian `head`, judul halaman, dan elemen `header` yang menampilkan tulisan Box Element.

**Tujuan:** Membuat struktur dasar dokumen HTML sebagai awal praktikum.

**Screenshot:**

![Screenshot Langkah 1](screenshots/01-dokumen-html.png)

### 3.2 Membuat Box Element

Selanjutnya, dibuat tiga elemen `div` dengan class `div1`, `div2`, dan `div3`. Setiap elemen memiliki teks Div 1, Div 2, dan Div 3.

**Tujuan:** Memahami bahwa elemen HTML dapat digunakan sebagai kotak pembentuk layout halaman web.

**Screenshot:**

![Screenshot Langkah 2](screenshots/02-box-element.png)

### 3.3 Menerapkan CSS Float Property

CSS ditambahkan untuk memberikan warna latar pada setiap kotak dan menggunakan properti `float: left` serta `padding: 10px`.

Div 1 menggunakan warna merah, Div 2 warna kuning, dan Div 3 warna hijau.

**Hasil:** Ketiga kotak ditampilkan berjajar ke arah kiri.

**Screenshot:**

![Screenshot Langkah 3](screenshots/03-css-float.png)

### 3.4 Mengatur Clearfix Element

Elemen `div4` ditambahkan setelah Div 3. Pada CSS, Div 4 diberikan warna biru, `clear: left`, dan `float: none`.

Percobaan juga dilakukan dengan mengubah nilai properti `clear` menjadi `both` dan `right` untuk mengamati perbedaannya.

**Tujuan:** Memahami penggunaan properti `clear` untuk mengatur posisi elemen terhadap elemen yang menggunakan float.

**Screenshot:**

![Screenshot Langkah 4](screenshots/04-clearfix.png)

### 3.5 Membuat Kerangka Layout Sederhana

Folder `lab4_layout` dibuat dengan dua file, yaitu `home.html` dan `style.css`. Pada file HTML dibuat kerangka layout yang terdiri dari:

* Header
* Navigasi
* Hero panel
* Main content
* Sidebar
* Footer

Elemen semantik HTML digunakan untuk membagi bagian-bagian halaman.

**Tujuan:** Membuat struktur dasar website dengan pembagian area yang jelas.

**Screenshot:**

![Screenshot Langkah 5](screenshots/05-kerangka-layout.png)

### 3.6 Mengatur CSS Dasar dan Header

File `style.css` diisi dengan pengaturan dasar, seperti reset margin dan padding, jenis font, warna teks, lebar container, posisi container, dan tampilan header.

Container menggunakan lebar 980 piksel dan margin otomatis agar berada di tengah halaman.

**Hasil:** Halaman memiliki kerangka yang lebih teratur dan header mulai memiliki tampilan sesuai modul.

**Screenshot:**

![Screenshot Langkah 6](screenshots/06-header.png)

### 3.7 Membuat Navigasi

Navigasi dibuat menggunakan elemen `nav` dan tautan `a`. CSS digunakan untuk memberikan warna latar biru, teks putih, jarak antarelemen, serta efek hover dan active.

**Hasil:** Menu Home, Artikel, About, dan Kontak ditampilkan pada bagian navigasi.

**Screenshot:**

![Screenshot Langkah 7](screenshots/07-navigasi.png)

### 3.8 Membuat Hero Panel

Hero panel diisi dengan judul Hello World!, paragraf, dan tautan Learn more. CSS mengatur warna latar abu-abu, ukuran teks, padding, dan margin.

**Hasil:** Bagian hero menjadi area pengenalan utama pada halaman website.

**Screenshot:**

![Screenshot Langkah 8](screenshots/08-hero-panel.png)

### 3.9 Mengatur Main Content dan Sidebar

Bagian main content dan sidebar diatur menggunakan properti CSS `float: left`. Lebar dan padding ditentukan agar kedua bagian dapat disusun berdampingan.

**Tujuan:** Memahami penggunaan float dalam pembuatan layout dua kolom.

**Screenshot:**

![Screenshot Langkah 9](screenshots/09-main-sidebar.png)

### 3.10 Membuat Sidebar Widget

Sidebar diisi dengan dua widget, yaitu Widget Header yang berisi daftar tautan dan Widget Text yang berisi paragraf.

CSS ditambahkan untuk mengatur border, warna judul, daftar tautan, padding, dan efek hover.

**Hasil:** Sidebar menampilkan komponen informasi tambahan di samping konten utama.

**Screenshot:**

![Screenshot Langkah 10](screenshots/10-sidebar-widget.png)

### 3.11 Mengatur Footer

Footer diatur menggunakan CSS dengan warna latar gelap, teks berwarna terang, padding, dan properti `clear: both`.

**Tujuan:** Menempatkan footer di bawah elemen-elemen yang menggunakan float.

**Screenshot:**

![Screenshot Langkah 11](screenshots/11-footer.png)

### 3.12 Menambahkan Elemen pada Main Content

Main content ditambahkan tiga kotak konten yang berisi gambar, heading, paragraf, dan tautan View detail. CSS digunakan untuk mengatur lebar kotak, posisi, perataan teks, dan bentuk gambar melingkar menggunakan `border-radius: 50%`.

**Hasil:** Konten utama menampilkan tiga kotak secara berdampingan.

**Screenshot:**

![Screenshot Langkah 12](screenshots/12-main-content.png)

### 3.13 Menambahkan Content Artikel

Dua elemen `article` ditambahkan ke main content. Setiap artikel berisi heading, gambar, dan paragraf. CSS mengatur jarak artikel, garis pemisah, serta posisi gambar menggunakan float kiri dan kanan.

**Tujuan:** Memahami penggunaan elemen artikel dan pengaturan posisi gambar pada konten web.

**Screenshot:**

![Screenshot Langkah 13](screenshots/13-artikel.png)

## 4. Tugas Praktikum

### 4.1 Membuat Halaman About

Halaman About dibuat dalam file `about.html`. Halaman ini berisi deskripsi singkat dan portfolio. Navigasi digunakan agar pengguna dapat kembali ke halaman utama atau membuka halaman lainnya.

**Screenshot:**

![Screenshot Halaman About](screenshots/14-about.png)

### 4.2 Membuat Halaman Contact

Halaman Contact dibuat dalam file `kontak.html`. Halaman ini berisi formulir dengan input Nama, Email, Message, dan tombol Kirim.

Atribut `required` digunakan pada input untuk meminta pengguna mengisi kolom sebelum formulir dapat dikirim.

**Screenshot:**

![Screenshot Halaman Contact](screenshots/15-contact.png)

## 5. Validasi HTML

Setelah semua halaman selesai dibuat, dokumen HTML diperiksa menggunakan W3C Markup Validation Service melalui tautan berikut:

https://validator.w3.org/

Validasi dilakukan untuk memeriksa struktur dan kesesuaian kode HTML. Hasil validasi dicatat berdasarkan hasil pemeriksaan aktual setiap file.

**Screenshot hasil validasi:**

![Screenshot Validasi HTML](screenshots/16-validasi.png)

## 6. Kesimpulan

Berdasarkan praktikum CSS Layout, saya mempelajari cara membuat struktur halaman web menggunakan HTML, memahami konsep box element, serta menerapkan properti CSS `float` dan `clear`.

Saya juga mempelajari penggunaan elemen semantik HTML5, pengaturan navigasi, hero panel, main content, sidebar, widget, artikel, dan footer. Selain itu, saya menerapkan materi tersebut untuk membuat halaman About dan Contact.

Praktikum ini membantu saya memahami dasar pembuatan layout website sederhana menggunakan HTML dan CSS.

## 7. Repository

Repository GitHub praktikum:

[Masukkan URL repository GitHub di sini]
