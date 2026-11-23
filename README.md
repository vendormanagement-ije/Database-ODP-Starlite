# Dashboard Port ODP per Vendor & Stasiun

Dashboard statis (satu file `index.html`, tanpa dependensi) yang menghitung jumlah port ODP per **Vendor** dan **Stasiun** dari sheet Google **"Raw ODP Teregistrasi"**.

## Fitur
- KPI: total port, total ODP, jumlah vendor, jumlah stasiun, rata-rata port/ODP
- Top 15 vendor & top 15 stasiun (klik bar untuk filter)
- Tabel Vendor × Stasiun / Per Vendor / Per Stasiun — bisa diurutkan, dicari, dan diekspor ke CSV
- Filter vendor, stasiun, tipe port (8 / 16 / 32+ / lainnya), sembunyikan baris tanpa stasiun
- Panel kualitas data (ODP duplikat, port kosong, stasiun/vendor kosong, dll.)
- Tombol **↻ Refresh data**: mengambil data terbaru langsung dari Google Sheet (yang dipublikasikan) di browser
- Mode terang / gelap

Data snapshot sudah tertanam di `index.html`, jadi halaman langsung tampil meski offline.

## Upload ke GitHub Pages
1. Buat repository baru di GitHub, lalu upload `index.html` (dan README ini) ke root repo.
2. Buka **Settings → Pages**, pilih **Source: Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
3. Setelah 1–2 menit dashboard tersedia di `https://<username>.github.io/<nama-repo>/`.

> Catatan: siapa pun yang membuka halaman ini dapat melihat datanya. Gunakan repo privat / jangan publikasikan jika data bersifat internal.
