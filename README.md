# MALAQBI (SIMAS - SHAKTI)

Website aplikasi MALAQBI (SIMAS - SHAKTI) — file tunggal `index.html` yang bisa langsung dihosting di GitHub Pages.

## Cara hosting di GitHub Pages

1. Buat repository baru di GitHub (bisa publik atau privat, tapi GitHub Pages gratis hanya untuk publik pada akun gratis).
2. Upload file `index.html` (dan `README.md` ini, opsional) ke repository tersebut lewat menu **Add file > Upload files**, atau lewat git:
   ```bash
   git init
   git add index.html
   git commit -m "Deploy MALAQBI website"
   git branch -M main
   git remote add origin https://github.com/USERNAME/NAMA-REPO.git
   git push -u origin main
   ```
3. Di repository, buka **Settings > Pages**.
4. Pada bagian **Source**, pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
5. Tunggu beberapa menit, situs akan aktif di:
   `https://USERNAME.github.io/NAMA-REPO/`

## Catatan
- File `index.html` bersifat mandiri (self-contained), jadi tidak perlu file tambahan lain.
- Karena ukurannya cukup besar (~2 MB), pastikan koneksi saat upload stabil.
- Jika data aplikasi disimpan di localStorage browser, data tersebut hanya tersimpan di perangkat masing-masing pengguna (tidak otomatis sinkron antar perangkat).
