# Subhan & Mutiyah

Rekonstruksi undangan pernikahan Sunda berdasarkan https://art.webinvite.id/yulia-farhan/ . Struktur, ornamen, font, warna, dan video pembuka mengikuti referensi; nama, foto dan detail acara adalah contoh.

## Menjalankan

Node.js 20.19+ atau 22.12+.

```sh
npm install
npm run dev
npm run build
npm run preview
```

## Personalisasi

Edit teks acara di `index.html` dan samakan tanggal/jadwal/nama di `config.js`. Ganti foto contoh di `public/assets/`. Konfigurasi dinamis mengendalikan judul tab, countdown, file kalender, penerimaan RSVP, dan hadiah. Tautan nama tamu: `?to=Nama%20Tamu`. Musik: `public/assets/selamanya.wav`.

RSVP contoh disimpan lokal di browser pengunjung. Data tidak dibagikan antarpengunjung dan tidak terkirim ke mempelai. Untuk RSVP sungguhan, isi `rsvpEndpoint` dengan endpoint HTTPS yang menerima JSON `{name,attendance,message}`. Endpoint harus menyediakan validasi, CORS, penyimpanan, dan pembatasan permintaan. Rahasia backend tidak boleh diletakkan dalam frontend.

Hadiah dinonaktifkan. Konfigurasi: `gift: {bank:'Nama Bank', number:'Nomor', name:'Pemilik'}`.

## Preview

Repository public: https://github.com/schwaarzkve/undangan-subhan-mutiyah

Preview: https://schwaarzkve.github.io/undangan-subhan-mutiyah/

Push ke `main` otomatis membangun dan menerbitkan preview melalui GitHub Actions. Nama tamu bisa diisi lewat `?to=Nama%20Tamu`.

Dokumentasi rekonstruksi: `RECONSTRUCTION.md`. Sumber dan batas lisensi aset: `ASSETS.md`.
