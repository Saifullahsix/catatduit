# CatatDuit PWA

Aplikasi pencatat keuangan pribadi berbasis Progressive Web App (PWA).

## Struktur

- `index.html` — aplikasi utama
- `manifest.webmanifest` — metadata instalasi PWA
- `sw.js` — service worker dan cache offline
- `icon-180.png` — ikon Apple touch
- `icon-192.png` — ikon PWA
- `icon-512.png` — ikon PWA resolusi tinggi

## Menjalankan lokal

Gunakan server lokal, bukan membuka `index.html` langsung dengan `file://`. Contoh:

```bash
python3 -m http.server 8080
```

Lalu buka `http://localhost:8080/`.

## Deploy

Project ini siap dideploy ke hosting HTTPS seperti GitHub Pages.
