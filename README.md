# RASARA PWA

Website statis RASARA dengan PWA dasar, tanpa backend dan tanpa biaya hosting wajib.

## Isi folder
- `index.html` — halaman website (Home, Produk, Layanan, Tentang Kami, Kontak)
- `manifest.webmanifest` — metadata aplikasi
- `sw.js` — service worker dan cache offline dasar
- `assets/rasara-logo.png` — logo asli yang diberikan pemilik
- `assets/icon-192.png`, `assets/icon-512.png` — ikon instalasi yang dibuat dari logo asli

## Menjalankan secara lokal
Service worker tidak aktif jika file dibuka langsung melalui `file://`. Jalankan server lokal, misalnya dengan VS Code + ekstensi Live Server, atau:
`python -m http.server 8000`
Lalu buka `http://localhost:8000`.

## Publikasi gratis
Unggah seluruh isi folder ini ke repository GitHub, lalu aktifkan GitHub Pages (Settings → Pages → Deploy from a branch). Alternatif: drag-and-drop folder ke Netlify. Pastikan situs menggunakan HTTPS agar instalasi PWA dan service worker aktif.

## Mengganti logo
Ganti `assets/rasara-logo.png` dengan file logo baru bernama sama. Untuk ikon aplikasi, buat ulang `assets/icon-192.png` dan `assets/icon-512.png` dengan ukuran sesuai nama file.

## Mengganti foto produk
Cari elemen `<img>` di `index.html` dan ubah nilai `src` ke nama file gambar lokal, misalnya `assets/ayam.jpg`. Simpan foto di folder `assets/`. Menggunakan foto lokal membuat gambar dapat dicache dan tersedia lebih andal saat offline.

## Catatan
- Nomor WhatsApp yang dipakai: `6285701393008` (dari 0857-0139-3008).
- Facebook menggunakan tautan yang diberikan pemilik: https://www.facebook.com/share/1FKGBEgPpB/?mibextid=wwXIfr.
- Jam operasional masih meminta pelanggan konfirmasi melalui WhatsApp.
- WhatsApp memerlukan koneksi internet; transaksi tidak dapat dilakukan offline.
- Foto produk saat ini masih menggunakan gambar sementara eksternal dari Pexels.


## Pin Google Maps presisi
- Nama tempat: Telur Bebek Orange Fresh — RASARA FARM
- Koordinat pin: `-6.9553874, 109.6141583`
- Tautan tempat: https://www.google.com/maps/place/Telur+Bebek+Orange+Fresh+%E2%80%94+RASARA+FARM/@-6.9553287,109.6132336,18.5z/data=!4m6!3m5!1s0x2e70210028fff7a9:0xbdad3fd626f522a2!8m2!3d-6.9553874!4d109.6141583!16s%2Fg%2F11zyjr9lmb
- Petunjuk arah: https://www.google.com/maps/dir/?api=1&destination=-6.9553874%2C109.6141583
