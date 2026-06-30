# 💻 Eka Syarif Maulana - Portfolio Website

[![Repository](https://img.shields.io/badge/GitHub-Repository-blue?style=flat-square&logo=github)](https://github.com/dresar/portofolioku)
[![Tech Stack](https://img.shields.io/badge/Tech%20Stack-HTML,%20CSS,%20JS-orange?style=flat-square)](#-tech-stack)
[![Animation](https://img.shields.io/badge/Animations-AOS%20%26%20CSS-purple?style=flat-square)](#-fitur-utama--interaktivitas)

Website portofolio pribadi modern yang interaktif, responsif, dan kaya akan animasi untuk mempresentasikan profil, keahlian, proyek, dan sertifikasi dari **Eka Syarif Maulana**.

---

## 📌 Informasi Proyek

*   **Judul Project:** Eka Syarif Maulana - Personal Portfolio Website
*   **Repository URL (GitHub):** [https://github.com/dresar/portofolioku](https://github.com/dresar/portofolioku)
*   **Tech Stack:** HTML, CSS, JavaScript, Font Awesome, AOS (Animate on Scroll), SweetAlert2

---

## 📷 Foto Profil & Sertifikat

### 🧑‍💻 Foto Profil
Berikut adalah foto profil pengembang yang disematkan dalam halaman portofolio:

<p align="left">
  <img src="https://res.cloudinary.com/dpgybasuh/image/upload/v1782790021/portfolio/frud9oq4hunutdol4apr.jpg" alt="Eka Syarif Maulana" width="220" style="border-radius: 10px; border: 3px solid #3085d6; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

### 📜 Galeri Sertifikat
Koleksi sertifikat profesional yang dicantumkan dalam bagian sertifikasi portofolio:

| Sertifikat 1 | Sertifikat 2 |
| :---: | :---: |
| <img src="https://res.cloudinary.com/dpgybasuh/image/upload/v1778312830/portfolio/ktmhgcopkczncntckn8m.jpg" alt="Sertifikat 1" width="300" style="border-radius: 8px;"/> | <img src="https://res.cloudinary.com/dpgybasuh/image/upload/v1778267175/portfolio/z5jexvwberqjjl4hvq7h.png" alt="Sertifikat 2" width="300" style="border-radius: 8px;"/> |
| **Sertifikat 3** | **Sertifikat 4** |
| <img src="https://res.cloudinary.com/dpgybasuh/image/upload/v1778267171/portfolio/wiwcmdxab5wkrnpok2lk.png" alt="Sertifikat 3" width="300" style="border-radius: 8px;"/> | <img src="https://res.cloudinary.com/dpgybasuh/image/upload/v1778267166/portfolio/lrf47kc3vguqehdgyeaa.jpg" alt="Sertifikat 4" width="300" style="border-radius: 8px;"/> |

---

## 📝 Deskripsi Singkat

**Portofolioku** adalah platform portofolio web berbasis front-end statis yang dirancang secara estetis untuk merepresentasikan profil profesional, keahlian pemrograman, riwayat proyek akademis/pribadi, dan pencapaian sertifikasi dari Eka Syarif Maulana. Dengan memadukan desain responsif modern, animasi transisi scroll, dan modal galeri interaktif, website ini memberikan pengalaman pengguna (UX) yang sangat mulus dan menarik bagi para calon perekrut maupun rekan kolaborator di industri teknologi informasi.

---

## 🔍 Konten Lengkap (Project Detail)

Website ini terdiri dari 6 bagian utama yang dapat diakses dengan mudah melalui navigasi menu maupun scroll layar:

### 1. **Home Section**
*   **Tampilan Awal (Hero Area):** Menyambut pengunjung dengan animasi teks perkenalan nama dan foto profil resmi.
*   **Tagline:** Menampilkan identitas personal yang menarik: *"Fans King MU | Teknologi Informasi"*.
*   **Swipe Up Link:** Tombol penunjuk arah bawah yang menuntun pengunjung secara halus menuju bagian *About Me*.

### 2. **About Me Section**
*   Menyajikan narasi perkenalan diri sebagai programmer kreatif yang berkomitmen memberikan kontribusi maksimal dan mudah beradaptasi dengan teknologi baru.
*   Menjelaskan latar belakang studi di bidang Teknologi Informasi, partisipasi dalam kursus pengembangan web, serta pengelolaan basis data.

### 3. **Skills Section**
Kumpulan keahlian teknis yang ditampilkan menggunakan grid ikon beresolusi tinggi dengan efek AOS (Animate on Scroll) jenis *flip* dan efek *hover brightness*:
*   **HTML & CSS:** Kerangka kerja dasar dan styling web.
*   **JavaScript:** Interaktivitas dinamis pada sisi klien.
*   **PHP & SQL:** Pemrosesan backend dinamis dan manajemen database.
*   **Tailwind CSS & React JS:** Kerangka kerja CSS modern dan pustaka UI berbasis komponen.
*   **GitHub:** Version control dan kolaborasi kode.

### 4. **Project Showcase Section**
Menampilkan 4 kartu proyek utama dengan transisi arah (`fade-up-right` dan `fade-up-left`):
1.  **Niscala Website:** Desain website kafe tugas akhir semester 3 (HTML, CSS, SCSS).
2.  **Food Funday:** Projek pemrograman web kuliah semester 4 (HTML, CSS, JS).
3.  **UI/UX Zero Hunger:** Rancangan desain pengalaman pengguna bertema sosial menggunakan Figma.
4.  **Game Design (Els Coffee Roastery):** Projek akhir perancangan 3D aset/game menggunakan Blender.

### 5. **Certification Section (Interactive Lightbox)**
*   Menampilkan 4 sertifikat utama dalam bentuk kartu grid.
*   **Custom Lightbox Overlay:** Ketika tombol mata (`.icon-eye`) diklik, modal overlay skala penuh (scale 1) akan muncul menampilkan sertifikat tersebut.
*   **Carousel Navigation:** Pengguna dapat menekan tombol navigasi panah kiri/kanan untuk berpindah dari satu sertifikat ke sertifikat lainnya tanpa menutup modal terlebih dahulu.

### 6. **Social Media & Contact Section**
*   Tautan langsung ke media sosial pengembang (Instagram dan TikTok).
*   Formulir pengiriman pesan interaktif yang divalidasi langsung di sisi klien menggunakan modal SweetAlert2.

---

## ⚡ Fitur Utama & Interaktivitas

1.  **Hamburger Menu & Responsive Header:** Navigasi otomatis berubah menjadi ikon hamburger pada perangkat seluler. Transisi menu dikoordinasikan secara mulus oleh kelas CSS `ul-active` di Javascript.
2.  **Smooth Scrolling:** Navigasi internal menggunakan fungsi `scrollIntoView({ behavior: 'smooth' })` untuk transisi halaman yang elegan tanpa lompatan kasar.
3.  **Animate On Scroll (AOS):** Animasi elemen web saat pengguna melakukan scroll layar (fade, zoom, flip) untuk menjaga visual tetap hidup dan dinamis.
4.  **SweetAlert2 Alerts:**
    *   **Project Redirect Confirmation:** Dialog konfirmasi pop-up saat mengklik proyek eksternal.
    *   **Form Validation:** Peringatan kesalahan jika formulir kontak dikirim dalam keadaan kosong, serta pesan sukses jika data lengkap.
5.  **Custom Lightbox Carousel:** Sistem galeri sertifikat dengan fungsionalitas overlay, tombol tutup, dan transisi geser sebelumnya/selanjutnya menggunakan logika indeks murni JavaScript.

---

## 🤖 AI Summaries (Ringkasan AI Terperinci)

Berikut adalah 7 ringkasan teknis berbasis AI yang menjelaskan komponen arsitektur dan fungsionalitas utama di balik repositori `portofolioku`:

### 1. Struktur Folder & Organisasi Repositori
Repositori ini terstruktur dengan sangat rapi dan modular. File [index.html](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/index.html) berada di root direktori sebagai pintu masuk utama aplikasi web. Seluruh aset gaya dikelompokkan di dalam folder [style/](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/style/) (berisi [style.css](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/style/style.css)), fungsionalitas Javascript di folder [js/](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/js/) (berisi [script.js](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/js/script.js)), pustaka ikon di folder `fontawesome/`, dan seluruh gambar teknis keahlian disimpan dalam folder `img/`. Struktur ini memisahkan kekhawatiran kode (separation of concerns) dengan sangat baik.

### 2. Arsitektur HTML & Dependensi Eksternal
File [index.html](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/index.html) ditulis dengan sintaks HTML5 semantik (menggunakan tag `<section>`, `<header>`, `<ul/li>`, dan `<form>`). Dokumen ini mengintegrasikan Google Fonts (Poppins & Roboto) untuk tipografi modern, Font Awesome lokal untuk ikonografi, AOS CSS & JS melalui CDN untuk penanganan animasi scroll, serta pustaka SweetAlert2 CDN untuk menangani interaksi popup modal dialog yang interaktif.

### 3. Sistem Desain CSS & Tipografi
Gaya visual situs dikendalikan sepenuhnya melalui berkas [style.css](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/style/style.css). CSS ini mengadopsi font modern 'Poppins' dan 'Roboto', serta mendefinisikan layout berbasis flexbox dan grid. Terdapat penggunaan transisi halus (`transition: 0.3s` hingga `0.5s`) pada elemen tautan, tombol, kartu proyek, dan efek hover transisi warna oranye/biru khas yang memberikan nuansa premium pada keseluruhan portofolio.

### 4. Responsivitas dan Desain Mobile-Friendly
Antarmuka website dirancang agar fully-responsive menggunakan *media queries* CSS. Pada layar kecil (< 768px), header navigasi disembunyikan dan diubah menjadi tata letak menu vertikal overlay yang ditarik dari kanan/atas saat tombol hamburger diklik. Grid proyek dan sertifikat juga secara otomatis menyesuaikan kolomnya dari 2-4 kolom pada desktop menjadi 1 kolom vertikal yang rapi pada smartphone.

### 5. Logika Menu Navigasi Hamburger & Smooth Scroll
Logika JavaScript dalam [script.js](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/js/script.js) mengontrol perilaku interaktif navbar. Saat ikon `.hamburger-menu` diklik, sistem akan memicu `classList.toggle('ul-active')` pada elemen daftar menu. Setiap kali item menu diklik, menu overlay akan otomatis menutup kembali. Selain itu, fungsi `scrollIntoView` digunakan untuk memproses efek scroll halus ketika pengguna berpindah bagian halaman.

### 6. Mekanisme Custom Lightbox Carousel Sertifikat
Bagian sertifikat mengimplementasikan lightbox kustom tanpa library tambahan. Menggunakan kode di [script.js](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/js/script.js) (baris 34-70), setiap kartu sertifikat memiliki overlay bawaan. Saat tombol mata (`.icon-eye`) diklik, CSS transform `scale(1)` dipicu pada overlay terkait. Kode JavaScript juga mengontrol tombol navigasi kiri-kanan untuk menutup modal saat ini dan membuka modal berikutnya/sebelumnya berdasarkan manipulasi scale modal index tetangga.

### 7. Validasi Formulir & Integrasi SweetAlert2
SweetAlert2 diintegrasikan secara mendalam pada file [script.js](file:///c:/Users/NCN0C/Documents/GitHub/portofolioku/js/script.js) untuk meningkatkan user experience. Pada bagian Proyek, klik tautan luar akan memicu dialog konfirmasi SweetAlert berbentuk pertanyaan sebelum mengalihkan pengguna. Pada bagian Kontak, penyerahan formulir disaring terlebih dahulu; jika ada bidang nama, email, atau pesan yang kosong, dialog eror akan muncul. Jika lengkap, sistem akan menampilkan pesan apresiasi sukses dan mereset isi formulir ke kosong.

---

## 🛠️ Instalasi & Cara Menjalankan Secara Lokal

Untuk membuka dan menjalankan proyek ini di komputer lokal Anda, ikuti langkah-langkah mudah berikut:

1.  **Clone Repositori:**
    ```bash
    git clone https://github.com/dresar/portofolioku.git
    ```
2.  **Masuk ke Direktori Proyek:**
    ```bash
    cd portofolioku
    ```
3.  **Jalankan Aplikasi:**
    *   Cukup buka file `index.html` langsung di browser Anda (Klik dua kali pada file tersebut).
    *   *Atau* gunakan ekstensi Live Server di VS Code untuk pengalaman reload otomatis yang optimal.
