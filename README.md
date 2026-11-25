# Kopi Ruang: Company Profile Website

Landing page company profile untuk **Kopi Ruang**, sebuah specialty coffee café fiktif. Proyek konsep portofolio berdasarkan brief Protolabs, dirancang dan dikembangkan seolah menjadi produk nyata siap pakai.

**[Lihat Demo Live](https://kopi-ruang-website.vercel.app/)** · [Style Guide & Design System](https://kopi-ruang-website.vercel.app/style-guide.html)

> **Catatan:** ini adalah proyek konsep. Seluruh data (alamat, nomor kontak, harga, jumlah pelanggan, rating, testimoni) bersifat fiktif, dan seluruh foto dibuat dengan AI. Lihat [CREDITS.md](CREDITS.md).

<!-- Ganti dengan screenshot asli: simpan di folder docs/ lalu sesuaikan path -->
<!-- ![Desktop](docs/preview-desktop.png) -->
<!-- ![Mobile](docs/preview-mobile.png) -->

## Tentang Proyek

**Brief:** website company profile untuk café specialty coffee dengan fokus pada kualitas rasa dan suasana nyaman untuk bekerja dan berkumpul.

- **Target pengguna:** mahasiswa dan remote worker, young professional, coffee enthusiast
- **Value proposition:** biji kopi lokal berkualitas, tempat nyaman dengan WiFi cepat, desain minimal dan estetik
- **Call to action:** kunjungi café atau pesan online

## Fitur

- Landing page satu halaman dengan 9 section: Hero, Tentang, Keunggulan, Menu, Galeri, Ulasan, Lokasi, CTA, Footer
- Navbar sticky yang mengecil saat scroll, dengan menu hamburger di mobile (bisa ditutup dengan Esc)
- Menu dengan tab kategori yang bisa dinavigasi dengan keyboard (Coffee, Signature Drinks, Pastry)
- Galeri foto dengan lightbox (focus trap, navigasi panah, tutup dengan Esc)
- Dialog "Pesan Online" yang membuka WhatsApp dengan pesan terisi sesuai menu yang dipilih
- Indikator **Buka / Tutup** otomatis berdasarkan jam buka dan waktu lokal pengunjung
- Animasi muncul saat scroll yang menghormati `prefers-reduced-motion`
- Halaman [`style-guide.html`](style-guide.html) berisi token warna, tipografi, dan komponen
- Meta SEO, Open Graph, dan favicon

## Design System

| Token | Hex | Peran |
|---|---|---|
| `--green-900` | `#17291F` | Primary, section gelap |
| `--green-700` | `#22392C` | Secondary, panel di atas hijau |
| `--gold-500` | `#B39A6E` | Aksen, CTA, garis, ikon |
| `--gold-700` | `#6B5230` | Teks emas di latar terang |
| `--cream-100` | `#F5EFE3` | Background utama |
| `--beige-200` | `#E8DCC4` | Surface dan kartu |
| `--espresso-900` | `#2B1F17` | Teks utama di latar terang |
| `--sage-500` | `#7F8F7A` | Dekorasi dan border |

- **Proporsi warna:** sekitar 60% krem/beige, 30% hijau tua, 10% emas
- **Tipografi:** [Fraunces](https://fonts.google.com/specimen/Fraunces) (heading) dan [DM Sans](https://fonts.google.com/specimen/DM+Sans) (body)
- **Motif:** bentuk arch (lengkungan atas) dari logo, dipakai sebagai bingkai foto dan ornamen
- **Aksesibilitas:** kontras teks diuji terhadap WCAG AA (minimal 4,5:1)

## Tech Stack

- HTML, JavaScript, dan TypeScript (konfigurasi)
- [Tailwind CSS](https://tailwindcss.com/) v4
- [Vite](https://vite.dev/) sebagai build tool
- Deploy di [Vercel](https://vercel.com/), kode di GitHub

## Cara Menjalankan

Prasyarat: [Node.js](https://nodejs.org/) (versi LTS).

```bash
# 1. Clone repo
git clone https://github.com/irfanfahrezidesign/kopi-ruang-website.git

# 2. Pasang dependency
npm install

# 3. Jalankan server pengembangan
npm run dev

# 4. Build untuk produksi
npm run build
