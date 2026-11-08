# Rekonstruksi referensi

Referensi: https://art.webinvite.id/yulia-farhan/

## Observasi

HTML dan CSS publik memakai WordPress, Hello Elementor, Elementor/Pro, WeddingPress, Swiper, dan Royal/Essential Addons. Halaman terdiri dari cover personal, video pembuka Sunda, kutipan/countdown, mempelai, akad, resepsi, galeri, cerita, RSVP, hadiah, dan penutup. Kontainer isi asli memakai lebar maksimum 500 piksel. Video pembuka berdurasi 13,56 detik; teks tampil sekitar detik 8,7.

Rekaman REA pada viewport 390 × 844:

- Cover: `ev_cb81e4900d1a9c79889eccf4e2bba43c5a88097ae34afcee70a1e806f0dcab04`.
- Tombol buka dan hasil animasi: `ev_04ced3c7dc46db8aa22e01eb03dbebd3d281373ae2c1312fcb98376b7ee208c7`.

Rekaman asli menunjukkan deklarasi JavaScript ganda dan autoplay audio yang ditolak sebelum interaksi. Rekonstruksi mempertahankan struktur visual dan aset presentasi, dengan interaksi lokal yang terpisah dari layanan asli.

## Perbedaan yang disengaja

Nama, foto, keluarga, tanggal, dan lokasi menggunakan data contoh Subhan & Mutiyah. Musik memakai instrumental lokal yang sama dengan versi sebelumnya. Foto pasangan, rekening, alamat hadiah, komentar, endpoint WordPress, nonce, pelacakan, dan merek pembuat undangan asli tidak disertakan. RSVP contoh tersimpan di browser, tidak dibagikan antarpengunjung. Rekening dinonaktifkan sampai konfigurasi diisi.

## Batas verifikasi

Kemiripan visual dipandu HTML/CSS/aset publik dan rekaman browser. Tidak ada klaim bahwa backend, sumber asli, atau setiap piksel di semua perangkat identik. Penggantian foto/nama mengubah tampilan bagian personal. Daftar sumber aset ada di `public/reference/asset-manifest.json`; keberadaan URL publik bukan bukti lisensi redistribusi komersial.

## Penggantian elemen dekoratif

Struktur referensi tetap dipertahankan. Ilustrasi gedung, lanskap pepohonan, rangkaian bunga, motif gunungan, dan bingkai dekoratif aktif telah diganti dengan satu set taman paviliun dan bingkai botanikal. Alur cover, isi, galeri, jadwal, RSVP, hadiah, dan kalender tidak berubah. Pembuka memakai lapisan taman, bingkai, dan bunga yang dianimasikan dengan CSS; bukan video Gedung Sate pada referensi. Preferensi reduced motion didukung.
