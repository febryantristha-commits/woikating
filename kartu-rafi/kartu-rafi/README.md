# Kartu Ulang Tahun Kak Rafi

Pixel retro biru, 3 halaman: popup lagu -> puzzle 3x3 -> ucapan + aib + kejutan -> video.

## Jalankan di laptop
Buka folder di VS Code, klik kanan `index.html` -> Open with Live Server.
(Jangan klik dua kali filenya, karena musik dan video butuh server lokal.)

## Ganti isi
Semua teks ucapan, daftar foto aib, dan sifat-sifat ada di bagian `CFG` di dalam `index.html`
(cari komentar "ISI KARTU"). Foto ada di `assets/img`, lagu di `assets/audio`, video di `assets/video`.

## Taruh di GitHub Pages
1. Buat repo baru (pakai nama yang susah ditebak) dan upload isi folder ini.
2. Settings -> Pages -> Source: Deploy from a branch -> main / root.
3. Tunggu 1-2 menit, link-nya muncul di halaman yang sama.
Halaman sudah diberi tag noindex supaya tidak muncul di Google, tapi siapa pun yang punya link tetap bisa membukanya.
