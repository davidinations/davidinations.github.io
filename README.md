# Portofolio Data Analytics (GitHub Pages)

Repo ini berisi situs portofolio statis yang di-hosting melalui GitHub Pages. Fokus utamanya adalah menunjukkan kemampuan data analytics lewat dashboard Power BI yang saya buat dari pengalaman kerja sebelumnya.

## Isi repo

- `index.md` — halaman utama yang dirender oleh Jekyll (Ruby/Markdown) dan berisi dua screenshot dashboard Power BI.
- `_config.yml` — konfigurasi tema GitHub Pages.
- `Screenshot Dashboard Monitoring Line Production Machine.png` — dashboard monitoring mesin dan lini produksi.
- `Screenshot Overall Production.png` — dashboard ringkasan produksi keseluruhan.

## Dashboard yang ditampilkan

1. Monitoring Line Production Machine
2. Overall Production

## Menjalankan secara lokal

Pastikan Ruby dan Jekyll sudah terpasang, lalu jalankan:

```bash
bundle exec jekyll serve
```

Buka `http://localhost:4000` di browser.

## Deploy

Setiap push ke branch `main` akan otomatis di-build dan dipublikasikan oleh GitHub Pages.
