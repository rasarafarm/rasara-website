RASARA PWA — paket awal

Isi folder:
- index.html: website utama (responsif).
- manifest.webmanifest: metadata instalasi PWA.
- sw.js: service worker untuk cache dasar/offline shell.
- icon.svg: ikon aplikasi sederhana.

Cara mencoba:
1. Ekstrak folder ini.
2. Jalankan melalui server lokal (misalnya ekstensi Live Server di VS Code), bukan dengan membuka file HTML langsung.
3. Untuk publikasi gratis, unggah seluruh isi folder ke Netlify atau GitHub Pages. PWA membutuhkan HTTPS (localhost untuk pengujian).

WAJIB sebelum dipublikasikan:
- Ganti nomor contoh 62812345678 di seluruh index.html dengan nomor WhatsApp bisnis dalam format internasional tanpa tanda + atau spasi.
- Ganti foto ilustrasi jika ingin memakai foto produk/usaha sendiri.
- Lengkapi alamat, tautan Google Maps, Facebook, dan jam operasional yang saat ini masih berupa placeholder.

Catatan: halaman katalog saat ini belum memiliki checkout, database stok, dashboard admin, atau pembayaran online. Pemesanan diarahkan ke WhatsApp. Foto dan font dari layanan eksternal membutuhkan internet; cache PWA ini hanya menyimpan shell aplikasi.
