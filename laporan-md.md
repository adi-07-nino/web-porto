# LAPORAN PROYEK WEBSITE PORTFOLIO

## Deskripsi Proyek

### Tujuan
Proyek ini bertujuan untuk membuat website portfolio personal yang profesional untuk menampilkan identitas, keterampilan, dan karya-karya dari seorang developer bernama Ryan. Website ini dirancang untuk menjadi platform yang dapat digunakan untuk memperkenalkan diri kepada calon klien atau perekrut, serta menunjukkan kemampuan teknis dan proyek-proyek yang telah dikerjakan.

### Link Website
**https://web-porto-ecru.vercel.app/**

### Fitur Utama
1. **Tampilan Responsif**: Website dapat diakses dengan baik di berbagai perangkat, dari mobile hingga desktop
2. **Mode Tema Gelap/Terang**: Pengguna dapat beralih antara tema terang dan gelap dengan toggle CSS yang hanya membutuhkan JavaScript minimal
3. **Navigasi Intuitif CSS-Only**: Menu navigasi yang jelas dengan hamburger menu CSS-only untuk tampilan mobile tanpa ketergantungan pada JavaScript
4. **Halaman Beranda**: Menampilkan profil singkat dan ajakan untuk menjelajahi website
5. **Bagian About Me**: Informasi tentang latar belakang, keterampilan, dan keahlian
6. **Portfolio**: Galeri proyek yang telah dikerjakan dengan filter berdasarkan kategori
7. **Halaman Kontak**: Form untuk mengirim pesan dan informasi kontak lainnya
8. **Integrasi Media Sosial**: Tautan ke platform media sosial

### Teknologi yang Digunakan
1. **HTML5**: Struktur dasar website
2. **CSS3**: Styling, animasi, dan interaktivitas
   - Penggunaan CSS Variables untuk tema gelap/terang
   - CSS-only hamburger menu dengan checkbox hack
   - Flexbox dan Grid untuk layout responsif
   - Media queries untuk responsivitas
   - Selector :checked untuk implementasi toggle
3. **JavaScript (Minimal)**: Hanya untuk fungsionalitas yang memang membutuhkannya
   - Validasi form kontak
   - Filter portofolio
   - Pengalihan toggles tema dengan kode minimal
4. **Font Awesome**: Ikon-ikon yang digunakan dalam desain
5. **Google Fonts**: Font Poppins untuk tipografi website

## Struktur Folder dan File

```
portfolio-website/
│
├── index.html              # Halaman beranda dengan JS inline minimal
├── portfolio.html          # Halaman portfolio/proyek dengan JS inline minimal
├── contact.html            # Halaman kontak dengan JS inline minimal
├── style.css               # File stylesheet utama (dengan implementasi CSS untuk darkmode)
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
- Semua file HTML berisi minimal JavaScript inline untuk fungsionalitas spesifik dan toggle tema

### 2. CSS (style.css)
- Menggunakan CSS variables untuk manajemen warna dan tema
- Implementasi dark mode dengan class selector `:root.light-mode`
- Penggunaan flexbox dan grid untuk layout responsif
- Media queries untuk tampilan di berbagai ukuran layar
- CSS-only hamburger menu menggunakan checkbox hack
- Toggle tema dengan ikon matahari ☀️ dan bulan 🌙

### 3. JavaScript (Inline)
- Toggle tema light/dark dengan kode minimal di masing-masing halaman HTML
- Filter untuk proyek portfolio
- Validasi form kontak
- Smooth scrolling untuk navigasi internal

## Responsivitas

Website dirancang dengan pendekatan mobile-first, memastikan tampilan yang optimal di berbagai perangkat:
- **Desktop** (> 1024px): Tampilan penuh dengan layout multi-kolom
- **Tablet** (768px - 1024px): Penyesuaian ukuran elemen dan beberapa perubahan layout
- **Mobile** (< 768px): Perubahan signifikan pada layout dengan menu hamburger CSS-only dan struktur single-column

## Fitur Dark/Light Mode

Implementasi tema gelap/terang dilakukan dengan:
1. Toggle switch dengan ikon matahari dan bulan yang diposisikan di sudut kanan atas
2. JavaScript minimal untuk mengubah class pada elemen HTML root
3. Variabel CSS yang berbeda untuk setiap tema
4. Transisi halus antar tema untuk pengalaman pengguna yang optimal

## Performa dan Optimasi

1. **Font**: Menggunakan Google Fonts dengan subset yang spesifik
2. **CSS**: Struktur CSS yang terorganisir dan efisien, dengan penggunaan CSS untuk fungsionalitas interaktif
3. **JavaScript Minimal**: Mengurangi ketergantungan pada JavaScript untuk meningkatkan performa
4. **Menghilangkan External JS**: Semua JavaScript dipindahkan ke inline untuk mengurangi HTTP request

## Kesimpulan dan Pengembangan Masa Depan

Proyek website portfolio ini berhasil mencapai tujuan untuk menampilkan identitas profesional, keterampilan, dan karya dari seorang developer. Website memiliki tampilan yang menarik, responsif, dan user-friendly. Pendekatan CSS-first dengan JavaScript minimal meningkatkan performa dan efisiensi website.

Beberapa pengembangan yang dapat dilakukan di masa depan:
1. Implementasi backend untuk fungsionalitas form kontak
2. Penambahan blog untuk berbagi pengetahuan
3. Optimasi SEO untuk meningkatkan visibilitas
4. Implementasi PWA (Progressive Web App) untuk pengalaman mobile yang lebih baik
5. Implementasi lengkap dark/light mode yang sepenuhnya CSS-only tanpa JavaScript
