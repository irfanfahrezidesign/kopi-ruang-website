# Kredit & Inventaris Aset Gambar — Kopi Ruang

Proyek ini adalah konsep portofolio. Seluruh foto dibuat dengan AI. Seluruh data, harga, dan testimoni bersifat fiktif.

## Daftar Aset Gambar

| Nama File | Section yang Memakainya | Sumber | Catatan |
| --- | --- | --- | --- |
| `public/assets/logo.png` | Navbar, Menu Mobile, Footer (`index.html`) | Aset lampiran pemilik proyek (asal/lisensi tidak diketahui) | Logo transparan `1020×1032 px` (~107 KB); dipakai langsung di atas latar `--green-900`. |
| `src/assets/images/hero-pour-over.jpg` | Hero, Menu (V60 Single Origin), Galeri (Detail Tanaman & Seduh), Style Guide | Dibuat dengan AI (Gemini Image Generation) | `896×1200 px` (~735 KB). Ada emboss tulisan `"Kalita"` samar pada dripper keramik putih; tidak ada kemasan atau label produk. |
| `src/assets/images/tentang-interior-cafe.jpg` | Tentang Kami, Galeri (Interior Café), Style Guide | Dibuat dengan AI (Gemini Image Generation) | `896×1200 px` (~752 KB). Bersih, tidak ada tulisan atau merek terlihat. |
| `src/assets/images/menu-espresso.jpg` | Menu (Espresso), Galeri (Cangkir & Tekstur), Style Guide | Dibuat dengan AI (Gemini Image Generation) | `1200×896 px` (~828 KB). Bersih, tidak ada tulisan atau merek terlihat. |
| `src/assets/images/menu-americano.jpg` | Menu (Americano) | Dibuat dengan AI (Gemini Image Generation) | `1200×896 px` (~824 KB). Bersih, tidak ada tulisan atau merek terlihat. |
| `src/assets/images/menu-cafe-latte.jpg` | Menu (Café Latte, Oat Honey Cappuccino) | Dibuat dengan AI (Gemini Image Generation) | `1200×896 px` (~693 KB). Bersih, tidak ada tulisan atau merek terlihat. |
| `src/assets/images/menu-signature-dingin.jpg` | Menu (Kopi Ruang Latte, Pandan Cold Brew, Es Kopi Gula Aren) | Dibuat dengan AI (Gemini Image Generation) | `1200×896 px` (~763 KB). Bersih, tidak ada tulisan atau merek terlihat; saat ini dipakai ulang untuk tiga kartu minuman dingin. |
| `src/assets/images/menu-pastry.jpg` | Menu (Butter Croissant, Almond Croissant, Banana Bread, Choco Chip Cookie), Galeri (Homemade Pastries) | Dibuat dengan AI (Gemini Image Generation) | `1200×896 px` (~806 KB). Bersih, tidak ada tulisan atau merek terlihat; saat ini dipakai ulang untuk empat kartu pastry. |
| `src/assets/images/galeri-meja-kerja.jpg` | Galeri (Sudut Kerja Fokus) | Dibuat dengan AI (Gemini Image Generation) | `896×1200 px` (~685 KB). Ada tampilan antarmuka web samar di layar laptop (mirip huruf `"G"`), tanpa merek laptop terlihat. |
| `src/assets/images/galeri-bar-seduh.jpg` | Galeri (Bar Seduh) | Dibuat dengan AI (Gemini Image Generation) | `1200×896 px` (~778 KB). Ada papan menu meja bertuliskan `"Menu / Filter Coffee / Espresso / Latte"` dan kemasan kopi polos di rak belakang. |

## Catatan Migrasi WebP

Setiap foto pada `index.html` dan `style-guide.html` sudah dibungkus elemen `<picture>` dengan komentar `<source srcset="...webp" type="image/webp" />`. Setelah file `.webp` hasil kompresi ditambahkan ke `src/assets/images/`, cukup hapus tanda komentar HTML pada tag `<source>` terkait.
