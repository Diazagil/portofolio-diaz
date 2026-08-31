# Portofolio — Diaz

Website portofolio pribadi, siap di-hosting di GitHub Pages.

## Struktur
```
index.html      -> halaman utama (HTML + CSS + JS jadi satu file)
assets/
  lingulu.png   -> screenshot proyek Lingulu
  tanemin.png   -> screenshot proyek Tanemin
```

## Cara hosting di GitHub Pages

1. Buat repository baru di GitHub, misalnya `portofolio` atau `<username>.github.io`.
2. Upload semua isi folder ini (`index.html` dan folder `assets/`) ke root repository tersebut.
   - Bisa lewat web GitHub (drag & drop), atau lewat terminal:
     ```
     git init
     git add .
     git commit -m "Portofolio pertama"
     git branch -M main
     git remote add origin https://github.com/<username>/<nama-repo>.git
     git push -u origin main
     ```
3. Di repository, buka **Settings > Pages**.
4. Pada bagian **Source**, pilih branch `main` dan folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit, situs akan aktif di:
   - `https://<username>.github.io/<nama-repo>/` (repo biasa), atau
   - `https://<username>.github.io/` (jika nama repo persis `<username>.github.io`)

## Yang mungkin ingin diubah
- Link LinkedIn di bagian Kontak (`index.html`, dekat `linkedin.com/in/...`) — sesuaikan dengan URL profil LinkedIn kamu yang sebenarnya.
- Deskripsi singkat di bagian hero dan tentang, kalau mau nada bahasanya diubah.
- Tambah proyek baru dengan menduplikasi blok `.project` di bagian `#projects`.
