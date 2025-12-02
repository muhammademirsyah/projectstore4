# Ghaniyy Store - Website Redesign

## 📋 Struktur Website Baru (Multi-Page)

Website telah di-redesign dari single-page menjadi multi-page structure untuk pengalaman yang lebih baik:

### Halaman Utama:

1. **index-new.html** - Homepage Baru (Simplified)
   - Welcome Screen dengan musik
   - Logo & Nama Toko (BESAR untuk mobile)
   - Tentang Kami
   - Quick Contact
   - Footer

2. **layanan.html** - Halaman Layanan Akademik
   - Cek Turnitin (dengan gambar)
   - Jasa Parafrase
   - Publish Jurnal
   - Perbaikan Naskah
   - Pembuatan PowerPoint
   - Request Layanan Lain

3. **aplikasi.html** - Halaman Aplikasi Digital Premium
   - 14 Aplikasi Premium:
     - Canva Pro
     - CapCut Pro
     - Netflix Premium
     - Spotify Premium
     - YouTube Premium
     - Disney+ Hotstar
     - QuillBot Premium
     - ChatGPT Plus
     - Prime Video
     - DeepL Pro
     - Picsart Gold
     - Viu Premium
     - Iflix
     - Gamma

4. **kontak.html** - Halaman Kontak Lengkap
   - Contact Form
   - WhatsApp: 0895-3746-51500
   - Instagram: @ghaniyystore.official
   - Kerjasama: 0899-9123-944
   - Jam Operasional
   - FAQ

### File Lama (Masih Ada):
- **index.html** - Homepage lama (single-page)

## 🎨 Fitur Desain Baru:

### Welcome Screen
- Background putih bersih
- Logo 160px (lebih besar untuk mobile)
- Brand name 56px
- Subtitle 18px
- Button 20px padding
- Animasi floating logo

### Homepage Baru (index-new.html)
- Fokus pada brand identity
- Logo & nama toko JUMBO
- Tentang kami dengan 3 highlight boxes
- Stats: 300+ pelanggan, 4.9/5 rating, sejak 2022
- Quick contact dengan logo WA & IG
- CTA buttons ke halaman layanan & kontak

### Responsive Design
- Mobile-first approach
- Viewport responsive (width=device-width)
- Mobile menu toggle
- Card layouts yang flexible
- Touch-friendly button sizes

### Animasi
- Subtle pulse pada buttons & cards
- Fade in effects
- Logo floating
- Gradient flow pada text
- Smooth transitions

## 📱 Navigasi:

Header Navigation (semua halaman):
- **Home** → index-new.html
- **Layanan Akademik** → layanan.html
- **Aplikasi Digital** → aplikasi.html
- **Kontak** → kontak.html
- **WhatsApp Button** (floating)

## 🎵 Musik Background:

- Musik hanya di homepage (index-new.html)
- Dimulai saat klik tombol "Masuk Website" di welcome screen
- Volume 0.3 (tidak terlalu keras)
- Tidak ada toggle button (musik langsung jalan)

## 🎯 Keunggulan Desain Baru:

1. **Lebih Profesional**: Setiap kategori punya halaman sendiri
2. **Mobile Friendly**: Elemen lebih besar, mudah di-tap
3. **Loading Lebih Cepat**: Konten dipecah per halaman
4. **SEO Better**: Setiap halaman punya fokus yang jelas
5. **User Experience**: Navigasi lebih intuitif
6. **Scalable**: Mudah menambah layanan/aplikasi baru

## 📝 Cara Pakai:

### Development (Local):
```bash
# Buka dengan Live Server atau langsung buka file
index-new.html
```

### Deployment:
Upload semua file ke hosting:
- index-new.html (set sebagai default homepage)
- layanan.html
- aplikasi.html
- kontak.html
- src/css/styles.css
- src/js/app.js
- src/js/products.js
- assets/* (semua gambar)

## 🔄 Perbandingan:

| Feature | Old (index.html) | New (index-new.html) |
|---------|-----------------|---------------------|
| Structure | Single Page | Multi Page |
| Welcome Logo | 120px | 160px |
| Navigation | Anchor links | Page links |
| Mobile View | Fixed viewport | Responsive |
| Content | Semua di 1 page | Terbagi per kategori |
| Loading | Heavy | Lighter |

## 🚀 Next Steps (Optional):

1. Tambah halaman "Tentang Kami" lengkap dengan sejarah toko
2. Tambah halaman "Testimoni" pelanggan
3. Tambah halaman "Cara Order" step-by-step
4. Tambah Blog untuk tips akademik
5. Integra dengan payment gateway

## 📞 Kontak:

- WhatsApp: 0895-3746-51500
- Instagram: @ghaniyystore.official
- Kerjasama: 0899-9123-944

---

**Dibuat dengan ❤️ untuk Ghaniyy Store**
*Redesigned: 2024*
