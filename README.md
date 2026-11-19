# selawe.github.io
Sekedar membuat jejak, mungkin berguna suatu saat nanti

## Menjalankan secara lokal

Instal [Hugo](https://github.com/gohugoio/hugo/releases/tag/v0.170.1) versi
0.170.1, lalu jalankan `hugo server` dan buka http://localhost:1313/.
Untuk menghasilkan situs statis di `public/`, jalankan `hugo --minify`.

Artikel disimpan di `content/posts/`. Kebijakan privasi disimpan sebagai
Markdown di `unblock-cube-privacy/`. Hugo memakai nilai `url` di masing-masing
berkas untuk mempertahankan alamat `.html` yang sudah digunakan.

## GitHub Pages

Pilih **GitHub Actions** di **Settings → Pages → Build and deployment → Source**.
Workflow akan membangun dan menerbitkan situs pada setiap push ke branch
`master`. Workflow juga dapat dijalankan dari tab **Actions**.
