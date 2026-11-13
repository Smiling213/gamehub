# GameHub — Website Marketplace Game

## Menjalankan
1. Ekstrak ZIP.
2. Buka `index.html` di browser untuk melihat website.

## Sebelum dipublikasikan
1. Buka `index.html` dengan editor teks.
2. Cari `SELLER_WHATSAPP` dan ganti `6281234567890` dengan nomor WhatsApp toko (format internasional, tanpa tanda +).
3. Edit daftar `games` untuk mengganti nama, platform, genre, harga, dan warna cover.
4. Uji tombol keranjang dan pemesanan.

## Publikasi gratis ke internet (GitHub Pages)
1. Buat akun di https://github.com/ jika belum punya.
2. Buat repository baru, misalnya `gamehub`.
3. Upload `index.html` ke repository (boleh juga upload README).
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
6. Tunggu proses publikasi. GitHub akan memberi alamat gratis seperti `https://username.github.io/gamehub/`.

Alternatif hosting statis gratis: https://www.netlify.com/ atau https://vercel.com/.

## Batasan versi ini
Ini adalah starter website katalog marketplace statis. Katalog dan keranjang berjalan di browser, sedangkan checkout mengirim ringkasan pesanan ke WhatsApp penjual. Belum ada akun pembeli/penjual, database, stok real-time, pembayaran otomatis, panel admin, atau sistem escrow. Fitur tersebut memerlukan backend/database dan integrasi pembayaran yang sesuai. Jangan menerima pembayaran sebelum memverifikasi pesanan dan identitas penjual.
