# JELAJAH — Lombok & Indonesia Travel Guide

Website direktori/promosi wisata menggunakan React, Vite, React Router, dan CSS custom.

## Menjalankan project

Pastikan Node.js versi 18 atau lebih baru sudah terpasang.

```bash
npm install
npm run dev
```

Buka alamat yang ditampilkan Vite, biasanya `http://localhost:5173`.

## Build untuk deployment

```bash
npm run build
npm run preview
```

Folder hasil build berada di `dist/`.

## Struktur project

```text
jelajah-react/
├── index.html
├── package.json
├── README.md
└── src/
    ├── App.jsx
    ├── main.jsx
    ├── styles.css
    └── data/
        └── destinations.js
```

## Fitur

- Beranda editorial dengan hero, kategori, destinasi unggulan, dan koleksi Lombok.
- Halaman kategori: Pantai, Bukit & Pegunungan, Air Terjun, Budaya & Religi.
- Halaman semua destinasi dengan pencarian, filter wilayah, dan pengurutan.
- Halaman detail destinasi dengan deskripsi, highlight, galeri, fasilitas, estimasi tiket, dan waktu kunjungan.
- Tombol pencarian penginapan terdekat melalui Google Maps.
- Tombol lokasi dan petunjuk arah Google Maps.
- Responsive untuk desktop, tablet, dan ponsel.

## Catatan data

Harga tiket adalah estimasi awal untuk kebutuhan demonstrasi dan perencanaan, bukan tarif resmi yang dijamin berlaku. Harga dapat berubah karena kebijakan pengelola, musim, status kawasan, jenis tiket, dan aktivitas tambahan. Selalu konfirmasi ke pengelola sebelum berangkat.

Pencarian penginapan menggunakan Google Maps Search agar pengguna dapat melihat akomodasi, jarak, ulasan, dan ketersediaan terbaru. Website ini tidak melakukan pemesanan hotel secara langsung.

Foto pada demo menggunakan URL gambar Unsplash. Untuk publikasi produksi, ganti dengan foto milik sendiri atau foto berlisensi yang sesuai, lalu simpan di `public/images/` atau layanan penyimpanan gambar.

## Deployment

Project dapat di-deploy ke Vercel atau Netlify sebagai Vite app. Build command: `npm run build`; output directory: `dist`.
