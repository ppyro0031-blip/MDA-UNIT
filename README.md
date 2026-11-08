# MDA Universe

Website statis responsif dengan tampilan terinspirasi dari dua screenshot referensi MDA Universe.

## Menjalankan

1. Ekstrak ZIP.
2. Buka `index.html` di browser, atau unggah seluruh isi folder ke repository GitHub.
3. Untuk GitHub Pages: buka **Settings → Pages**, pilih branch `main` dan folder `/root`, lalu simpan.

## Fitur yang tersedia

- Halaman login dan pendaftaran akun demo (akun disimpan lokal di browser; password di-hash menggunakan PBKDF2 Web Crypto).
- Dashboard responsif dengan navigasi Beranda, Storage, Studio, Music, Community, Cerita, Pengaturan, Tentang, dan Bantuan.
- Storage menyimpan file menggunakan IndexedDB di perangkat/browser saat ini.
- Studio menerapkan filter gambar dan mengunduh hasil PNG.
- Music memutar file audio lokal.
- Cerita disimpan pada localStorage browser.
- Tombol Grup dan Saluran menuju tautan WhatsApp yang diberikan.
- Tema terang/gelap.

## Batasan penting

Ini adalah versi frontend statis. Akun, file, cerita, dan preferensi hanya tersedia di browser/perangkat tempat data dibuat; belum ada sinkronisasi antar pengguna atau perangkat. Daftar status pengguna pada dashboard adalah data contoh. Login Google/Discord/GitHub juga belum aktif.

Agar bisa dipakai sebagai layanan komunitas bersama oleh semua orang, perlu backend (misalnya Supabase atau Firebase) untuk autentikasi, database, penyimpanan cloud, dan aturan keamanan. Jangan gunakan password penting pada versi demo ini.
