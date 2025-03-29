# LAPORAN PROYEK WEBSITE PORTFOLIO

## Deskripsi Proyek

### Tujuan
Proyek ini bertujuan untuk membuat website portfolio personal yang profesional untuk menampilkan identitas, keterampilan, dan karya-karya dari seorang developer bernama Ryan. Website ini dirancang untuk menjadi platform yang dapat digunakan untuk memperkenalkan diri kepada calon klien atau perekrut, serta menunjukkan kemampuan teknis dan proyek-proyek yang telah dikerjakan.

### Fitur Utama
1. **Tampilan Responsif**: Website dapat diakses dengan baik di berbagai perangkat, dari mobile hingga desktop
2. **Mode Tema Gelap/Terang**: Pengguna dapat beralih antara tema terang dan gelap sesuai preferensi
3. **Navigasi Intuitif**: Menu navigasi yang jelas dengan hamburger menu untuk tampilan mobile
4. **Halaman Beranda**: Menampilkan profil singkat dan ajakan untuk menjelajahi website
5. **Bagian About Me**: Informasi tentang latar belakang, keterampilan, dan keahlian
6. **Portfolio**: Galeri proyek yang telah dikerjakan dengan filter berdasarkan kategori
7. **Halaman Kontak**: Form untuk mengirim pesan dan informasi kontak lainnya
8. **Integrasi Media Sosial**: Tautan ke platform media sosial

### Teknologi yang Digunakan
1. **HTML5**: Struktur dasar website
2. **CSS3**: Styling dan animasi
   - Penggunaan CSS Variables untuk tema gelap/terang
   - Flexbox dan Grid untuk layout responsif
   - Media queries untuk responsivitas
3. **JavaScript**: Interaktivitas dan fungsi dinamis
   - Tema gelap/terang toggle
   - Validasi form kontak
   - Filter portofolio
   - Menu hamburger untuk tampilan mobile
4. **Font Awesome**: Ikon-ikon yang digunakan dalam desain
5. **Google Fonts**: Font Poppins untuk tipografi website

## Struktur Folder dan File

```
portfolio-website/
│
├── index.html              # Halaman beranda
├── portfolio.html          # Halaman portfolio/proyek
├── contact.html            # Halaman kontak
├── style.css               # File stylesheet utama
├── script.js               # File JavaScript utama
│
└── images/                 # Folder untuk menyimpan gambar
    ├── nino.jpg            # Foto profil
    ├── code.jpg            # Gambar untuk bagian About
    ├── web1.png            # Gambar portfolio (web design)
    ├── web2.jpg            # Gambar portfolio (web design)
    ├── web3.jpg            # Gambar portfolio (web design)
    ├── ui.jpg              # Gambar portfolio (UI/UX)
    ├── ui1.png             # Gambar portfolio (UI/UX)
    └── ui3.jpg             # Gambar portfolio (app development)
```

## Penjelasan Komponen

### 1. HTML Files
- **index.html**: Berisi halaman utama dengan hero section, about section, dan services section
- **portfolio.html**: Menampilkan karya-karya dalam bentuk grid dengan filter berdasarkan kategori
- **contact.html**: Berisi form kontak dan informasi kontak

### 2. CSS (style.css)
- Menggunakan CSS variables untuk manajemen warna dan tema
- Implementasi dark mode dengan attribute selector `[data-theme="dark"]`
- Penggunaan flexbox dan grid untuk layout responsif
- Media queries untuk tampilan di berbagai ukuran layar

### 3. JavaScript (script.js)
- Pengelolaan tema light/dark dengan local storage
- Toggle untuk menu mobile (hamburger menu)
- Filter untuk proyek portfolio
- Validasi form kontak
- Smooth scrolling untuk navigasi internal

## Responsivitas

Website dirancang dengan pendekatan mobile-first, memastikan tampilan yang optimal di berbagai perangkat:
- **Desktop** (> 1024px): Tampilan penuh dengan layout multi-kolom
- **Tablet** (768px - 1024px): Penyesuaian ukuran elemen dan beberapa perubahan layout
- **Mobile** (< 768px): Perubahan signifikan pada layout dengan menu hamburger dan struktur single-column

## Fitur Dark Mode

Implementasi tema gelap/terang dilakukan dengan:
1. Toggle switch di header
2. Penyimpanan preferensi pengguna menggunakan localStorage
3. Deteksi preferensi sistem (prefers-color-scheme)
4. Variabel CSS yang berbeda untuk setiap tema

## Performa dan Optimasi

1. **Font**: Menggunakan Google Fonts dengan subset yang spesifik
2. **CSS**: Struktur CSS yang terorganisir dan efisien
3. **JavaScript**: Kode JS modular dengan event listeners yang efisien

## Link Website

*Catatan: Website belum di-hosting. Link akan ditambahkan setelah proses deployment.*

## Kesimpulan dan Pengembangan Masa Depan

Proyek website portfolio ini berhasil mencapai tujuan untuk menampilkan identitas profesional, keterampilan, dan karya dari seorang developer. Website memiliki tampilan yang menarik, responsif, dan user-friendly.

Beberapa pengembangan yang dapat dilakukan di masa depan:
1. Implementasi backend untuk fungsionalitas form kontak
2. Penambahan blog untuk berbagi pengetahuan
3. Optimasi SEO untuk meningkatkan visibilitas
4. Animasi yang lebih interaktif menggunakan library seperti GSAP
5. Implementasi PWA (Progressive Web App) untuk pengalaman mobile yang lebih baik
